<template>
  <div id="app">
    <AppHeader />
    <router-view />
  </div>
</template>


<script>
import AppHeader from "@/components/Global/AppHeader.vue";
export default {
  name: "App",
  components: {
    AppHeader
  }
};
</script>