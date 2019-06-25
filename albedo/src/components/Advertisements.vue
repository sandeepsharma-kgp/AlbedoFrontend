<template>
<div><br><br><br>
    <div>
        <p style="font-weight: bold; padding:10px; color:#585252; font-size: 30px;">---Advertisement---</p>
    </div>

    <div style="background-color:#62959a;">
        <p style="font-weight: bold; padding:10px; color:white; font-size: 20px;">Take Tests</p>
    <div class="container" style="padding:0px 100px 25px;">
        <b-card-group deck>
            <b-card title="Competitive Exams" style="color:#060505;">
                <b-card-text style="padding:25px 0px;">
                    <div class="container">    
                        <b-button type="submit" style="background-color:#0f536d; border-color:#0f536d; width:100%;">JEE</b-button>
                    </div>
                    <div class="container">
                        <b-button type="submit" style="background-color:#0f536d; border-color:#0f536d; width:100%;">NEET</b-button>
                    </div>
                </b-card-text> 
            </b-card>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <b-card title="Class 8-12" style="color:#060505">
                <b-card-text>
                    <div class="container"><b-form-select v-model="selectBoard" :options="Board" style="background-color:#62959a; color:white;"></b-form-select></div>
                    <div class="container"><b-form-select v-model="selectClass" :options="Class" style="background-color:#62959a; color:white;"></b-form-select></div>
                    <div class="container"><b-button style="width:100%; background-color:#e16119; border-color:#e16119;">Submit</b-button></div>
                </b-card-text>
            </b-card>
        </b-card-group>
    </div>
    </div>
</div>   
</template>

<script>
export default {
data() {
      return {
        selectBoard: null,
        Board: [
          { value: null, text: 'Select your Board' },
          { value: 'State', text: 'State Board' },
          { value: 'CBSE', text: 'CBSE Board' },
          { value: 'ICSE', text: 'ICSE Board' }
        ],

        selectClass: null,
        Class: [
          { value: null, text: 'Select your Class' },
          { value: '08', text: '8' },
          { value: '09', text: '9' },
          { value: '10', text: '10' },
          { value: '11', text: '11' },
          { value: '12', text: '12' }
        ]

      }
    }
}
</script>

<style scoped>
.container{
    padding: 20px;
}

.b-card-group{
    text-align: center;
}

.b-card{
    color: black;
    height:350px; 
    width:350px;
}
</style>
