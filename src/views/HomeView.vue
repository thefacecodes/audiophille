<template>
  <div class="home">
    <div class="banner">
      <picture>
        <source media="(max-width: 480px)" srcset="../assets/home/mobile/image-header.jpg">
        <source media="(max-width: 960px)" srcset="../assets/home/tablet/image-header.jpg">
        <img src="../assets/home/desktop/image-hero.jpg" alt="">
      </picture>
      <div class="hero">
        <div>
           <span class="new">New product</span>
        <h1>XX99 Mark II Headphones</h1>
        <p> Experience natural, lifelike audio and exceptional build quality made for
      the passionate music enthusiast.</p>
      <router-link to="/product">See product</router-link> 
        </div>
       
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  components: {
  
  }
}
</script>

<style scoped>
.banner {
  /* background: url("../assets/home/desktop/image-hero.jpg"); */
  /* height: 100vh; */
  /* background-size: co; */
  /* background-position: top; */
  position: relative;
}

.banner img {
  width: 100%;
}

.hero {
  position: absolute;
  top: 0;
  display: flex;
  flex-direction: column;
  /* align-items: center; */
  justify-content: center;
 left: 15em;
 width: 40%;
 bottom: 0;
 /* background: black; */
}

.hero  h1 {
   color: white;
   font-size: 5em;
   text-transform: uppercase;
   letter-spacing: 0.1em;
   margin-block: 0.3em;
}

.new {
  color: gray;
  text-transform: uppercase;
  letter-spacing: 0.7em;
  font-size: 2em;
  /* margin-bottom: 5em; */
}

.hero p {
  font-size: 1.3em;
  color: #808080;
  width: 80%;
  margin-bottom: 3em;
}

.hero a {
  padding: 1em 2em;
  text-decoration: none;
  color: white;
  background: #d87d4a;
  font-size: 1.3em;
  text-transform: uppercase;
  letter-spacing: 0.1em;
}
</style>
