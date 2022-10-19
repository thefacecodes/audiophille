<template>
  <div>
   <NavBar />
  <router-view/>
 <FooterSection />
 </div>
</template>

<script>
  import NavBar from "./components/Nav.vue"
  import FooterSection from "./components/Footer.vue"
export default {
  name: "App",
  components: {
    NavBar,
    FooterSection
  }
}
</script>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Manrope:wght@200;300;500;600;700;800&display=swap");


* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Manrope", sans-serif;
}

html {
  font-size: 62.5%;
}
</style>
