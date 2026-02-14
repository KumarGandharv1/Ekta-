<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ekta ❤️ 14 Years</title>

<style>
body {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(135deg, #ff758c, #ff7eb3);
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  text-align: center;
  color: white;
}

.container {
  background: rgba(255,255,255,0.15);
  backdrop-filter: blur(12px);
  padding: 40px 25px;
  border-radius: 25px;
  width: 90%;
  max-width: 450px;
  box-shadow: 0 25px 50px rgba(0,0,0,0.25);
}

.gallery img {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 15px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.25);
}

p {
  font-size: 15px;
  line-height: 1.6;
}

button {
  margin: 10px;
  padding: 12px 25px;
  border-radius: 50px;
  border: none;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s ease;
}

#yes {
  background: white;
  color: #ff4d6d;
}

#no {
  background: #ff4d6d;
  color: white;
}

button:hover {
  transform: scale(1.08);
}

.hidden {
  display: none;
}

.final {
  font-size: 18px;
  margin-top: 20px;
}
</style>
</head>

<body>

<div class="container">

  <h2>Ekta ❤️</h2>

  <div class="gallery">
    <img src="photo1.jpg" alt="Memory 1">
    <img src="photo2.jpg" alt="Memory 2">
  </div>

  <p id="message">
    14 years together… and now we are about to get married. 💍<br><br>
    Every laugh, every memory, every second with you is priceless.  
    I cannot forget a single moment spent with you.  
    You are my forever. ❤️<br><br>
    So tell me...
  </p>

  <h3>Will you be my Valentine — forever? 💖</h3>

  <button id="yes" onclick="sayYes()">YES ❤️</button>
  <button id="no" onclick="noClicked()">NO 😜</button>

  <div id="finalMessage" class="final hidden">
    💞 From 14 years… to forever. 💞<br>
    I love you endlessly, Ekta. ❤️
  </div>

</div>

<script>

let noCount = 0;

function noClicked() {
  noCount++;

  if(noCount == 1) {
    document.getElementById("message").innerHTML =
    "Ektaaa 😏 After 14 years… this is your answer?";
  }
  else if(noCount == 2) {
    document.getElementById("message").innerHTML =
    "Think again… we are literally getting married soon 💍❤️";
  }
  else if(noCount == 3) {
    document.getElementById("message").innerHTML =
    "Okay okay… clearly the only correct answer is YES 😌";
    document.getElementById("no").style.display = "none";
  }
}

function sayYes() {
  document.getElementById("finalMessage").classList.remove("hidden");
  document.getElementById("yes").style.display = "none";
  document.getElementById("no").style.display = "none";
}

</script>

</body>
</html>
