<template>
  <div class="animate__animated animate__backInLeft">
    <h3 style="color: #08fdd8">Bienvenid@!</h3>
      <div style="font-size: 28px;">
        Hola, soy Andy Canales, este solía ser mi portafolio anteriormente, te invito a hecharle un vistazo al nuevo
      </div>
      <div style="display: flex; justify-content: center; font-size: 28px;">
        <div class="mano1">👉</div>
        <a href="https://andycanales-dev.vercel.app/" target="_blank" style="margin: 0 30px; color: #08fdd8;">
          AQUÍ
        </a>
        <div class="mano2">👈</div>
      </div>
    <a href="https://www.linkedin.com/in/andy-ruben-canales-roman-818a39219/" target="_blank">
      <img src="@/assets/icons/linkedin.png" />
    </a>
    <a href="https://github.com/AndyRCR" target="_blank">
      <img src="@/assets/icons/github.png" />
    </a>
    <a href="https://twitter.com/RubenCanalesR" target="_blank">
      <img src="@/assets/icons/twitter.png" />
    </a>
  </div>
</template>
<style scoped>
* {
  color: white;
}
h3 {
  font-size: 50px;
}
p {
  font-size: 25px;
}
img{
  margin: 20px 10px;
  transition: .3s;
}
img:hover {
  transform: scale(1.5);
}
.mano1{
  animation: mov1 2s infinite;
}
.mano2{
  animation: mov2 2s infinite;
}

@keyframes mov1 {
  0%{
    transform: translateX(15px);
    visibility: hidden;
  }
  50%{
    transform: translateX(0px);
    visibility: visible;
  }
  100%{
    transform: translateX(15px);
  }
}

@keyframes mov2 {
  0%{
    transform: translateX(-15px);
    visibility: hidden;
  }
  50%{
    transform: translateX(0px);
    visibility: visible;
  }
  100%{
    transform: translateX(-15px);
  }
}
</style>
