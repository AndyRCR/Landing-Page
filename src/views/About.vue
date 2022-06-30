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
            He tenido experiencia como Líder de Proyectos/Analista de Datos, y en el rubro de la programación web como desarrollador
            Front-end freelance; cualquier duda o consulta tambien puede realizarlo por mi correo o número telefonico:
            <a href="https://api.whatsapp.com/send/?phone=51970811868&text&app_absent=0" style="color: #08fdd8">andycr321@gmail.com</a> / 
            <a href="https://andyrcr.github.io/MusiCSStore---CEA/" style="color: #08fdd8" target="_blank"> +51 970811868</a>
          </p>

          <p>
            ¿Deseas ver algunos de mis trabajos? Aún me encuentro refinando algunos otros, pero puedes ir dándole un vistazo a estos 😉
          </p>

          <div style="color: #08fdd8; font-size: 24px; text-align: center; margin-top: 30px;">Proyectos en React</div>
          <div class="container-proyectos">
            <div>
              <a href="https://la-tienda-pe.vercel.app/" target="_blank">
                <p style="color: #08fdd8">La Tienda Pe'</p>
              </a>
              <a href="https://la-tienda-pe.vercel.app/" target="_blank">
                <video src="https://andyrcr-portfolio.s3.sa-east-1.amazonaws.com/tiendape.mp4" autoplay loop muted></video>
              </a>
              <div style="max-width: 450px; margin-top: 20px; text-align: center;">
                Primer proyecto en React, desarrollado para la presentación final del curso de React en Coderhouse.
                <p style="font-weight: bold; font-size: 15px;">Tecnologías usadas: React, Cloud Firestore, Material-UI, EmailJS</p>
              </div>
            </div>
            <div>
              <a href="https://weather-app-andyrcr.vercel.app/" target="_blank">
                <p style="color: #08fdd8">Weather App</p>
              </a>
              <a href="https://weather-app-andyrcr.vercel.app/" target="_blank">
                <video src="https://andyrcr-portfolio.s3.sa-east-1.amazonaws.com/weatherapp.mp4" autoplay loop muted></video>
              </a>
              <div style="max-width: 450px; margin-top: 20px; text-align: center;">
                Proyecto realizado para el curso de Algoritmos de Computación Gráfica.
                <p style="font-weight: bold; font-size: 15px;">Tecnologías usadas: React, Cloud Firestore, Styled-components, Ant Design</p>
              </div>
            </div>
            <div>
              <a href="https://foxbel-music-player.vercel.app/" target="_blank">
                <p style="color: #08fdd8">Foxbel Music Player</p>
              </a>
              <a href="https://foxbel-music-player.vercel.app/" target="_blank">
                <video src="https://andyrcr-portfolio.s3.sa-east-1.amazonaws.com/foxbel.mp4" autoplay loop muted></video>
              </a>
              <div style="max-width: 450px; margin-top: 20px; text-align: center;">
                Proyecto realizado como prueba técnica para uno de mis anteriores trabajos, resaltado como uno de los mejores entregados.
                <p style="font-weight: bold; font-size: 15px;">Tecnologías usadas: React, Material-UI, Deezer API</p>
              </div>
            </div>
            <div>
              <a href="https://peko-cinema.vercel.app/" target="_blank">
                <p style="color: #08fdd8">Peko Cinema (Desktop only)</p>
              </a>
              <a href="https://peko-cinema.vercel.app/" target="_blank">
                <video src="https://andyrcr-portfolio.s3.sa-east-1.amazonaws.com/peko.mp4" autoplay loop muted></video>
              </a>
              <div style="max-width: 450px; margin-top: 20px; text-align: center;">
                Proyecto realizado de manera personal, a fin de poner en práctica lo aprendido durante mis últimos cursos.
                <p style="font-weight: bold; font-size: 15px;">Tecnologías usadas: React, Material-UI, AWS S3, Cloud Firestore</p>
              </div>
            </div>
          </div>

          <div style="color: #08fdd8; font-size: 24px; text-align: center; margin-top: 30px;">Primeras Paginas Web (2020)</div>
          <div class="container-proyectos">
            <div>
              <a href="https://andyrcr.github.io/MusiCSStore---CEA/" target="_blank">
                <p style="color: #08fdd8">MusiCSStore</p>
              </a>
              <a href="https://andyrcr.github.io/MusiCSStore---CEA/" target="_blank">
                <video src="https://andyrcr-portfolio.s3.sa-east-1.amazonaws.com/musicsstore.mp4" autoplay loop muted></video>
              </a>
            </div>
            <div>
              <a href="https://andyrcr2.github.io/DrinkHouse/" target="_blank">
                <p style="color: #08fdd8">Drink House</p>
              </a>
              <a href="https://andyrcr2.github.io/DrinkHouse/" target="_blank">
                <video src="https://andyrcr-portfolio.s3.sa-east-1.amazonaws.com/drinkhouse.mp4" autoplay loop muted></video>
              </a>
            </div>
          </div>

        </div>
        <footer class="footer">
          <p class="center-align">
            Copyright 2022 💙 - Andy Ruben Canales Roman
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
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
.container-proyectos > div{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.container-proyectos a:nth-child(2){
  display: flex;
  justify-content: center;
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
