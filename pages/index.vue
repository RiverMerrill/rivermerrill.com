<template>
  <div class="body">
    <div class="header">
      <div class="title">
        <h1 class="text-xs-center display-4">River Merrill</h1>
        <!-- <div
          class="line-animation"
          data-aos="zoom-in"
          data-aos-duration="3000"
        ></div> -->
        <p class="subtitle text-xs-center">Web Developer</p>
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
    this.$anime({
      targets: '.subtitle',
      duration: 3000,
      easing: 'easeInOutQuad',
      loop: true,
      direction: 'alternate',
      keyframes: [
        { 'border-top': '2px solid red' },
        { 'border-top': '2px solid grey' },
        { 'border-right': '2px solid red' },
        { 'border-right': '2px solid grey' },
        { 'border-bottom': '2px solid red' },
        { 'border-bottom': '2px solid grey' },
        { 'border-left': '2px solid red' },
        { 'border-left': '2px solid grey' },
      ]

    })
  }
}
</script>

<style scoped>
.header {
  height: 600px;
  /* background: url("https://www.toptal.com/designers/subtlepatterns/patterns/papyrus.png"); */
  border-bottom: 1px solid lightgrey;
}
.title {
  margin-top: 20%;
}
.line-animation {
  border-bottom: 1px solid red;
  width: 40%;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 5px;
}
.subtitle {
  width: 200px;
  margin-left: auto;
  margin-right: auto;
}
</style>
