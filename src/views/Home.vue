<template>
  <v-app :style="{background: $vuetify.theme.themes.light.background}">
    <v-layout row>
      <v-flex md3>
        <v-app :style="{background: $vuetify.theme.themes.light.background}">
          <v-container>
            <v-flex>
              <v-card class="ma-5 text-center mt-8" shaped elevation="10">
                <v-avatar class="mt-n7" size="60" elevation="10">
                  <img src="../assets/juliano.png">
                </v-avatar>
                <v-card-title class="layout justify-center">
                  Juliano Soares
                </v-card-title>
                <v-card-subtitle class="layout justify-center">
                  23 anos, Santa Maria
                </v-card-subtitle>
                <v-list class="mt-n5">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Blood
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Height
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Weight
                    </v-list-item-title>
                  </v-list-item>

                  <v-list-item class="mt-n5">
                    <v-list-item-subtitle>A+</v-list-item-subtitle>
                    <v-list-item-subtitle>165 cm</v-list-item-subtitle>
                    <v-list-item-subtitle>80 kg</v-list-item-subtitle>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>

            <v-flex>
              <v-card class="ma-5 mt-n2" shaped elevation="10">
                <v-list>
                  <v-list-item>
                    <v-list-item-avatar size="10" color="cyan darken-1">
                    </v-list-item-avatar>
                    <v-list-item-title class="m1-n2">Kognum</v-list-item-title>
                    <v-list-item-subtitle>10 mg</v-list-item-subtitle>
                  </v-list-item>
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Mon
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      WED
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      FRI
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      SUN
                    </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-n5">
                    <v-list-item-subtitle>2 vezes ao dia depois da comida
                    </v-list-item-subtitle>
                  </v-list-item>
                  <v-divider></v-divider>
                </v-list>

                <v-list two-line="" subheader="">
                  <v-list-item>
                    <v-list-item-avatar size="35">
                      <img src="../assets/juliano.png">
                    </v-list-item-avatar>
                    <v-list-item-content class="m1-n2">
                      <v-list-item-title>Dr. Juliano Soares</v-list-item-title>
                      <v-list-item-subtitle>Hospitaal de Caridade
                      </v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-list>

                <v-list two-line="" subheader="" class="mt-n5">
                  <v-list-item>
                    <v-list-item-title>
                      Surgeon
                    </v-list-item-title>
                    <v-list-item-subtitle>spinal pain</v-list-item-subtitle>
                  </v-list-item>
                </v-list>

                <v-list two-line="" subheader="" class="my-n8">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">Date
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">Time
                    </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-n10">
                    <v-list-item-title>
                      26 julho 2020
                    </v-list-item-title>
                    <v-list-item-title>14:00
                    </v-list-item-title>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>

            <v-flex>
              <v-card class="ma-5 text-center mt-6" shaped elevation="10">
                <v-list-item three-line="">
                  <v-list-item-title class="headline mb-1">
                    <v-icon>fab fa-cc-visa</v-icon>
                  </v-list-item-title>
                  <v-list-item-subtitle>
                    2345 4545 7876 2354
                  </v-list-item-subtitle>
                  <v-list-item-avatar size="60" color="cyan darken-1">
                    <v-icon color="white">fas fa-plus</v-icon>
                  </v-list-item-avatar>
                </v-list-item>
              </v-card>
            </v-flex>
          </v-container>
        </v-app>
      </v-flex>

      <v-flex md9>
        <v-app :style="{background: $vuetify.theme.themes.dark.background}"
        class="rounded">
          <v-container>
            <v-flex>
              <v-list class="mt-5">
                <v-list-item>
                  <v-list-item-title class="cyan--text text--darken-1">
                    Examination
                  </v-list-item-title>
                  <v-list-item-action>
                    <v-btn class="ma-2" tile outlined color="cyan darken-1">
                      <v-icon left>fas fa-eye</v-icon> See all
                    </v-btn>
                  </v-list-item-action>
                </v-list-item>
              </v-list>
            </v-flex>

            <v-flex>
              <v-row no-gutter>
                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card height="80px" width="10px" color="green"></v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader="" class="m1-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>21 julho 2020
                            </v-list-item-subtitle>
                            <v-list-item-title>sdadsd asdasdas
                            </v-list-item-title>
                            <v-list-item-subtitle>sdad asdasda
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>
                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card height="80px" width="10px" color="red"></v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader="" class="m1-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>21 julho 2020
                            </v-list-item-subtitle>
                            <v-list-item-title>sdadsd asdasdas
                            </v-list-item-title>
                            <v-list-item-subtitle>sdad asdasda
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>
                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card height="80px" width="10px" color="blue"></v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader="" class="m1-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>21 julho 2020
                            </v-list-item-subtitle>
                            <v-list-item-title>sdadsd asdasdas
                            </v-list-item-title>
                            <v-list-item-subtitle>sdad asdasda
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>
              </v-row>
            </v-flex>

            <v-flex class="mt-12">
              <v-row no-gutters="">
                <v-col cols="12" md="8">
                  <v-flex>
                    <v-list class="mt-5">
                      <v-list-item>
                        <v-list-item class="cyan--text text--darken-1">
                        Health Curve
                        </v-list-item>
                        <v-list-item-content>
                          <v-btn class="mr-1" outlined="" color="cyan darken-1">
                            D
                          </v-btn>
                        </v-list-item-content>
                        <v-list-item-content>
                          <v-btn class="mr-1" outlined="" color="cyan darken-1">
                            W
                          </v-btn>
                        </v-list-item-content>
                        <v-list-item-content>
                          <v-btn class="mr-1" outlined="" color="cyan darken-1">
                            M
                          </v-btn>
                        </v-list-item-content>
                        <v-list-item-content>
                          <v-btn outlined="" color="cyan darken-1">
                            Y
                          </v-btn>
                        </v-list-item-content>
                      </v-list-item>
                    </v-list>
                  </v-flex>

                  <v-flex>
                    <v-sparkline
                      :value="value"
                      :gradient="gradient"
                      :smooth="radius || false"
                      :padding="padding"
                      :line-width="width"
                      :stroke-linCap="lineCap"
                      :gradient-direction="gradientDirection"
                      :fill="fill"
                      :type="type"
                      :auto-line-width="autoLineWidth"
                      auto-draw=""
                    >
                    </v-sparkline>
                  </v-flex>
                </v-col>
                <v-flex class="m1-10">
                <v-row>
                  <v-date-picker
                    v-model="date2"
                    :event-color="date => date[9] % 2 ? 'red' : 'yellow'"
                    :events="functionEvents"
                    color="cyan darken-1"
                  >
                  </v-date-picker>
                </v-row>
              </v-flex>
              </v-row>
            </v-flex>

            <v-flex class="mt-5">
              <v-list class="m1-5">
                <v-list-item>
                  <v-list-item-avatar color="cyan darken-1" size="20px">
                  </v-list-item-avatar>
                  <v-list-item-title>Average</v-list-item-title>
                  <v-list-item-avatar color="cyan darken-1" size="20px">
                  </v-list-item-avatar>
                  <v-list-item-title class="m1-5">My Data</v-list-item-title>
                </v-list-item>
              </v-list>
            </v-flex>

            <v-col cols="12" md="4">
              <v-flex class="m1-10">
                <v-list>
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Nearest Tratment & Advice
                    </v-list-item-title>
                  </v-list-item>
                </v-list>
              </v-flex>

            </v-col>
          </v-container>
        </v-app>
      </v-flex>
    </v-layout>
  </v-app>
</template>

<script>
const gradients = [
  ['#222'],
  ['#42b3f4'],
  ['red', 'orange', 'yellow'],
  ['#00c6ff', '#f0f', '#ff0'],
  ['#f72047', '#ffd200', '#ifeeaea'],
];

export default {
  data: () => ({
    width: 2,
    radius: 10,
    padding: 8,
    lineCap: 'round',
    gradient: gradients[5],
    value: [0, 2, 5, 9, 5, 10, 3, 5, 0, 0, 1, 8, 2, 9, 0],
    gradientDirection: 'top',
    gradients,
    fill: false,
    type: 'trend',
    autoLineWidth: false,
    arrayEvents: null,
    date2: new Date().toISOString().substr(0, 10),
  }),

  computed: {
    theme() {
      return this.$vuetify.theme.dark ? 'dark' : 'light';
    },
  },

  mounted() {
    this.arrayEvents = [...Array(6)].map(() => {
      const day = Math.floor(Math.random() * 30);
      const d = new Date();
      d.setDate(day);
      return d.toISOString().substr(0, 10);
    });
  },

  methods: {
    functionEvents(date) {
      const [,, day] = date.split('-');
      if ([12, 17, 18].includes(parseInt(day, 10))) return true;
      if ([12, 17, 18].includes(parseInt(day, 10))) return ['red', '#00f'];
      return false;
    },
  },
};
</script>
<style scoped>
.rounded {
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
}
</style>
