<template>
  <div>
    <Navbar />
    <nuxt />
    <Footer />
  </div>
</template>

<style>
@import 'assets/style/general.css';
</style>
<script>
import Footer from '../components/Footer'
import Navbar from '../components/Navbar'
export default {
  components: { Navbar, Footer }
}
</script>
