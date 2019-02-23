<template>
  <v-app dark>
    <v-toolbar app color="#6863ce">
      <v-toolbar-title><v-btn flat nuxt to="/">Nuxt Universal</v-btn></v-toolbar-title>
      <v-spacer></v-spacer>
      <!--<v-toolbar-items class="hidden-sm-and-down">-->
        <!--<v-btn flat nuxt to="about">about</v-btn>-->
        <!--<v-btn flat nuxt to="contact">contact</v-btn>-->
      <!--</v-toolbar-items>-->
    </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer class="pa-3">
      <span>&copy; 2019</span>
      <v-spacer></v-spacer>
      <v-btn flat nuxt to="terms">terms</v-btn>
      <v-btn flat nuxt to="location">location</v-btn>
    </v-footer>
  </v-app>
</template>

