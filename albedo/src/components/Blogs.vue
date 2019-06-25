<template>
    <div class="container" style="padding:30px 100px 25px;">
        <b-container class="bv-example-row">
        <b-row>
            <b-col class="border-right"><strong style="font-size:20px; font-weight:bold; color:#141313;">Blogs</strong>
            <div style="padding: 40px 14px 0px 0px;">
                <b-card no-body class="overflow-hidden" >
                    <b-row no-gutters>
                    <b-col md="4">
                        <b-card-img :src="require('../assets/images/blogging-blur-communication-261662.jpg')" style="padding:25px 20px 0px 20px; width:150px;"></b-card-img>
                    </b-col>
                    <b-col md="8">
                        <b-card-body>
                        <b-card-text style="text-align:left;">
                            <a href="">This is a wider card with supporting text as a natural lead.</a><br>
                            <p style="font-size:15px; color:grey;">By:abc</p>
                        </b-card-text>
                        </b-card-body>
                    </b-col>
                    </b-row>
            </b-card>
            <b-card no-body class="overflow-hidden">
                <b-row no-gutters>
                <b-col md="4">
                    <b-card-img :src="require('../assets/images/blogging-blur-communication-261662.jpg')" style="padding:25px 20px 0px 20px; width:150px;"></b-card-img>
                </b-col>
                <b-col md="8">
                    <b-card-body>
                    <b-card-text style="text-align:left;">
                        <a href="">This is a wider card with supporting text as a natural lead.</a><br>
                        <p style="font-size:15px; color:grey;">By:abc</p>
                    </b-card-text>
                    </b-card-body>
                </b-col>
                </b-row>
            </b-card>
            <b-card no-body class="overflow-hidden">
                <b-row no-gutters>
                <b-col md="4">
                    <b-card-img :src="require('../assets/images/blog-businesswoman-create-267569.jpg')" style="padding:25px 20px 0px 20px; width:150px;"></b-card-img>
                </b-col>
                <b-col md="8">
                    <b-card-body>
                    <b-card-text style="text-align:left;">
                        <a href="">This is a wider card with supporting text as a natural lead.</a><br>
                        <p style="font-size:15px; color:grey;">By:abc</p>
                    </b-card-text>
                    </b-card-body>
                </b-col>
                </b-row>
            </b-card>
            </div><br>
            <b-button style="background-color:#e16119; border-color:#e16119; width:150px;">View More</b-button>
            </b-col>

            <b-col><strong style="font-size:20px; font-weight:bold; color:#141313;">Questions & Answers</strong>
                <div style="padding: 40px 0px 0px 14px;">
                    
                    <b-row>    
                        <b-col sm="8">
                        <b-form-input v-model="text" placeholder="Type your question here..."></b-form-input>
                        </b-col>
                        <b-col sm="4">
                        <b-button style="background-color:#e16119; border-color:#e16119;">Ask Question</b-button>
                        </b-col>
                    </b-row><br><br>
                    
                    <b-card no-body class="overflow-hidden" style="height:150px;">
                    <b-row no-gutters>
                    <b-col md="2">
                        <b-card-img :src="require('../assets/icons/question.svg')" style="padding:50px 10px; width:80px;"></b-card-img>
                    </b-col>
                    <b-col md="10">
                        <b-card-body style="text-align:left;">
                        <b-card-text>
                            <p style="color:grey; font-size:15px;">Class-Board-Subject</p>
                            <a href="">This is a wider card with supporting text as a natural lead.</a><br>
                            <p style="font-size:15px; color:grey;">By:abc</p>
                        </b-card-text>
                        </b-card-body>
                    </b-col>
                    </b-row>
                </b-card>
                <b-card no-body class="overflow-hidden" style="height:150px;">
                    <b-row no-gutters>
                    <b-col md="2">
                        <b-card-img :src="require('../assets/icons/question.svg')" style="padding:50px 10px; width:80px;"></b-card-img>
                    </b-col>
                    <b-col md="10">
                        <b-card-body style="text-align:left;">
                        <b-card-text>
                            <p style="color:grey; font-size:15px;">Class-Board-Subject</p>
                            <a href="">This is a wider card with supporting text as a natural lead.</a><br>
                            <p style="font-size:15px; color:grey;">By:abc</p>
                        </b-card-text>
                        </b-card-body>
                    </b-col>
                    </b-row>
                </b-card>
                </div><br>
                <b-button style="background-color:#e34a00; border-color:#e34a00; width:150px;">View More</b-button>
            </b-col>
        </b-row>
        </b-container>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.border-right{
    border-right: 1px solid black;
}
</style>