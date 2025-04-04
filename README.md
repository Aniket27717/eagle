<!doctype html>
<html> 
 <head> 
  <link rel="stylesheet" href="style.css"> 
 </head> 
 <body> 
  <header> 
   <nav> 
    <div class="nav"> 
     <h2 class="nav-2">Warning ⚠️ </h2> 
    </div> 
   </nav> 
  </header> 
  <div class="warn"> 
   <h3>"Accessing <span class="span-1" style="color: white;">restricted</span> protocols.. <br> Are you sure you want to continue?"</h3> 
  </div> 
  <audio id="audio-1" controls> 
   <source src="https://raw.githubusercontent.com/Aniket27717/-/main/click-47609.mp3" type="audio/mpeg"> Your browser does not support the audio element. 
  </audio> 
  <script>
      function playAudio() {
        var audio = document.getElementById('audio-1');
        audio.play();  

        // When audio ends, perform an action (e.g., open a file or URL)
        audio.onended = function() {
            window.location.href = "index2.html"; // Replace with your desired action
        };
      }
  </script> 
  <div class="circle"> 
   <div class="circle-1"></div> 
   <div class="circle-2"></div> 
   <div class="circle-3"></div> 
   <div class="circle-4"></div> 
   <div class="circle-5"></div> 
   <div class="circle-6"></div> 
   <div class="circle-7"></div> 
   <div class="circle-8"> <button class="btn-1" onclick="playAudio()">Click</button> 
   </div> 
  </div> 
 </body>
</html>
