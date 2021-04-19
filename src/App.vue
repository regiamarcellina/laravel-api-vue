<template>
  <div id="nav">
    <div class="container">
      <Navbar />
      <router-view />
    </div>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

    import Navbar from "@component/Navbar.vue";

    export default {
      name: "Home",
      components: {
        Navbar,
      },
    };
</script>
