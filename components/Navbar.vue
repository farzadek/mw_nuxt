<template>
  <nav class="navbar navbar-light">
    <div class="container">
      <NuxtLink class="navbar-brand" to="/"><img src="~assets/img/logo.png" alt=""> MontréalWEB</NuxtLink>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#headerNavbar"
        aria-controls="headerNavbar"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div id="headerNavbar" class="collapse navbar-collapse">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">{{ menuItems[0] }}</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">{{ menuItems[1] }}</a>
          </li>
          <li class="nav-item">
            <NuxtLink to="/portfolio" class="nav-link">{{
              menuItems[2]
            }}</NuxtLink>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">{{ menuItems[3] }}</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">{{ menuItems[4] }}</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"
              >{{ menuItems[5] }} <img src="~assets/img/en_flag.png" alt=""
            /></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  data() {
    return {
      menuItems: [
        'accueuil',
        'ce que nous faisons',
        'portfolio',
        'À PROPOS DE NOUS',
        'CONTACTEZ-NOUS',
        'EN'
      ]
    }
  }
}
</script>

<style scoped>
@import 'assets/style/navbar.css';
</style>
