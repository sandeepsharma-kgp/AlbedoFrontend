<template>
    <div style="padding:50px;">
        <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="480"
      img-height="120"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        img-src="https://picsum.photos/480/120/?image=52"
      ><h3>The Best</h3><h4>We pride ourselves in being the very best in Teaching</h4></b-carousel-slide>
      <!-- Text slides with image -->
      <b-carousel-slide
        caption="First slide"
        text="Nulla vitae elit libero, a pharetra augue mollis interdum."
        img-src="https://picsum.photos/480/120/?image=59"
      ></b-carousel-slide>
      <!-- Text slides with image -->
      <b-carousel-slide
        caption="First slide"
        text="Nulla vitae elit libero, a pharetra augue mollis interdum."
        img-src="https://picsum.photos/480/120/?image=42"
      ></b-carousel-slide>

    </b-carousel>   
    <div class="notif">
      <h4 style="color: rgb(240, 222, 61);"><b style="color:white;">Notification : </b>CLAT 2019 to be conducted online.</h4>
    </div>
    
    </div>  
</template>

<style scoped>
.notif{
   background-color : rgb(240, 109, 61) !important;
   padding:0px;
   height : 15%;
   text-align: center;
}
</style>

<script>
export default {

}
</script>
