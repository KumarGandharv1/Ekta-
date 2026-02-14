<!DOCTYPE html>
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
  height: 100vh;
  text-align: center;
  color: white;
}

.container {
  background: rgba(255,255,255,0.15);
  backdrop-filter: blur(12px);
  padding: 40px 30px;
  border-radius: 25px;
  width: 90%;
  max-width: 420px;
  box-shadow: 0 25px 50px rgba(0,0,0,0.25);
}

h1 {
  font-size: 26px;
  margin-bottom: 15px;
}

p {
  font-size: 16px;
  line-height: 1.6;
  margin-bottom: 25px;
}

button {
  background: white;
  color: #ff4d6d;
  border: none;
  padding: 14px 30px;
  font-size: 16px;
  border-radius: 50px;
  cursor: pointer;
  font-weight: bold;
  transition: 0.3s ease;
}

button:hover {
  transform: scale(1.08);
  box-shadow: 0 10px 25px rgba(0,0,0,0.25);
}

.hidden {
  display: none;
}

.celebration {
  font-size: 20px;
  margin-top: 20px;
}
</style>
</head>

<body>

<div class="container">
  <h1 id="title">Ekta ❤️</h1>

  <p id="message">
    14 years together… and now we are about to get married. 💍<br><br>
    This journey has been nothing less than magical.  
    Every laugh, every fight, every memory —  
    I cannot forget a single moment spent with you.  
    You have been my best friend, my strength, my forever. ❤️<br><br>
    So today, I want to ask you something special…
  </p>

  <h2>Will you be my Valentine — forever? 💖</h2>

  <button onclick="sayYes()">YES, Always ❤️</button>

  <div id="finalMessage" class="celebration hidden">
    💞 You are my 14 years, my today, and my forever. 💞<br>
    I love you, Ekta. ❤️
  </div>
</div>

<script>
function sayYes() {
  document.getElementById("finalMessage").classList.remove("hidden");
}
</script>

</body>
</html>
