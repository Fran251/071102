# 071102

[Uploadin<!DOCTYPE html>[Uploading script.js…]document.addEventListener("DOMContentLoaded", function() {
    const audio = new Audio("love.mp3"); 
    
    const playAudio = () => {
        audio.play().catch(error => {
            console.log("Reproducción automática bloqueada, esperando interacción del usuario.");
        });
    };
    
    playAudio();
    
    document.body.addEventListener("click", () => {
        audio.play();
    }, { once: true });
});

document.addEventListener('contextmenu', function (e) {
  e.preventDefault();
});

document.addEventListener('keydown', function (e) {
  if (e.key === 'F12') {
    e.preventDefault();
  }
  if (e.ctrlKey && e.shiftKey && e.key === 'I') {
    e.preventDefault();
  }
  if (e.ctrlKey && e.key === 'u') {
    e.preventDefault();
  }
});()

<html lang="en">
<head>[Carta.pdf](https://github.com/user-attachments/files/19383540/Carta.pdf)

  <meta charset="UTF-8">
  <title>Mi negrita ❤️</title>
  <link href="https://fonts.googleapis.com/css?family=Indie+Flower" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Great+Vibes|Dancing+Script|Parisienne|Sacramento|Allura|Satisfy|Tangerine" rel="stylesheet">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="./style.css">
</head>
<body>
<div class='wrapper'>
  <div class='plant'>
    <div class='flower'>
      <div class='head'>
        <div class='face'></div>
      </div>
    </div>
    <div class='leaf__one'></div>
    <div class='leaf__two'></div>
    <div class='leaf__three'></div>
  </div>
  <div class='pot'>
    <div class='top'></div>
  </div>
  <div class='text'> Feliz 21 tolot🌻❤️
    <br>
  </div>
  
  <div class="download-section">
    <a href="./Carta.pdf" download="Carta.pdf">
      <button>Carta 📩</button>
    </a>
  </div>
</div>
<div class='whitespace'></div>

<!-- 

Buy me a coffee:

    * https://buymeacoffee.com/alexx.dev
    * https://www.tiktok.com/@alexx.dev?is_from_webapp=1&sender_device=pc  

-->

<script src="script.js"></script>

</body>
</html>
g index.html…]()
