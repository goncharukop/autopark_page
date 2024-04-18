<template>
  <v-app>
    <v-main style="display: flex; flex-direction: column; max-width: 1180px; margin: 0 auto; gap: 24px;">
      <HeaderOne/>
      <HeaderTwo/>
      <ProductDetails/>
      <MainCard/>
      <LineDivider />
      <CarDetails />
      <LineDivider />

      <CallToAction />
      <LineDivider />

      <OtherCars/>
      <LineDivider />

      <CommentsBuyers />
      <LineDivider />

      <CallIcon />  
    </v-main>
      <PageFooter />

  </v-app>
</template>

<script>
import HeaderOne from './components/HeaderOne.vue'
import HeaderTwo from './components/HeaderTwo.vue'
import ProductDetails from './components/ProductDetails.vue'
import MainCard from './components/MainCard.vue'
import CarDetails from './components/CarDetails.vue'
import CallToAction from './components/CallToAction.vue'
import OtherCars from './components/OtherCars.vue'
import CommentsBuyers from './components/CommentsBuyers.vue'
import PageFooter from './components/PageFooter.vue'
import CallIcon from './components/CallIcon.vue'
import LineDivider from './components/LineDivider.vue'

export default {
  name: 'App',

  components: {
    HeaderOne,
    HeaderTwo,
    ProductDetails,
    MainCard,
    CarDetails,
    CallToAction,
    OtherCars,
    CommentsBuyers,
    PageFooter,
    CallIcon,
    LineDivider
  },

  data: () => ({
    //
  }),
}
</script>

<style>
a {
  color: inherit;
  text-decoration: none;
}
</style>