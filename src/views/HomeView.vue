<template>
  <div class="home">
    <BannerSection />
  </div>
</template>

<script>
// @ is an alias to /src
import BannerSection from "../components/Banner.vue";
export default {
  name: "HomeView",
  components: { BannerSection },
};
</script>

<style scoped>
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
</style>
