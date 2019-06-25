<template>
<div style="background-color:#F9EEEE;">
    <div>
        <p style="font-weight: bold; padding:30px; color:	#000000; font-size: 35px;">Classroom Programs</p>
    </div>

    <div style="padding:50px; background-color:#FDFCFC; align:center">
        
      <div class="container" style="padding:0px 0px 0px;">
        <b-card-group deck style="background-color:">
            <b-card title="">
             
               <b-img :src="require('../assets/Icons/study1.svg')" style="padding : 1px 75px; "></b-img>
                 <h2 style="text-color:#2953a3;font-weight: bold">Lorem ipsum</h2>
                <b-card-text style="padding:2px 0px;">
                    <div class="container">    
                        <p>Use card groups to render cards as a single, attached element with equal width and height columns. Card groups use display: flex; to achieve their uniform sizing.</p>
                    </div>
                    <div class="container">
                        <b-button type="submit" style="background-color:#e34a00; border-color:#e34a00; width:100%;">View Details</b-button>
                    </div>
                </b-card-text> 
            </b-card>


            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            
            <b-card title="">
             <b-img :src="require('../assets/Icons/study1.svg')" style="padding : 1px 75px; "></b-img>
                 <h2 style="text-color:#2953a3;font-weight: bold">Lorem ipsum</h2>
                <b-card-text style="">
                    <div class="container">    
                        <p>Use card groups to render cards as a single, attached element with equal width and height columns. Card groups use display: flex; to achieve their uniform sizing.</p>
                    </div>
                    <div class="container">
                        <b-button type="submit" style="background-color:#e34a00; border-color:#e34a00; width:100%;">View Details</b-button>
                    </div>
                </b-card-text> 
            </b-card>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            
            <b-card title="">
               <b-img :src="require('../assets/Icons/study1.svg')" style="padding : 1px 75px; "></b-img>
                 <h2 style="text-color:#2953a3;font-weight: bold">Lorem ipsum</h2>
                <b-card-text style="padding:0px 0px;">
                    <div class="container">    
                        <p>Use card groups to render cards as a single, attached element with equal width and height columns. Card groups use display: flex; to achieve their uniform sizing.</p>
                    </div>
                    <div class="container">
                        <b-button type="submit" style="background-color:#e34a00; border-color:#e34a00; width:100%;">View Details</b-button>
                    </div>
                </b-card-text> 
            </b-card>

        </b-card-group>
    </div>
    </div>
      
    <div class="container" style="padding:30px 150px;background-color:#F9EEEE;">
      <div>
        <p style="font-weight: bold; padding:0px; color:	#000000; font-size: 35px;">Exams</p>
      </div>
      <b-card-group style="padding:30px">
        
        <b-card title="">
            <b-img :src="require('../assets/Icons/study1.svg')" style="padding : 1px 75px; "></b-img>
                 <h2 style="text-color:#2953a3;font-weight: bold">Lorem ipsum</h2>
                <b-card-text style="">
                    <div class="container">    
                        <p>Use card groups to render cards as a single, attached element with equal width and height columns. Card groups use display: flex; to achieve their uniform sizing.</p>
                    </div>
                    <div class="container">
                        <b-button type="submit" style="background-color:#e34a00; border-color:#e34a00; width:100%;">View Details</b-button>
                    </div>
                </b-card-text> 
            </b-card>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            
            <b-card >
               <b-img :src="require('../assets/Icons/study1.svg')" style="padding : 1px 75px; "></b-img>
                    <h2 style="text-color:#2953a3;font-weight: bold">Lorem ipsum</h2>
                <b-card-text style="padding:0px 0px;">
                    <div class="container">    
                        <p>Use card groups to render cards as a single, attached element with equal width and height columns. Card groups use display: flex; to achieve their uniform sizing.</p>
                    </div>
                    <div class="container">
                        <b-button type="submit" style="background-color:#e34a00; border-color:#e34a00; width:100%;">View Details</b-button>
                    </div>
                </b-card-text> 
            </b-card>
      </b-card-group>
    </div>
</div>   
</template>

<script>
export default {
}
</script>

<style scoped>
.container{
    padding: 5px;
}
.b-card-group{
    padding: 150px;
    text-align: center;
    background: cornsilk;
}
.b-card{
    color: black;
    height:300px; 
    width:300px;
}
</style>