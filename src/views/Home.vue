<template>
  <div class="home">
    <MainVideo />
    <HomeCategory />
    <HomeCategory />
    <HomeCategory />
  </div>
</template>

<script>
// @ is an alias to /src
import MainVideo from "@/components/MainVideo.vue";
import HomeCategory from "@/components/HomeCategory.vue";

export default {
  name: "Home",
  components: {
    MainVideo,
    HomeCategory

  }
};
</script>
