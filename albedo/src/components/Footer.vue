<template>
<div>
    <div class="social">
        Connect with Us<br>
        <b-img :src="require('../assets/icons/facebook (1).svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../assets/icons/twitter.svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../assets/icons/gmail.svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../assets/icons/youtube (1).svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../assets/icons/instagram.svg')" style="padding: 14px;"></b-img>
    </div>
    <div class="copright">
        Copyright Notice: @ 2018 Greycells18 Media Limited and its Licensors. All rights reserved.
    </div>
    <div class="fixed-bottom" style="text-align:right;padding:20px 40px;"><b-button style="background-color:#063b6c; border-color:#063b6c; border-radius:8px;"><b-img :src="require('../assets/icons/envelope.svg')" style="padding: 0px 5px 0px 0px;"></b-img>Contact Us</b-button></div>
</div>
</template>

<script>
export default {
    
}
</script>

<style>
    .social{
        background-color:black;
        color: white;
        font-weight: bold;
        font-size:20px;
    }

    .copyright{
        background-color: white;
        color: black;
    }
</style>