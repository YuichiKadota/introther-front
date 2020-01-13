<template>
  <v-container>
    <v-list-item>
      <v-list-item-content>
        <v-list-item-title class="title grey--text text--darken-2">
          IntroOther
        </v-list-item-title>
      </v-list-item-content>
    </v-list-item>
    <v-divider></v-divider>
    <v-list dence nav>
      <v-list-item>
        <vist-item-icon>
          <v-icon>mdi-account</v-icon>
        </vist-item-icon>
        <v-list-item-content>
        <v-dialog v-model="dialog" max-width="600px">
        <template v-slot:activator="{ on }">
          <v-btn text v-on="on">ログインする</v-btn>
        </template>
        <Login/>
      </v-dialog>
        </v-list-item-content>
      </v-list-item>
    </v-list>
  </v-container>
</template>

<script lang="ts">

import Vue from "vue";
import Login from "./Login.vue"

export default Vue.extend({
  name: "Aside",
  components:{
    Login
  },
  data: () => ({
    dialog: false
  })
});

</script>
