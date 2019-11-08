<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-center">
        <img
        src="../assets/img/Logo.png"
        alt="Vuetify.js"
        style="height:250px;"
      >
      </div>
      <v-card>
        <h1 style="text-align:center; font-family:Helvetica Neue;"> 
          Welcome to the Agritech 
        </h1>
        <v-card-text>
          <p>As one of significant economic problems in Thailand,
crepe-rubber manufacture SMEs are lacking of
abilities to maintain the consistency of both quality and
supply chain due to the uncertainty of weather or technology.
Therefore, customers (company) would not buy
the crepe-rubber, and the price is undercut by the larger
company. Consequently, we are willing to tackle with this
problem which satisfy both suppliers and customers. As
there are two main problems to be solved, in this project
(i.e., phase-1) we aim to increase the quality of the
crepe-rubber to prepare the minimum viable products for
our platform.</p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Inspire
          </v-btn>
          <v-btn
          color="red"
          nuxt
          to="/about">
            About us
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<style>
v-card-title.headline{
  text-align: center;
}
</style>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>