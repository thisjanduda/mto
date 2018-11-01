<template>
  <div id="app">
    <welcome />
    <about />
    <trailer />
    <offer />
    <personalize />
    <contact />
    <faq />
  </div>
</template>

<script>
import About from '@/components/About.vue'
import Contact from '@/components/Contact.vue'
import Faq from '@/components/Faq.vue'
import Offer from '@/components/Offer.vue'
import Personalize from '@/components/Personalize.vue'
import Trailer from '@/components/Trailer.vue'
import Welcome from '@/components/Welcome.vue'

export default {
  name: 'app',
  components: {
    About,
    Contact,
    Faq,
    Offer,
    Personalize,
    Trailer,
    Welcome
  }
}
</script>

<style lang="scss">
@import url('styles/normalize.css');
*, *:before, *:after{
  box-sizing: border-box;
}
body{
  font-family: 'Lato', sans-serif;
}
h1, h2, h3, h4, h5, h6{
  font-family: 'Lobster', cursive;
}
.font-secondary{
  font-family: 'Lobster', cursive;
}
a{
  text-decoration: none;
}
.btn{
  border-width: 1px;
  border-style: solid;
  border-radius: 5px;
  padding: 5px 15px;
}
section{
  min-height: 100vh;
}

</style>
