<template>
  <div>
    <nuxt />
    <Footer />
  </div>
</template>

<style>
@import 'assets/style/general.css';
</style>
<script>
import Footer from '../components/Footer'
export default {
  components: { Footer }
}
</script>
