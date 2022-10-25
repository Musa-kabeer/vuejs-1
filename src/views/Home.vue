<template>
  <div>
    <Sidebar />
  </div>
</template>

<script>
// import Dashboard from "../components/layouts/dashboard/Content.vue";
import Sidebar from "../components/practice/sidebar.vue";
export default {
  components: {
    Sidebar,
  },
  data() {
    return {
      name: "VISHWA",
      nickname: "BAKO",
    };
  },
};
</script>
