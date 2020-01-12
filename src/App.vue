<template>
<v-app>
<v-navigation-drawer app v-model="drawer" clipped>
    <Aside/>
    </v-navigation-drawer>
    <v-app-bar color="dark" dark app clipped-left>
      <v-app-bar-nav-icon @click="drawer=!drawer"></v-app-bar-nav-icon>
      <router-link to="/">
      <v-img src="./assets/samplelog2.png" alt="imageIcon" max-height="40" max-width="150"/>
      </router-link>
      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-menu offset-y>
          <template v-slot:activator="{on}">
            <v-btn v-on="on" text>@himuko<v-icon>mdi-account</v-icon></v-btn>
          </template>
        </v-menu>
      </v-toolbar-items>
    </v-app-bar>
    <div class="paddiv">
    </div>
<router-view/>
</v-app>
</template>

<script lang="ts">
import Vue from "vue";
import Aside from "./components/Aside.vue"

export default Vue.extend({
  name: "app",
  components:{
    Aside
  },
  data: () => ({
    drawer: false
  })
});
</script>
<style>
div.paddiv{
  margin-top:60px;
}
</style>