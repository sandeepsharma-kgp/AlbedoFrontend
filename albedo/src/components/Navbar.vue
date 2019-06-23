<template>
<div>
    <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#" style="font-weight:bold; font-size:27px;">Albedo Academy</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">  
          <a href="#" class = "call"><b-img :src="require('../static/icons/call.svg')" style="padding : 14px;"></b-img><h8 style="padding : 14px; padding-left:0px;">+91-xxxxxxxxxx</h8></a>
          <b-button variant="outline-dark" class="scholar">Scholarship</b-button>
          <b-nav-item href="#" style="padding:5px;" active>About Us</b-nav-item>
          <b-nav-item href="#" style="padding:5px;" active>Doubts & Solution</b-nav-item>
          <b-nav-item-dropdown text="All Program" right type="dark" style="padding:5px;">
            <b-dropdown-item href="#">Class 8-9</b-dropdown-item>
            <b-dropdown-item href="#">Class 9-10</b-dropdown-item>
            <b-dropdown-item href="#">Class 11-12</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-img :src="require('../static/icons/man-user.svg')" style="padding : 14px;"></b-img>
          <b-img :src="require('../static/icons/map-pin-marked.svg')" style="padding : 14px;"></b-img>
          
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
    background-color : #e34a00 !important;
}
.scholar{
  background : none;
  color :white;
  border-radius : 15px;
  border-color: white;
  
}
.call{
  color : white;
  text-decoration: none;
}
.call:hover{
  color:white;
}
</style>