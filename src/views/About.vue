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
          <h1>Hola</h1>
          <p>
            Muchas gracias por visitar esta sección, este proyecto fue realizado
            con Vue.js, Materialize y Three.js
          </p>
          <p>
            ¿Deseas ver otros trabajos nuestros? Accede a ellos pulsando
            <a href="#" style="color: #08fdd8"
              >aquí</a
            >
          </p>
        </div>
        <footer class="footer">
          <p class="center-align">
            Clockwerk Team está conformado por:
          </p>
          <ul class="center-align">
            <li>
              Andy Canales Roman - 
              <a style="color: #08fdd8" href="https://www.linkedin.com/in/andy-ruben-canales-roman-818a39219/">Ver mas</a>
            </li>
            <li>
              Angelo Calvo Pimentel - 
              <a style="color: #08fdd8" href="https://www.linkedin.com/in/angelo-jampierre-b9a714221/">Ver mas</a>
            </li>
            <li>
              Gabriel Montoya Huamani - 
              <a style="color: #08fdd8" href="https://www.linkedin.com/in/gabriel-montoya-huamani-a525b0193/">Ver mas</a>
            </li>
            <li>
              Miguel Berrio Huamani - 
              <a style="color: #08fdd8" href="https://www.linkedin.com/in/miguel-angel-berrio-huamani-842123162/">Ver mas</a>
            </li>
          </ul>
          <p class="center-align">
            Copyright 2022 💙 - Todos nuestros proyectos reciben constante soporte y son desplegados en nuestros diferentes repositorios de
            <a style="color: #08fdd8" href="https://github.com/">Github</a>
          </p>
        </footer>
      </div>
    </div>
  </div>
</template>
<style scoped>
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
  position: absolute;
  bottom: 40px;
  width: 100vw;
  color: white;
  padding: 0 20px;
}
</style>
