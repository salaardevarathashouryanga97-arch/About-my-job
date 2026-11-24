# About-my-job
About my job

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Little Surprise 💌</title>
<style>
* { box-sizing: border-box; }
body {
  margin: 0;
  min-height: 100vh;
  background: linear-gradient(135deg,#ffe0ec,#fff4f5,#fce4ec);
  font-family: Georgia, serif;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #91435f;
  padding: 20px;
}
.card {
  background: white;
  padding: 32px 22px;
  border-radius: 25px;
  max-width: 420px;
  width: 100%;
  box-shadow: 0 10px 35px #c76b8630;
}
h1 { color: #c34f7b; }
.envelope { font-size: 90px; animation: bounce 1.5s infinite; }
@keyframes bounce {
  50% { transform: translateY(-10px); }
}
button {
  background: #d85d89;
  color: white;
  border: 0;
  padding: 14px 25px;
  border-radius: 30px;
  font-size: 17px;
  cursor: pointer;
  margin-top: 15px;
}
#letter { display: none; line-height: 1.8; }
.message {
  background: #fff0f5;
  border-radius: 18px;
  padding: 20px;
  margin-top: 20px;
}
.ending { font-size: 24px; font-weight: bold; color: #c34f7b; }
</style>
</head>
<body>
<div class="card">
  <div id="welcome">
    <div class="envelope">💌</div>
    <h1>Hey Maya! 🌸</h1>
    <p>Someone has a little message for you...</p>
    <button onclick="openLetter()">Open your surprise ❤️</button>
  </div>

  <div id="letter">
    <h1>Dear Maya, 💗</h1>
    <div class="message">
      <h2>The Lid = Delete 😂</h2>
      <p>Please smile, because your smile adds to your beauty!</p>
      <p>They say smiling can boost your mood, reduce stress and make life happier.</p>
      <p>Don't smile for other people. Please smile for yourself.</p>
      <p>You don't have to smile every time, but never forget how beautiful your smile is!</p>
      <p>Keep smiling, Maya! 😊❤️</p>
    </div>
    <p class="ending">THE LID = DELETE 😂</p>
    <p>From your unofficial smile reminder 💌</p>
  </div>
</div>
<script>
function openLetter() {
  document.getElementById("welcome").style.display = "none";
  document.getElementById("letter").style.display = "block";
}
</script>
</body>
</html>
