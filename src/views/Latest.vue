<template>
  <div class="Latest">
    <HomeCategory />
    <HomeCategory />
    <HomeCategory />
  </div>
</template>

<script>
// @ is an alias to /src
import HomeCategory from "@/components/HomeCategory.vue";

export default {
  name: "Latest",
  components: {
    HomeCategory

  }
};
</script>
