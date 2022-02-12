<template>
  <v-app>
    <v-app-bar app color="orange" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          :src="require('./assets/check.png')"
          transition="scale-transition"
          width="40"
        />

        <h1>Resto</h1>
      </div>

      <v-spacer></v-spacer>

      <v-btn href="https://google.com" target="_blank" text>
        <span class="mr-2">Login</span>
        <v-icon>mdi-login</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
