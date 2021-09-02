<template>
  <v-app dark>

    <v-main>

      <v-app-bar fixed class="nav" dense dark>
        <v-btn to='/'  v-if="$route.path !='/'">
          <v-icon>mdi-arrow-left</v-icon>
        </v-btn>
        <v-spacer></v-spacer>

        <nuxt-link to="/contact">
          <v-toolbar-subtitle>Contact me</v-toolbar-subtitle>
        </nuxt-link>
      </v-app-bar>
       <Snowf
        :amount="30"
        :size="3"
        :speed="3"
        :wind="0"
        :opacity="0.6"
        :swing="1"
        :image="null"
        :zIndex="null"
        :resize="true"
        color="#7b46ec"
      />
      <Snowf
        :amount="50"
        :size="5"
        :speed="1.5"
        :wind="0"
        :opacity="0.8"
        :swing="1"
        :image="null"
        :zIndex="null"
        :resize="true"
        color="#fff"
      />

      <v-container>
        <Nuxt />
      </v-container>
    </v-main>

  </v-app>
</template>

<script>
import Snowf from "vue-snowf";

export default {
  components: {
    Snowf,
  },
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "Welcome",
          to: "/",
        },
        {
          icon: "mdi-chart-bubble",
          title: "Inspire",
          to: "/inspire",
        },
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js",
    };
  },
};
</script>
<style>
.nav {
  background-color: rgba(0, 0, 0, 0) !important;
}
.v-application a {
 color: white;
}
.v-application a:hover {
 color: #7b46ec ;
 width: 104px;
}

.nuxt-link-active {
  color: #7b46ec !important;
}
</style>
