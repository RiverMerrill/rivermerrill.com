<template>
  <div class="body">
    <div class="header text-xs-center">
      <nuxt-link to="/">Home</nuxt-link>
      <nuxt-link to="/store">Store</nuxt-link>
    </div>
    <v-container>
      <v-row class="albums">
        <v-col class="ma-3">
          <a href="https://song.link/album/us/i/1454553565">
            <img
              src="/hardreset.jpg"
              alt=""
            >
          </a>
        </v-col>
        <v-col class="ma-3">
          <a href="https://song.link/album/us/i/1384303675">
            <img
              src="/unusual.jpg"
              alt=""
            >
          </a>
        </v-col>
        <v-col class="ma-3">
          <a href="https://song.link/album/us/i/1318531615">
            <img
              src="/weatherboy.jpg"
              alt=""
            >
          </a>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.header {
  padding-bottom: 10%;
  color: white;
}

.header a {
  margin: 200px;
  font-size: 14pt;
  color: white !important;
  text-decoration: none;
}

.header a:hover {
  color: #b8eeff !important;
  text-decoration: none;
}

.body {
  height: 100%;
  background-color: #f9d29d;
  background-image: linear-gradient(315deg, #f9d29d 0%, #ffd8cb 74%);
}

.albums v-col img {
  width: 30%;
}
</style>


