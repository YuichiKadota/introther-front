<template>
  <v-container>
  <v-card
    class="mx-auto"
    max-width="500"
    outlined
    elevation=1
  >
    <v-list-item three-line>
      <v-list-item-avatar
        tile
        size="80"
      >
      <v-img
          src="../assets/userimage_02.png"
          alt="himuko"

      ></v-img>
      </v-list-item-avatar>
      <v-list-item-content>
        <div class="overline mb-4"></div>
        <v-list-item-subtitle>@himukoさんは@sitaraさんに紹介文を書きました</v-list-item-subtitle>
        <v-list-item-text>お米もうどんもNG案件、炭水化物あっちいけー！あっちいけ〜〜〜〜〜〜！！てかあっちいけ〜！！</v-list-item-text>
      </v-list-item-content>
    </v-list-item>

    <v-card-actions>
      <v-btn text><v-icon>mdi-eye</v-icon>他の紹介文を見る</v-btn>
      <v-btn text><v-icon>mdi-lead-pencil</v-icon>この人に書く</v-btn>
    </v-card-actions>
  </v-card>
  </v-container>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "UserPost",
  data: () => ({
        post:[
          {title: 'testTitle',text: 'testText'}
        ]
  })
});
</script>
