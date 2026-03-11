<!DOCTYPE html>
<html>
<body>
  <button onclick="playSound()">Нажми меня 😊</button>
  <script>
    function playSound() {
      var audio = new Audio('sound.mp3');
      audio.volume = 1.0;
      audio.play();
    }
  </script>
</body>
</html>
