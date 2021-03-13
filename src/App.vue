<template>
  <v-app>
    <v-app-bar class="topbar-slide"
      app
      color="grey darken-4"
      dark
    >
      <a href="/" color="white" class="homepage-link">
        <div class="d-flex align-center">
          <v-img src="./assets/crane.jpg" class="shrink mr-2" width="40"
            alt="Axel Fiolle"
            style="border-radius: 50%;"
          />
          <h1>andaroth.art</h1>
        </div>
      </a>

      <v-spacer></v-spacer>

      <v-btn
        href="https://soundcloud.com/axel-andaroth"
        target="_blank"
        text
      >
        <span class="mr-2">SoundCloud</span>
        <v-icon x-small>mdi-open-in-new</v-icon>
      </v-btn>
      <v-btn
        href="https://github.com/Andaroth"
        target="_blank"
        text
      >
        <span class="mr-2">GitHub</span>
        <v-icon x-small>mdi-open-in-new</v-icon>
      </v-btn>
      <v-btn
        href="https://www.flickr.com/photos/axel-andaroth/"
        target="_blank"
        text
      >
        <span class="mr-2">Flickr</span>
        <v-icon x-small>mdi-open-in-new</v-icon>
      </v-btn>
      <v-btn
        href="https://www.instagram.com/an.da.ro.th/"
        target="_blank"
        text
      >
        <span class="mr-2">Instagram</span>
        <v-icon x-small>mdi-open-in-new</v-icon>
      </v-btn>
      <v-btn
        href="https://axelandaroth.wordpress.com/"
        target="_blank"
        text
      >
        <span class="mr-2">WordPress</span>
        <v-icon x-small>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main class="page-viewer">
      <LandingPage/>
    </v-main>
  </v-app>
</template>

<script>
import LandingPage from './components/LandingPage';

export default {
  name: 'App',

  components: {
    LandingPage,
  },

  data: () => ({
    //
  }),
};
</script>

<style lang="scss" scoped>
  .page-viewer {
    background-image: url('./assets/bg_clouds.jpg');
    background-attachment: fixed;
    background-size: cover;
    background-repeat: no-repeat;
  }

  .topbar-slide {
    overflow-x: auto;
  }

  a {
    color: #CC9A54 !important;
    caret-color: #CC9A54 !important;
    &.homepage-link { text-decoration: none; }
  }
</style>