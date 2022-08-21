<template>
  <div id="aboutMe" class="container mt text-white">
    <div class="row">
      <div class="col-md-6 col-sm-12">
        <h1 class="bold mt-5">
          Miguel Francisco <span class="lastName">valdez</span>
        </h1>
        <h5 class="mt bold">Tec. en Ingeneria de sotware</h5>

        <p align="justify" class="presentation bold mt">
          Hola, soy Miguel Francisco Asencio Valdez Técnico en Ingeneria de
          Software egresado del Instituto (Itla) 2022-2025. Actualmente tengo
          conocimientos en las siguientes tecnologías: administración de base de
          datos, programación, desarrollo de Software, (backend-frontend) pero
          el área en el que me desenvuelvo es el DESARROLLO de aplicaciones web.
        </p>

        <p align="justify" class="presentation bold mt">
          Soy una persona AutoDidacta, tengo pasión por la enseñanza en el manejo de programas(aplicaciones) y el uso de las nuevas tecnologías.
        </p>

        <p align="justify" class="presentation bold mt">
          <img width="10%" src="../img/bandera.png" alt="bandera Dominicana" />
          <span class="mx-5">+1 829 539 0497</span>
          <a
            href="cv/cv.pdf"
            download="cv-Miguel.pdf"
            class="btn success text-white"
          >
            <v-icon dark>mdi-arrow-down-bold-box</v-icon>
            Descargar CV</a
          >
        </p>
      </div>

      <div class="col-md-6 mt perfil col-sm-12 mt-5">
        <img src="../img/perfil.jpg" alt="Perfil" width="50%" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.bold {
  font-weight: bold;
}
.border {
  border-radius: 25px;
}
.mt {
  margin-top: 30px;
}
.presentation {
  font-size: 20px;
  line-height: 27px;
  color: #8f8888;
}
.more {
  font-size: 20px;
}
.lastName {
  display: block;
}
.success {
  background: rgb(41, 126, 25);
  border-radius: 20px;
}
.perfil img {
  background-color: white;
  padding: 2px;
  border-radius: 20px;
}
.perfil img:hover{
  transform: scale(1.2);
  transition: all .2s ease-in-out;
}
.perfil {
  color: #8f8888;
}
@media (max-width: 768px) {
  .perfil img {
    display: none;
  }
}
</style>