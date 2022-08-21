<template>
  <footer id="contactarme" class="d-flex text-white p-3">
    <div class="container">
      <div class="row">
        <h2>Contactame A Traves De:</h2>
        <div class="col">
          <a href="https://github.com/miguelfra" target="blanck">
            <span><v-icon dark> mdi-github </v-icon></span>
          </a>
        </div>
        <div class="col">
          <a
            href="mailto:miguelacensio1503@gmail.com"
            target="blanck"
          >
            <span><v-icon dark> mdi-gmail </v-icon></span>
          </a>
        </div>
        <div class="col">
          <a href="https://wa.me/18295390497" target="blanck">
            <span><v-icon dark> mdi-whatsapp </v-icon></span>
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  background-color: #000000;
  -webkit-box-shadow: -1px 5px 0px -3px rgba(39, 245, 221, 1);
  -moz-box-shadow: -1px 5px 0px -3px rgba(39, 245, 221, 1);
  box-shadow: -1px -5px 0px -3px rgba(39, 245, 221, 1);
  margin-top: 82px;
}
.v-icon.v-icon {
  font-size: 40px;
  border: #fff solid 1px;
  border-radius: 41px;
  padding: 10px;
}
a {
  text-decoration: none;
}
.v-icon.v-icon:hover {
  transform: scale(1.5);
  transform: rotate(360deg);
   background-color: rgb(118, 116, 116);
  transition: all .5s ease-in-out;
}
</style>