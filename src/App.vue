<template>
  <div id="app">
    <header>
      <nav
        class="navbar fixed-top navbar-light"
        style="background-color: #ffffff"
      >
        <h2 class="text-dark h2">
          <a class="navbar-brand" href="#">
            <img
              src="https://yt3.ggpht.com/ytc/AAUvwnhTEa6kEyqgSvL3wMaMbUDZtyHvhXehJppDCeOGUCI=s900-c-k-c0x00ffffff-no-rj"
              width="75"
              height="75"
              alt=""
              loading="lazy"
            /> </a
          >Space Weather Database Of Notifications, Knowledge, Information
          (DONKI)
        </h2>
      </nav>
    </header>
    <br />
    <Axios />
    <footer>
      <nav class="navbar navbar-light">
        <h2 class="text-dark h2">
          <a class="navbar-brand" href="https://www.nasa.gov/" target="_blank">
            <img
              src="https://lh3.googleusercontent.com/-9SbvMHKLu_o/UdPLXZmCFWI/AAAAAAAAB1E/ncgeI6ECwvE/s400/NASA-logo_53.jpg"
              width="60"
              height="50"
              alt=""
              loading="lazy"
            />
          </a>
        </h2>
      </nav>
    </footer>
  </div>
</template>

<script>
import Axios from "./components/axios.vue";

export default {
  name: "App",
  components: {
    Axios
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: auto;
  height: auto;
  background-image: url("https://www.nasa.gov/sites/default/files/styles/full_width_feature/public/thumbnails/image/stsci-h-p2016a-m-2000x1374.png");
  margin-top: 100px;
  border-radius: 10px;
}
header {
  margin-bottom: 15vh;
}
footer {
  margin-top: 15vh;
  background-image: url("https://www.nasa.gov/sites/default/files/styles/full_width_feature/public/thumbnails/image/stsci-h-p2016a-m-2000x1374.png");
}
</style>

