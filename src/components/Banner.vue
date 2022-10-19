<template>
  <div class="banner">
    <div class="hero">
      <span class="new">New product</span>
      <h1>XX99 Mark II Headphones</h1>
      <p>
        Experience natural, lifelike audio and exceptional build quality made for the
        passionate music enthusiast.
      </p>
      <router-link to="/product">See product</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "BannerSection",
};
</script>

<style scoped>
.banner {
  background: url("../assets/home/desktop/image-hero.jpg");
  height: 100vh;
  background-size: co;
  background-position: top;
  position: relative;
  padding: 30px 150px;
  display: flex;
  align-items: center;
}

.hero {
  width: 50%;
}

.hero h1 {
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

@media (max-width: 480px) {
  .banner {
    padding: 20px;
    background: url("../assets/home/mobile/image-header.jpg");
    background-size: cover;
  }
  .hero {
    width: 100%;
    text-align: center;
  }

  .hero p {
    width: 100%;
  }
}
</style>
