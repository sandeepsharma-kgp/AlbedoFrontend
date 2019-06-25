<template>
<div>
    <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">Albedo Academy</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      
      <b-navbar-nav class="ml-auto">  
          <a href="#" class = "call"><b-img :src="require('../assets/Icons/call1.svg')" style="padding : 14px;"></b-img><h8 style="padding : 14px; padding-left:0px;">+91xxxxxxxxxx</h8></a>
          <b-button variant="outline-dark" class="scholar">Scholarship</b-button>
          <b-nav-item href="#" style="padding:5px;" active>About Us</b-nav-item>
          <b-nav-item href="#" style="padding:5px;" active>Doubts & Solution</b-nav-item>
          <b-nav-item-dropdown text="All Program" right type="dark" style="padding:5px;">
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown>
          
      <b-img :src="require('../assets/Icons/mappin.svg')" style="padding : 14px;"></b-img>
          <b-img :src="require('../assets/Icons/manuser.svg')"></b-img>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
 <h3></h3>
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
.scholar{
  background : none;
  color :white;
  border-radius : 50px;
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