<template>
  <v-app>
      <Posts/>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import Posts from "../components/Posts.vue";

export default Vue.extend({
  name: "app",
  components:{
    Posts
  }
});

</script>