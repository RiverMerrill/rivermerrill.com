<template>
  <div class="body">
    <div class="header">
      <div class="title text-xs-center">
        <nuxt-link to="/music">Music</nuxt-link>
        <h1 class="display-4">River Merrill</h1>
        <nuxt-link to="/store">Store</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'
import AOS from 'aos';
import 'aos/dist/aos.css';
AOS.init();

export default {
  components: {
    Logo,
    VuetifyLogo
  },
  mounted() {
  },
  methods: {
  },
  data() {
    return {
    }
  }
}
</script>

<style scoped>
.body {
  height: 100%;
  overflow: hidden;
}
.header {
  overflow-x: hidden;
  height: 100%;
  background: url("/header.jpg");
  background-size: cover;
  border-bottom: 1px solid lightgrey;
}

.line-animation {
  border-bottom: 1px solid red;
  width: 40%;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 5px;
}

.title {
  font-weight: bolder;
  color: white;
}

.title h1 {
  display: inline-block;
}

.title a {
  margin: 100px;
  color: white !important;
  text-decoration: none;
}
.title a:hover {
  color: pink !important;
  text-decoration: none;
}

.subtitle {
  width: 200px;
  margin-left: auto;
  margin-right: auto;
}

hr {
  width: 400px;
  margin: 0 auto 20px auto;
  border-top: 1px solid red;
}
</style>
