<template>
  <div>
    <client-only placeholder="Loading...">
      <!-- <Snowf
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
      /> -->
    </client-only>
    <div class="mt-12">
      <v-row justify="center">
        <v-col sm="8" md="6">
          <h1 class="mb-6 text-center">Contact me
          </h1>

          <p class="text-center">
            Got any questions?
          </p>
          <div class="text-center">
            <a href="https://www.linkedin.com/in/edouardyonga/" target="_blank">
              <v-icon color="primary">mdi-linkedin</v-icon> linkedin
            </a>


            <a class=" mx-4 animate__animated animate__bounce" href="mailto:ededwardyonga@gmail.com" target='_blank'>
              <v-icon color='primary' class="mr-1">mdi-email</v-icon
              >Email
            </a>

            <a class="mr-2" href="//api.whatsapp.com/send?phone=237654309211&text=Mr Edouard Yonga , Am interested in your services" target="_blank">
              <v-icon color='primary' class="mr-1">mdi-whatsapp</v-icon
              >+237 654309211
            </a>
          </div>

          <v-divider class="mt-5 mb-n2" />
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
// import Snowf from "vue-snowf";
import "animate.css"
export default {
  // components: {
  //   Snowf,
  // },
};
</script>

<style>
</style>
