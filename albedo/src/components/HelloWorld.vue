<template>
  <div>
  <b-card
    overlay
    img-src="https://picsum.photos/900/250/?image=3"
    img-alt="Card Image"
    text-variant="white"
    title=""
    sub-title=""
  >
    <b-card-text>
      <h3 class="p1">The Best</h3><br>
      <h3> We Pride Ourself In Being The Very Best In Teaching</h3>
    </b-card-text>
  </b-card>
  
</div>
</template>

<script>
  export default {
    data() {
      return {
        mainProps: { blank: true, blankColor: '#777', width: 75, height: 75, class: 'm1' }
      }
    }
  }
</script>
<style>
.p1{
  display: block;
  margin-top: 2em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
  font: bold;
  }
.p2{
  display: block;
  margin-top: 0em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
}
.a1{ 
  display: block;
  font-size: 1.5em;
  margin-top: 1em;
  margin-bottom: 0.83em;
  margin-left: 0;
  margin-right: 0;
  font-weight: bold;
  }
</style>

    

