<template>
  <v-container flued>
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
    <!--@todo Props配列をv-forで表示 -->
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
    <v-layout wrap column justify-center>
      <v-flex center xs12 sm6 md4><UserPost/></v-flex>
    </v-layout>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";
import UserPost from "./UserPost.vue"

export default Vue.extend({
  name: "Post",
  components:{
    UserPost
  },
});
</script>
