<template>
  <div id="skills" class="text-white skills">
    <div class="container">
      <h2 class="py-4">Skills</h2>
      <div class="row">
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3 py-2">
          <div class="items">
            <img src="../img/html5.svg" alt="html" width="50%" />
            <p>Html</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/css.svg" alt="css" width="50%" />
            <p>Css</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/bootstrap.svg" alt="bootstrap" width="50%" />
            <p>Bootstrap</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/js.svg" alt="js" width="50%" />
            <p>Javascript</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/vue.png" alt="vue" width="50%" />
            <p>Vue Js</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/node.png" alt="node" width="50%" />
            <p>Node Js</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/git.svg" alt="git" width="50%" />
            <p>Git</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/github.svg" alt="github" width="50%" />
            <p>Github</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/mysql.svg" alt="mysql" width="50%" />
            <p>Mysql</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/npm.png" alt="npm" width="50%" />
            <p>Npm</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/api.png" alt="api" width="50%" />
            <p>Api Rest</p>
          </div>
        </div>
        <div class="col-6 mb-3 col-lg-2 col-sm-4 col-md-3">
          <div class="items">
            <img src="../img/vuetify.jpg" alt="vuetify" width="50%" />
            <p>Vuetify</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
window.addEventListener("scroll", () => {
  let item = document.querySelectorAll(".items");
  item.forEach(function (element) {
    let pocision = element.getBoundingClientRect().top;
    let tamanoPantalla = window.innerHeight;

    if (pocision < tamanoPantalla) {
      element.classList.add("animacion");
    }
  });
});
export default {};
</script>

<style scoped>
.skills {
  -webkit-box-shadow: 0px -2px 0px 0px rgba(88, 94, 93, 1);
  -moz-box-shadow: 0px -2px 0px 0px rgba(88, 94, 93, 1);
  box-shadow: 0px -2px 0px 0px rgba(88, 94, 93, 1);
  background-color: rgb(1, 10, 12);
}
img {
  padding-top: 5px;
}
.items {
  width: 130px;
  height: 130px;
  padding: 0;
  grid-column: span 2;
  border-radius: 100%;
  background: rgb(0, 183, 255);
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  align-content: center;
  box-shadow: 0px 3px 4px rgb(0 0 0 / 32%);
}
.animacion {
  animation-name: evento-animado;
  animation-duration: 3s;
  transition: all 3s ease-in-out;
}
.items:hover {
  transform: rotate(360deg);
  transition: all 0.5s ease-in-out;
}
@keyframes evento-animado {
  0% {
    transform: translatex(100% );
  }
  

  100% {
    transform: translateY(0%);
  }
}
p {
  font-family: "Dancing Script", cursive;
  font-weight: 700;
  font-size: 20px;
}
</style>