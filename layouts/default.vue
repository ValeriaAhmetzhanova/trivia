<template>
  <v-app>
    <Header />
    <v-main>
      <Nuxt />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'
export default {
  components: { Footer, Header },
}
</script>
