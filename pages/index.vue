<template>
  <div class="index">
    <section class="intro">
      <div class="container">
        <div>
          <h1>MontréalWEB</h1>
          <p>
            Une petite équipe de programmeurs Web et de graphistes
            professionnels dans un petit studio à Longueuil!
          </p>
          <a class="btn btn-primary" href=""
            >Dites-nous ce que vous avez besoin</a
          >
        </div>
      </div>
    </section>

    <section id="cdnfaison" class="cqnfaison">
      <div class="container">
        <h2>CE QUE NOUS FAISONS</h2>
        <div class="row">
          <div class="col-12 col-sm-4">
            <div>
              <h3>
                <i class="fa fa-picture-o" aria-hidden="true"></i>Design Web
              </h3>
              <p>
                Une de nos compétences est la conception Web. Nous sommes
                spécialisés dans la conception UI / UX. Nous sommes aussi
                infographiste et photographe.
              </p>
            </div>
          </div>
          <div class="col-12 col-sm-4">
            <div>
              <h3>
                <i class="fa fa-laptop" aria-hidden="true"></i>Développement Web
              </h3>
              <p>
                Avez-vous déjà entendu parler de HTML, CSS, Javascript,
                Typescript? Nous sommes spécialistes en eux. Angular, jQuery,
                Bootstrap... sont quelques-unes des expertises de FrontEnd.
              </p>
            </div>
          </div>
          <div class="col-12 col-sm-4">
            <div>
              <h3>
                <i class="fa fa-mobile" aria-hidden="true"></i>Site Web
                responsive
              </h3>
              <p>
                Vos visiteurs vérifient-ils votre site Web à l'aide de leurs
                téléphones intelligents? Tablette? Portable? Peu importe quel
                appareil, nous rendons le site Web totalement adaptable à tout
                appareil!
              </p>
            </div>
          </div>
          <div class="col-12 col-sm-4">
            <div>
              <h3>
                <i class="fa fa-edit" aria-hidden="true"></i>Mettre à jour le
                contenu
              </h3>
              <p>
                Avez-vous seulement besoin de mettre à jour et d'apporter des
                modifications à votre site Web? Nous pouvons vous offrir un prix
                très raisonnable pour un service parfait.
              </p>
            </div>
          </div>
          <div class="col-12 col-sm-4">
            <div>
              <h3>
                <i class="fa fa-camera-retro" aria-hidden="true"></i
                >Photographie
              </h3>
              <p>
                Y a-t-il un problème sur votre site web? Avez-vous besoin de
                faire quelque chose de mieux? Parlez-nous, laissez-nous trouver
                la meilleure solution à un coût raisonnable.
              </p>
            </div>
          </div>
          <div class="col-12 col-sm-4">
            <div>
              <h3>
                <i class="fa fa-mobile" aria-hidden="true"></i>Site Web
                responsive
              </h3>
              <p>
                Vos visiteurs vérifient-ils votre site Web à l'aide de leurs
                téléphones intelligents? Tablette? Portable? Peu importe quel
                appareil, nous rendons le site Web totalement adaptable à tout
                appareil!
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="portfolio" class="portfolio">
      <div class="container">
        <h2>QUELQUES-UNS DE NOS TRAVAUX</h2>
        <p>
          Vous pouvez trouver ici certaines de nos œuvres, y compris la
          programmation Web, la conception Web, la conception graphique ou la
          photographie.
        </p>
        <div class="row">
          <h2>PORTFOLIO</h2>
          <div class="row">
            <FolioCompo title="web" />
          </div>
          <div class="row">
            <NuxtLink to="/portfolio/web" class="col-12 col-sm-6 mb-5 p-3">
              <h3>WEB</h3>
              <img src="~assets/img/bk.jpg" alt="" />
            </NuxtLink>
            <a class="col-12 col-sm-6 mb-5 p-3">
              <h3>Design web (UI)</h3>
              <img src="~assets/img/bk.jpg" alt="" />
            </a>
            <a class="col-12 col-sm-6 mb-5 p-3">
              <h3>Infographie</h3>
              <img src="~assets/img/bk.jpg" alt="" />
            </a>
            <a class="col-12 col-sm-6 mb-5 p-3">
              <h3>Photographie</h3>
              <img src="~assets/img/bk.jpg" alt="" />
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import FolioCompo from "~/components/FolioCompo.vue";

export default Vue.extend({
  components: {FolioCompo}
})
</script>
<style>
@import '../assets/style/index.css';
</style>
