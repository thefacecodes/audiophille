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

<style scoped></style>
