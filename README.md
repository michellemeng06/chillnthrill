<html>
<head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Reenie+Beanie&display=swap" rel="stylesheet">
  <style>
    
    body {
      background-color: #000000;
      margin: 0;
      position: relative; 
    }

    img {
      display: block;
      width: 100%;
      height: auto;
    }

  
.window {
  position: absolute; 
  top: 34%; 
  left: 40%; 
  transform: translate(-50%, -50%); 
  z-index: 1; 
  width: 50%; 
  max-width: 250px; 
  height: auto; 
}
    .desk {
      position: absolute; 
      top: 67%; 
      left: 59%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 15%; 
      max-width: 150px; 
      height: auto;  
    }
    
    .coat {
      position: absolute; 
      top: 53%; 
      left: 74%; 
      transform: translate(-50%, -50%); 
      
      width: 70%; 
      max-width: 450px; 
      height: 400px;  
    }
    .art {
      position: absolute; 
      top: 40%; 
      left: 59%; 
      transform: translate(-50%, -50%); 
      z-index: 3; 
      width: 30%; 
      max-width: 200px; 
      height: auto;  
    }
    .art2 {
      position: absolute; 
      top: 40%; 
      left: 67%; 
      transform: translate(-50%, -50%); 
      z-index: 3; 
      width: 30%; 
      max-width: 200px; 
      height: auto;  
    }
    .art3 {
      position: absolute; 
      top: 40%; 
      left: 53%; 
      transform: translate(-50%, -50%); 
      z-index: 3; 
      width: 30%; 
      max-width: 200px; 
      height: auto;  
    }
    .art4 {
      position: absolute; 
      top: 39%; 
      left: 28%; 
      transform: translate(-50%, -50%); 
      z-index: 3; 
      width: 30%; 
      max-width: 200px; 
      height: auto;  
    }
    .bear {
      position: absolute; 
      top: 58%; 
      left: 31%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 10%; 
      max-width: 100px; 
      height: auto;  
    }
    .world {
      position: absolute; 
      top: 56%; 
      left: 61.2%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 29%; 
      max-width: 150px; 
      height: auto;  
    }
    
    .clothing2 {
      position: absolute; 
      top: 59%; 
      left: 48.9%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 29%; 
      max-width: 150px; 
      height: auto;  
    }
    .candle {
      position: absolute; 
      top: 58.45%; 
      left: 56%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 10%; 
      max-width: 70px; 
      height: auto;  
    
    }
    .chair {
      position: absolute; 
      top: 67%; 
      left: 66%; 
      transform: translate(-50%, -50%); 
     z-index: 1;
      width: 50%; 
      max-width: 590px; 
      height: auto;  
    }
    .man {
      
          position: absolute;
          top: 80%;
          left: -20%;
          transform: translate(-50%, -50%);
        z-index: 20;
          width: 1100px;
          height: 800px;
          animation: moveMan 2s ease-in forwards;
          pointer-events: none;
      
    }
    
    
    @keyframes moveMan {
      0% {
        left: -20%; 
      }
      100% {
        left: 120%; 
      }
    }
    .couch {
      position: absolute; 
      top: 60%; 
      left: 40%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 30%; 
      max-width: 400px; 
      height: auto; 
    }
    .vase {
      position: absolute; 
      top: 58%; 
      left: 24%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 30%; 
      max-width: 150px; 
      height: auto; 
    }
    .title {
      position: absolute; 
      top: 25%; 
      left: 63.5%; 
      transform: translate(-50%, -50%); 
      z-index: 1; 
      width: 30%; 
      max-width: 600px; 
      height: auto; 
    }
    .clothing {
      position: absolute; 
      top: 52%; 
      left: 74.5%; 
      transform: translate(-50%, -50%); 
      z-index: 4; 
      width: 29%; 
      max-width: 350px; 
      height: auto;  
    }
    .reenie-beanie-regular {
      font-family: "Reenie Beanie", cursive;
      font-weight: 400;
      font-style: normal;
      color: #f5f5f2;
      position: absolute;
      top: 230px; 
      right: 585px; 
      margin: 0;
      z-index: 30;
   
    }

    .reenie-beanie-regular a {
      color: #f18926; 
      text-decoration: none; 
    }

    .reenie-beanie-regular a:hover {
      color: #af1a1f; 
    }
    .halloween {
      font-family: "Reenie Beanie", cursive;
      font-weight: 400;
      font-style: normal;
      color: #f5f5f2;
      position: absolute;
      top: 230px; 
      right: 325px; 
      margin: 0;
      z-index: 30;
    }

    .halloween a {
      color: #f18926; /* Default link color */
      text-decoration: none; /* Remove underline */
    }
   

    .halloween a:hover {
      color: #af1a1f; /* Hover color */
    }
    .audio-button {
      font-family: "Reenie Beanie", cursive;
      font-weight: 400;
      font-style: normal;
      color: #f5f5f2;
      position: absolute; 
      top: 160px; 
      left: 394px; 
      transform: translateX(-50%); 
      z-index: 10; 
      text-decoration: none;
    }
  

    .audio-button:hover {
      color: #af1a1f; 
    }
    h1.audio-button {
      color: #f18926; /* Default text color (orange) */
    }

    h1.audio-button:hover {
      color: #af1a1f; /* Change color on hover */
    }
    .audio-button {
      cursor: pointer; /* Ensures the cursor is a pointer (hand) */
    }
    .textt {
      font-family: "Reenie Beanie", cursive;
      font-weight: 400;
      font-size: 20;
      font-style: normal;
      color: #f5f5f2;
      position: absolute; 
      top: 142px; 
      left: 1000px; 
      transform: translateX(-50%); 
      z-index: 10; 
      text-decoration: none;
    }
    .textt2 {
      font-family: "Reenie Beanie", cursive;
      font-weight: 400;
      font-size: 20;
      font-style: normal;
      color: #f5f5f2;
      position: absolute; 
      top: 380px; 
      left: 894px; 
      transform: translateX(-50%); 
      z-index: 10; 
      text-decoration: none;
    }
    .textt3 {
      font-family: "Reenie Beanie", cursive;
      font-weight: 400;
      font-size: 20;
      font-style: normal;
      color: #af1a1f;
      position: absolute; 
      top: 395px; 
      left: 888px; 
      transform: translateX(-50%); 
      z-index: 10; 
      text-decoration: none;
    }
  </style>
</head>
<body>
  
  <h1 class="audio-button" onclick="playAudio('additionalTrack')">play lo-fi</h1>

   
  <audio id="additionalTrack" src="lofi.mp3" preload="auto" loop></audio>


  <h1 class="reenie-beanie-regular">open the <a href="https://hack.club/boba-manor">door</a></h1>
  
  <img src="bg.png" alt="Background Image">
   <h1 class="halloween"><a href="https://open.spotify.com/playlist/7IHm4LT0DLB1kJwgbNtRVU?si=a70269a47a084245">halloween playlist</a></h1>
  

  <audio src="scary.mp3" autoplay loop></audio>
  
  <img class="couch" src="couch.png" alt="Couch Image"> 
  
  <img class="desk" src="desk.png" alt="Desk Image"> 
  <img class="candle" src="candle.png"alt="Candle Image">
 
  <a href="https://www.youtube.com/watch?v=E7U2_ojLd1o&ab_channel=NeoScaryGodmother">
    <img class="window" src="window.gif" alt="Window Gif">
  </a>

  <img class="clothing" src="clothing.png"alt="Clothing Image">
   <img class="coat" src="coat.png"alt="Coat Image">
   <img class="art" src="art.png"alt="art Image">
  <img class="man" src="man.png" alt="Man Image">

   <img class="bear" src="bear.png"alt="Bear Image">
  
    <img class="art2" src="art2.png" alt="Art2 Image">
  
  
  
  
    <img class="art3" src="art3.png" alt="Art3 Image">
 
  <a href="https://www.youtube.com/watch?v=03U4I2LKmZw&ab_channel=LIGHTSAREOFF">
    <img class="art4" src="art4.png" alt="Art4 Image">
  </a>
    <img class="world" src="world.png"alt="World Image">
  <img class="vase" src="vase.png"alt="Vase Image">
   <img class="chair" src="chair.png"alt="Chair Image">
  <a href="https://www.canva.com/design/DAGTeh7OYTg/j3K7PTMRuSAi8TVQRm8LIw/view?utm_content=DAGTeh7OYTg&utm_campaign=designshare&utm_medium=link&utm_source=editor">
    <img class="title" src="title.png" alt="Title Image">
  <img class="clothing2" src="clothing2.png"alt="Clothing2 Image">
  <img class="clothing" src="clothing.png"alt="Clothing Image">
   <h1 class="textt">welcome to the chill 'n thrill room!</h1>
  <h1 class="textt2">explore for easter eggs and have fun.</h1>
  <h1 class="textt3">p.s., scroll to the right, if you dare...</h1>


  
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>chill 'n thrill 🎃🎶</title>
  <style>
    button {
        position: absolute; /* Position it relative to the nearest positioned ancestor */
        top: 40px; /* Adjust the vertical position as needed */
        left: 40px; /* Adjust the horizontal position as needed */
        font-family: "Reenie Beanie", cursive;
        font-size: 16px; /* Adjust size as needed */
        color: #f18926; /* Match link color */
        background: none; /* Remove background */
        border: none; /* Remove border */
        cursor: pointer;
        text-decoration: underline; /* Underline to match link text */
        z-index: 2; /* Ensure it's above the background */
    }
    .play-sound:hover {
        color: #af1a1f; /* Change to your desired hover color */
    }

    .play-sound {
        position: absolute; /* Position it relative to the nearest positioned ancestor */
        top: 193px; /* Adjust the vertical position as needed */
        left: 345px; /* Adjust the horizontal position as needed */
        font-family: "Reenie Beanie", cursive;
        font-size: 30px; /* Adjust size as needed */
        color: #f18926; /* Match link color */
        cursor: pointer; /* Change the cursor to pointer */
        text-decoration: none; /* Underline to match link text */
        z-index: 2; /* Ensure it's above the background */
    }

    
  </style>
</head>
<body>

  <h1 id="playAudio" class="play-sound">play sound</h1>
   

  <audio id="backgroundAudio" src="scary.mp3" loop></audio>

  <script>
    document.getElementById('playAudio').addEventListener('click', function() {
      var audio = document.getElementById('backgroundAudio');
      audio.play();
    });

    function playAudio(trackId) {
      const audio = document.getElementById(trackId);
      audio.play();
    }
    document.getElementById('playAudio').addEventListener('click', function() {
        var audio = document.getElementById('backgroundAudio');
        audio.play();
    });
  </script>

</body>
  
  
</html>
