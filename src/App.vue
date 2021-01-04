<template>
  <v-app>
    <v-main>
      <v-container fluid>
        <v-card-title
          class="justify-center text-center display-1 mt-8 white--text font-weight-bold word_break"
        >
          &#9733; Symposium of Logic and Artificial Intelligence, January 13-14,
          2021 &#9733;
        </v-card-title>
        <v-card-title style="font-size: 2rem !important;"
          class="justify-center text-center display-1 mb-8 white--text word_break"
        >
          Chicago-Chisinau-Iasi
        </v-card-title>
        <v-row justify="center" class="ma-0">
          <v-card class="rounded-xl pa-2" height="100%" elevation="5">
            <!-- <v-card-title class="justify-center word_break">
                
              </v-card-title> -->
            <v-card-text
              class="text-subtitle-1 grey--text text--darken-4 text1 px-md-10"
            >
              <v-row class="ma-0">
                <h3>Organizers:</h3>
                <div class="px-2">
                  <p>Northeastern University in Chicago, USA</p>
                  <p>Alexandru Ioan Cuza University of Iasi, Romania</p>
                  <p>
                    Vladimir Andrunachievici Institute of Math. and Comp.
                    Science, Chisinau, Moldova
                  </p>
                </div>
              </v-row>
              <h3 class="mb-4">Schedule:</h3>
              <p class="pl-md-10 text-subtitle-2">January 13, 2021</p>
              <p>
                Alexei Muravitscky. <i>Nonmonotonic Consequence Relations</i>
              </p>
              <p>
                Stefan-Claudiu Susan:
                <i>
                  A practical implementation of Natural Deduction in
                  Propositional Logic
                </i>
              </p>

              <p>Andrei Arusoaie: <i>Certification in Matching Logic</i></p>
              <p>
                Ioachim Drugus.
                <i>Towards a Non-associative Model of Language</i>
              </p>
              <p>
                Talks of the participants in Romanian and Moldovan Logic and
                Artificial Intelligence Prizes Competition.
              </p>
              <p class="pl-md-10 text-subtitle-2">January 14, 2021</p>
              <p>
                Talks of the participants in Romanian and Moldovan Logic and
                Artificial Intelligence Prizes Competition
              </p>
              <p>Announcement of winners</p>
              <p>
                Martin Davis. <i>Algorithm, Equation, and Logic</i> (around 4 pm
                Chicago time)
              </p>
            </v-card-text>
          </v-card>
          <!-- <v-col cols="12" sm="6" md="4">
            <v-card class="rounded-xl pa-2" height="100%" elevation="5">
              <v-card-title class="justify-center"> </v-card-title>
              <v-card-text class="text-subtitle-1 grey--text text--darken-4">
              </v-card-text>
            </v-card>
          </v-col> -->
        </v-row>
        <v-row justify="center">
          <v-col cols="12" md="8">
            <v-card-title class="justify-center white--text text-h5 word_break">
              <em> </em>
            </v-card-title>
            <!-- <v-row justify="center">
              <img
                width="30%"
                class="mr-10 img1"
                src="../assets/islai.png"
                @click="gotopage('https://islai.org/')"
              />
              <img
                width="30%"
                class="img1"
                src="../assets/imi.png"
                @click="gotopage('http://www.math.md/')"
              />
            </v-row> -->
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",
};
</script>
<style scoped>
.img1:hover {
  cursor: pointer;
}
.word_break {
  word-break: normal;
  position: relative;
}
#app {
  background-color: #f3652f;
}
</style>