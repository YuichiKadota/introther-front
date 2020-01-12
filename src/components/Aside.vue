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
          <router-link to="/login">
            <v-list-item-title>
              ログイン
            </v-list-item-title>
          </router-link>
        </v-list-item-content>
      </v-list-item>
    </v-list>
  </v-container>
</template>

<script lang="ts">

import Vue from "vue";

export default Vue.extend({
  name: "Aside",
});

</script>
