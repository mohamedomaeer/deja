<template>
    <div class="admin" id="wrapper">
        <AdminSidebar />
        <div id="content-wrapper">
            <div class="container-fluid pb-0">
                <HomeCategory />
            </div>
        </div>
        
    </div>
</template>


<script>
// @ is an alias to /src
import AdminSidebar from "@/components/Admin/AdminSidebar.vue";
import HomeCategory from "@/components/HomeCategory.vue";

export default {
  name: "Admin",
  components: {
    AdminSidebar,
    HomeCategory
  }
};
</script>
