<template>
<v-app>
  <v-card width="500px" class="mx-auto mt-5">
    <v-card-title>
      <h1 class="display-1">ログイン</h1>
    </v-card-title>
    <v-card-text>
      <v-form>
        <v-text-field prepend-icon="mdi-account-circle" label="ユーザ名" />
        <v-text-field prepend-icon="mdi-lock" type="password" append-icon="mdi-eye-off" label="パスワード" />
      </v-form>
    </v-card-text>
    <v-card-actions>
        <v-btn class="success">ログイン</v-btn>
        <v-btn class="info">登録する</v-btn>
    </v-card-actions>
  </v-card>
</v-app>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "userRegister",
  data: () => ({
    //
  })
});
</script>