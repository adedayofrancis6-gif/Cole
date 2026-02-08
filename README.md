#<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Adebisi ❤️</title>

<style>
body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(to bottom, #ff758c, #ff7eb3);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: Arial, sans-serif;
  overflow: hidden;
}

.box {
  width: 200px;
  height: 200px;
  background: #e63946;
  position: relative;
  cursor: pointer;
  border-radius: 12px;
}

.lid {
  width: 200px;
  height: 60px;
  background: #c1121f;
  position: absolute;
  top: -60px;
  left: 0;
  border-radius: 12px 12px 0 0;
  transition: 0.7s;
}

.ribbon {
  width: 30px;
  height: 200px;
  background: gold;
  position: absolute;
  left: 85px;
}

.message {
  display: none;
  text-align: center;
  color: white;
  padding: 20px;
  max-width: 90%;
  animation: fadeIn 2s ease;
}

.message img {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  border: 4px solid white;
  margin-bottom: 15px;
}

.message h1 {
  font-size: 26px;
}

.message p {
  font-size: 16px;
  line-height: 1.6;
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}

.heart {
  position: absolute;
  font-size: 22px;
  animation: float 4s infinite;
}

@keyframes float {
  0% {transform: translateY(0); opacity: 1;}
  100% {transform: translateY(-600px); opacity: 0;}
}
</style>
</head>

<body>

<!-- Online Love Music -->
<iframe width="0" height="0"
src="https://www.youtube.com/embed/450p7goxZqg?autoplay=1&loop=1"
allow="autoplay">
</iframe>

<!-- Gift Box -->
<div class="box" onclick="openGift()">
  <div class="lid" id="lid"></div>
  <div class="ribbon"></div>
</div>

<!-- Message -->
<div class="message" id="message">
  <img src="adebisi.jpg" alt="Adebisi">
  <h1>Happy Valentine’s Day ❤️</h1>
  <p>
    My dearest Adebisi,<br><br>

    From the very first moment you walked into my life, you brought a kind of light I never knew I was missing.
    Loving you has been the easiest and most beautiful thing my heart has ever done.
    You make ordinary days feel special, and even the hardest moments feel lighter just because you’re in them.<br><br>

    Your smile calms me, your voice comforts me, and your presence alone gives me peace.
    You are not just my girlfriend, you are my safe place, my happiness, and my greatest blessing.
    With you, love feels pure, real, and intentional.<br><br>

    On this Valentine’s Day and every day after, I want you to know that my heart chooses you again and again.
    I promise to love you genuinely, respect you deeply, and stand by you no matter what life brings.
    You are my today, my tomorrow, and my always.<br><br>

    Thank you for loving me the way you do.
    Thank you for being you.
    I am grateful for you more than words can ever explain.<br><br>

    <strong>Forever yours,<br>
    Cole ❤️</strong>
  </p>
</div>

<script>
function openGift() {
  document.getElementById("lid").style.transform = "rotateX(150deg)";
  document.querySelector(".box").style.display = "none";
  document.getElementById("message").style.display = "block";

  for (let i = 0; i < 20; i++) {
    let heart = document.createElement("div");
    heart.className = "heart";
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.bottom = "0px";
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 4000);
  }
}
</script>

</body>
</html> Cole
