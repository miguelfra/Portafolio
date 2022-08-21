<template>
  <div id="app">
    <nav class="navbar fijo navbar-expand-lg navbar-dark w-100">
      <div class="container-fluid">
        <a class="navbar-brand">Portafolio</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0 flex">
            <li class="nav-item">
              <a class="mr-2" href="#aboutMe">
                <v-icon dark> mdi-home-variant-outline </v-icon> inicio</a
              >
            </li>
            <li class="nav-item">
              <a class="mr-2" href="#skills"><v-icon dark> mdi-web </v-icon> Skills</a>
            </li>
            <li class="nav-item">
              <a class="mr-2" href="#myprojects"><v-icon dark> mdi-folder-multiple-image </v-icon> My projects</a>
            </li>
              <li class="nav-item">
              <a class="mr-2" href="#contactarme"><v-icon dark> mdi-phone </v-icon> Contactarme</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <video muted autoplay loop>
      <source src="./video/fondo.mp4" type="video/mp4" />
    </video>

    <router-view />

    <Footer />
  </div>
</template>

<script>
import Footer from "./components/Footer.vue";
export default {
  components: {
    Footer,
  },
};
</script>

<style>
nav {
  background-color: #000000;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  /* Fondo-Video */
  min-height: 100vh;
  position: relative;
}
video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: -1;
}

nav {
  padding: 30px;
  -webkit-box-shadow: -1px 5px 0px -3px rgba(39, 245, 221, 1);
  -moz-box-shadow: -1px 5px 0px -3px rgba(39, 245, 221, 1);
  box-shadow: -1px 5px 0px -3px rgba(39, 245, 221, 1);
}
footer {
  z-index: 1;
}

.fijo {
  position: fixed;
  top: 0;
}
nav a,
.navbar-dark {
  font-weight: bold;
  color: #ffffff;
  text-decoration: none;
  margin-right: 10px;
}

nav a.router-link-exact-active {
  color: #39413d;
}

.flex {
  width: 100%;
  display: flex;
  justify-content: end;
}
.mr-2 {
  margin-right: 30px;
}
</style>
