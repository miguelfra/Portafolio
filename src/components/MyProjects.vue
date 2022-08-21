<template>
  <div id="myprojects" class="text-white">
    <h2 class="mt-5">My Projects</h2>
    <div class="container mb--5">
      <div class="row">
        <div class="col-lg-4 mt-6 col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/ricky end morty.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://rickyandmorthyv2.netlify.app" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6 col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/Gifs.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://app-gif-router-vue.netlify.app" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
            <div class="border">
              <a href="https://github.com/miguelfra/gif-route" target="blanck" class="btn text-white">Codigo Git</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6 col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/pelis.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://cute-fairy-37b437.netlify.app/" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
            <div class="border">
              <a href="https://github.com/miguelfra/pelis" target="blanck" class="btn text-white">Codigo Git</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/company.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://company-products.netlify.app" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
            <div class="border">
              <a href="https://github.com/miguelfra/company" target="blanck" class="btn text-white">Codigo Git</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/favorite-link.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://favorite-link.netlify.app" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
            <div class="border">
              <a href="https://github.com/miguelfra/APP_Link-" target="blanck" class="btn text-white">Codigo Git</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/store.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://github.com/miguelfra/app-store" target="blanck" class="btn text-white">Codigo Git</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/employee.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://github.com/miguelfra/Employees" target="blanck" class="btn text-white">Codigo Git</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/task.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://github.com/miguelfra/App-Task" target="blanck" class="btn text-white">Codigo Git</a>
            </div>
          </div>
        </div>
      </div>

      <div class="row mt-6">
        <h2 class="border-top">paginas web</h2>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/nintendo.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://gamenintendo.netlify.app/" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/festival.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://rock-festival163.netlify.app/" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/app-peluqueria.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://appsalom.netlify.app/" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
          </div>
        </div>
        <div class="col-lg-4 mt-6  col-sm-6 ">
          <img
            class="animacion-event"
            src="../img/noticias.jpg"
            width="100%"
            height="100%"
            alt="proyecto"
          />
          <div class="btn-flex">
            <div class="border">
              <a href="https://technews047.netlify.app/" target="blanck" class="btn text-white">Ver proyecto</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
window.addEventListener("scroll", () => {
  let item = document.querySelectorAll(".animacion-event");
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
img {
  background-color: #ffffff;
  padding: 2px;

}
img:hover{
  transform: scale(1.2);
  transition: all 1s ease-in-out;
}
.animacion {
  animation-name: items;
  animation-duration: 5s;
  animation-timing-function: ease-in;
}
@keyframes items{
  0%{
    transform: translateY(0%);
  }
  20%{
    transform: translateY(20%);
  }
  40%{
    transform: translateY(0%);
  }
  60%{
    transform: translateY(20%);
  }
  80%{
    transform: translateY(0%);
  }

  100%{
    transform: translateY(20%);
  }
}
.btn-flex {
  display: flex;
  justify-content: center;
  margin-top: 5px;
}
.border {
  border: 1px solid #ffffff;
  border-radius: 100px;
}
.border:hover {
  background-color: rgb(118, 116, 116);
  transition: all 1s ease-in-out;
}
a {
  font-weight: bold;
}
.mt-6{
  margin-top: 56px;
}
h2{
  margin-bottom: 0;
}
.border-top{
  border-top: 1px solid #ffffff;
}
</style>