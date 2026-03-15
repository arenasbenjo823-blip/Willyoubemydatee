```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Can You Be My Date? 💕</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;700;800;900&display=swap" rel="stylesheet">

<link rel="stylesheet" href="style.css">
</head>

<body>

<div class="hearts-bg"></div>

<div class="container">

<h1>CAN YOU BE MY DATE? 💕</h1>

<div class="gif-container">
<img id="cat-gif"
src="https://media.tenor.com/EBV7OT7ACfwAAAAj/u-u-qua-qua-u-quaa.gif"
alt="cute character">
</div>

<div class="buttons">
<button id="yes-btn" onclick="handleYesClick()">Yes 💘</button>
<button id="no-btn" onclick="handleNoClick()">No 😢</button>
</div>

<div id="tease-toast"></div>

</div>

<audio id="bg-music" loop autoplay muted>
<source src="music/beabadoobee - Glue Song (Lyrics).mp3" type="audio/mpeg">
</audio>

<button id="music-toggle" onclick="toggleMusic()" title="Toggle music">🔊</button>

<script>
function handleYesClick(){
    window.location.href="https://sahilgogna.github.io/v-day/yes.html";
}
</script>

<script src="script.js"></script>

</body>
</html>
```
