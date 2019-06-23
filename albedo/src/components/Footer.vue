<template>
<div>
    <div class="social">
        Connect with Us<br>
        <b-img :src="require('../static/icons/facebook (1).svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../static/icons/twitter.svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../static/icons/gmail.svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../static/icons/youtube (1).svg')" style="padding: 14px;"></b-img>
        <b-img :src="require('../static/icons/instagram.svg')" style="padding: 14px;"></b-img>
    </div>
    <div class="copright">
        Copyright Notice: @ 2018 Greycells18 Media Limited and its Licensors. All rights reserved.
    </div>
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