<template>
  <div
    class="about"
    style="
      width: 100%;
      background-color: black;
      min-height: 540px;
      position: absolute;
      top: 0vh;
    "
  >
    <div class="container-fluid">
      <div class="row">
        <div class="col s8 offset-s2">
          <h1>Hola :D</h1>
          <p>
            Muchas gracias por visitar esta sección, mi nombre es Andy Ruben Canales Roman
            Soy un estudiante de la carrera de Ingeniería de Sistemas, con un gran interés
            en el area del desarrollo web Front-end.
            <br><br>
            Actualmente me encuentro trabajando como Líder de proyecto y Analista de datos en 
            la empresa de desarrollo tecnológico Ezforms y en el rubro de la programación web como desarrollador
            Front-end freelance; cualquier duda o consulta tambien puede realizarlo por mi correo o número telefonico:
            <a href="https://api.whatsapp.com/send/?phone=51970811868&text&app_absent=0" style="color: #08fdd8">andycr321@gmail.com</a> / 
            <a href="https://andyrcr.github.io/MusiCSStore---CEA/" style="color: #08fdd8" target="_blank"> +51 970811868</a>
          </p>

          <p>
            ¿Deseas ver algunos de mis trabajos? Dales un vistazo:
          </p>
          <div class="container-proyectos">
            <div>
              <a href="https://andyrcr.github.io/MusiCSStore---CEA/" target="_blank">
                <p style="color: #08fdd8">MusiCSStore</p>
              </a>
              <a href="https://andyrcr.github.io/MusiCSStore---CEA/" target="_blank">
              <video src="../assets/video/video1.mp4" autoplay loop></video>
              </a>
            </div>
            <div>
              <a href="https://andyrcr2.github.io/DrinkHouse/" target="_blank">
                <p style="color: #08fdd8">Drink House</p>
              </a>
              <a href="https://andyrcr2.github.io/DrinkHouse/" target="_blank">
                <video src="../assets/video/video2.mp4" autoplay loop></video>
              </a>
            </div>
          </div>
        </div>
        <footer class="footer">
          <p class="center-align">
            Copyright 2022 💙 - Todos los proyectos o páginas reciben constante soporte y son desplegados en hostings de total confianza.<br> Mi github:
            <a style="color: #08fdd8" href="https://github.com/">Github</a>
          </p>
        </footer>
      </div>
    </div>
  </div>
</template>
<style scoped>
*{
  overflow-x: hidden;
}
.container-proyectos{
  display: flex;
  justify-content: space-around;
}
.container-proyectos p{
  text-align: center;
}
.row{
  display: flex;
  flex-direction: column;
}
.about {
  margin-top: 64px;
}
h1 {
  font-size: 40px;
  color: #08fdd8;
}
p {
  font-size: 20px;
}
* {
  color: white;
}
a:hover {
  color: #08fdd8;
}
.footer {
  /* position: absolute; */
  margin-top: 70px;
  width: 100vw;
  color: white;
  padding: 0 20px;
}
video{
  width: 100%;
  max-width: 450px;
  border: 1px solid white;
  border-radius: 5px;
}
@media (max-width: 450px){
  .container-proyectos{
    flex-direction: column;
  }
}
</style>
