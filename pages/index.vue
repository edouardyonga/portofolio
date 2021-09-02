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
          <h1 class="mb-6">
            < EDOUARD YONGA
            <typewriter
              :speed="500"
              :full-erase="true"
              :interval="600"
              :words="['/>']"
            >
            </typewriter>
          </h1>

          <p class="">
            I am a creative frontend developer, designer.
            <br />that likes working with
            <v-chip small outlined color="yellow">Javascript</v-chip>,
            <v-chip small outlined color="green">Vuejs/Nuxtjs</v-chip>, and
            <v-chip small outlined color="primary">JAMstack</v-chip>. <br />
            I am also experienced in UI/UX designing.
          </p>
          <div>
            <a href="https://www.linkedin.com/in/edouardyonga/" target="_blank">
              <v-icon color="primary">mdi-linkedin</v-icon>
            </a>
            <a
              href="https://stackoverflow.com/users/7189479/edouard-yonga"
              target="_blank"
            >
              <v-icon color="primary">mdi-stack-overflow</v-icon>
            </a>
            <a href="https://github.com/edouardyonga" target="_blank">
              <v-icon color="primary">mdi-github</v-icon>
            </a>
            <a href="https://gitlab.com/edouardyonga" target="_blank">
              <v-icon color="primary">mdi-gitlab</v-icon>
            </a>

            <p class="float-right">
              Download Resume<v-icon class="float-right"
                >mdi-file-download-outline</v-icon
              >
            </p>
          </div>

          <v-divider class="mt-5 mb-n2" />
        </v-col>
      </v-row>
      <v-row justify="center" align="center">
        <v-col cols="12" sm="8" md="6">
          <h2 class="py-3">Top Tools</h2>
          <v-row>
            <v-col>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>Javascript</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>HTML/CSS</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>Electronjs</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>GSAP</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>Vuejs</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>Nuxtjs</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>Nodejs</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>JAMstack</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle>Firebase</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>

          <v-divider />
          <h2 class="py-3">Experience</h2>
          <v-row>
            <v-col>
              <v-list-item three-line>
                <v-list-item-content>
                  <v-list-item-title class="primary--text font-weight-bold"
                    >Frontend Dev</v-list-item-title
                  >
                  <v-list-item-subtitle>Eagles Holdings</v-list-item-subtitle>
                  <v-list-item-subtitle>
                    January 2021 - Now
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col>
              <v-list-item three-line>
                <v-list-item-content>
                  <v-list-item-title class="primary--text font-weight-bold"
                    >Frontend Dev</v-list-item-title
                  >
                  <v-list-item-subtitle>Tekstedia</v-list-item-subtitle>
                  <v-list-item-subtitle>
                    Jun 2020 - November 2020
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col>
              <v-list-item three-line>
                <v-list-item-content>
                  <v-list-item-title class="primary--text font-weight-bold"
                    >Frontend Dev</v-list-item-title
                  >
                  <v-list-item-subtitle>Wazapay</v-list-item-subtitle>
                  <v-list-item-subtitle>
                    July 2019 - April 2020
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>

          <v-divider />
          <h2 class="py-3">Languages</h2>
          <v-row>
            <v-col>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title class="primary--text font-weight-thin"
                    ># Fluent
                  </v-list-item-title>
                  <v-list-item-subtitle>French</v-list-item-subtitle>
                  <v-list-item-subtitle>English</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title class="primary--text font-weight-thin"
                    ># Basic
                  </v-list-item-title>
                  <v-list-item-subtitle>Japaness</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col> </v-col>
          </v-row>

          <v-divider />
          <h2 class="py-3">Also Busy With</h2>
          <v-row>
            <v-col>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle
                    ><v-icon small color="primary" class="pb-1 pr-1"
                      >mdi-basketball</v-icon
                    >
                    Basketball</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle
                    ><v-icon small color="primary" class="pb-1 pr-1"
                      >mdi-book-open-variant</v-icon
                    >
                    Mangas && Animes</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
            </v-col>

            <v-col>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-subtitle
                    ><v-icon small color="primary" class="pb-1 pr-1"
                      >mdi-typewriter</v-icon
                    >
                    Blogging</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
// import Snowf from "vue-snowf";
export default {
  // components: {
  //   Snowf,
  // },
};
</script>

<style>
</style>
