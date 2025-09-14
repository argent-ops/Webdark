<!DOCTYPE html>  
<html>  
<head>  
<title>⚠️ Alerte Virus ⚠️</title>  
<style>  
body {  
  margin: 0;  
  height: 100vh;  
  background-color: black;  
  color: red;  
  display: flex;  
  justify-content: center;  
  align-items: center;  
  flex-direction: column;  
  font-family: Arial, sans-serif;  
  font-size: 2em;  
}  
#warning {  
  animation: blink 0.5s infinite;  
}  
@keyframes blink {  
  0% {opacity: 1;}  
  50% {opacity: 0;}  
  100% {opacity: 1;}  
}  
</style>  
</head>  
<body>  
<h1 id="warning">⚠️ BOOM ! Virus détecté ⚠️</h1>  
<p id="sub">Votre téléphone est infecté… (Fake prank)</p>  
  
<audio id="sound" autoplay>  
  <source src="https://www.soundjay.com/misc/sounds/bell-ringing-05.mp3" type="audio/mpeg">  
</audio>  
  
<script>  
function endPrank() {  
  document.body.innerHTML = "<h1>💥 PRANK TERMINÉ 💥</h1><p>Tout va bien 😎</p>";  
}  
  
// Affiche l’alerte pop-up après 2 secondes  
setTimeout(() => {  
  alert("⚠️ BOOM ! C'était un prank ! ⚠️");  
  endPrank();  
}, 2000);  
</script>  
</body>  
</html>  
