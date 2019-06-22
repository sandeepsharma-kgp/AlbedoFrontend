<template>
<div>
    <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">Albedo Academy</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
          <b-img :src="require('../static/icons/map-pin-marked.svg')" style="padding : 14px;"></b-img>
          <b-img :src="require('../static/icons/man-user.svg')"></b-img>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.navbar {
    background-color : rgb(240, 109, 61) !important;
}

</style>
