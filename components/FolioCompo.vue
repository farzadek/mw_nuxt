<template>
  <div class="folio-compo border">
    <h2>{{ title }}</h2>
    <div class="row">
      <div class="col-12 border">
        <div class="row">
          <div class="col-12 col-sm-3">
            <img src="~assets/img/bk.jpg" alt="" />
          </div>
          <div class="col-12 col-sm-3">
            <img src="~assets/img/bk.jpg" alt="" />
          </div>
          <div class="col-12 col-sm-3">
            <img src="~assets/img/bk.jpg" alt="" />
          </div>
          <div class="col-12 col-sm-3">
            <img src="~assets/img/bk.jpg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FolioCompo',
  props: ['title']
}
</script>

<style scoped>
.folio-compo {
  overflow: hidden;
}
.folio-compo .row {
  height: 200px;
  overflow: hidden;
  margin: 0 !important;
}
.folio-compo .row .col-12 {
  overflow: hidden;
}
.folio-compo h2 {
  text-transform: uppercase;
  color: #f7941e;
  font-family: Merriweather, sans-serif, arial;
  text-align: left !important;
  font-weight: 700;
}
.folio-compo img {
  height: 200px;
  width: auto;
}
</style>
