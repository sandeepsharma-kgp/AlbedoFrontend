<template>
<div>
<button onclick="document.getElementById('id01').style.display='block'" style="position:absolute; right:0; top:0; width:auto;">
  Login</button>

<div id="id01" class="modal">
  <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
  <div id="login">
    <div class="sign-up">
      <h1> Welcome to Albedo </h1>
      <input type="text" placeholder="Full Name" required/>
      <input type="email" placeholder="Email" required/>
      <input type="tele" pattern="[0-9]{10}" placeholder="Contact Number" required/>
      <select placeholder="Category" onchange="myFunction">
        <option  disabled value="" selected data-default>Category</option>
        <option value = "Unreserved">Unreserved</option>
        <option value = "OBC">OBC</option>
        <option value = "SC">SC</option>
        <option value = "ST">ST</option>
        <option value = "Unreserved-PH">Unreserved-PH</option>
        <option value = "OBC-PH">OBC-PH</option>
        <option value = "SC-PH">SC-PH</option>
        <option value = "ST-PH">ST-PH</option>
      </select>
      <img class="select-arrow" src = "../assets/down_arrow.svg">
      <input type="text" pattern="[0-9]{6}" maxlength="6" placeholder="Pin Code" required/>
      <input type="text" placeholder="City" required/>
      <input type="password" placeholder="Type-Password" required/>
      <input type="submit" value="SIGN ME UP">
    </div>
    
    <div class="sign-in">
      <h2>Sign In</h2>
      <form style="position:relative; top: 80px;">
        <input class="sign-in-email" type="email" placeholder="Email" required/>
        <input style="position:relative; top: 15px;" class="sign-in-password" type="password" placeholder="Password" required/>
      
        <label class="container">Remember me
          <input type="checkbox" value="marked">
          <span class="checkmark"></span>
        </label>
        
        <input style="position:relative; top: 50px;" type="submit" value="SIGN IN">
        <div style="position:relative; top: 50px;" class="psw">Forgot Password?</div>
      </form>
      
    </div>

    <div class="or">OR</div>
  </div>
</div>
  </div>
</template>

<script>
// Get the modal
var modal = document.getElementById('id01');

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>
<script>
export default {
  name: 'Login',
  data(){
    return{
      error:'',
      signUp:{
        name:null,
        email:null,
        contact:null,
        category:null,
        pin:null,
        city:null,
        password:null
      },
      signIn:{
        email:null,
        password:null
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
body{
  margin: 0;
  padding: 0;
  background: #efe4d3;
  font-size: 16px;
  color: #777;
  font-family: sans-serif;
  font-weight: 300;
}
#login{
  position: relative;
  margin:1% auto;
  width: 1000px;
  height: 550px;
  background: #fff;

}
.sign-up{
  position: absolute;
  top: 0;
  left: 0;
  box-sizing: border-box;
  padding: 40px;
  width: 500px;
  height: 500px;
}
h1 {
  margin: 0 0 20px 0;
  font-weight: bold;
  font-size: 16px;
}
h2 {
  margin: 0 0 20px 0;
  font-weight: bold;
  font-size: 16px;
  color: whitesmoke;
  font-family:'Lucida Sans','Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande',  Arial, sans-serif; 
}
.psw{
  color:white;
  font-size: 12px;
}
select,
input[type="text"],
input[type="tele"],
input[type="email"],
input[type="password"]
{
  display: block;
  box-sizing: border-box;
  margin-bottom: 20px;
  padding: 4px;
  padding-left: 16px;
  width: 400px;
  height: 33px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 400;
  font-size: 12px;
  border: 3px solid #e4e4e4;
  border-radius: 17px;
  transition: 0.2s ease;
}
select{
  color: gray;
  background: transparent;
  -moz-appearance: none;
  -webkit-appearance: none;
}	
.select-arrow{
  height: 30px;
  width: 30px;
  position: absolute;
  top: 240px;
  left: 400px;
}
select option {
  color: black;
}
select option[data-default] {
  color: #888;
}


input[type="submit"]{
  display: block;
  box-sizing: border-box;
  margin-bottom: 20px;
  padding: 4px;
  width: 400px;
  height: 35px;
  background: #e67300;
  border: none;
  border-radius: 10px;
  color: #fff;
  font-family: sans-serif;
  font-weight: 500;
  cursor: pointer;
  transition: 0.2s ease;
}
input[type="submit"]:hover,
input[type="submit"]:focus
{
  background: #ffa64d;
  transition: 0.2s ease;
}
.sign-in{
  position: absolute;
  top: 0;
  right: 0;
  box-sizing: border-box;
  padding: 40px;
  width: 500px;
  height: 550px;
  background: linear-gradient(rgba(20,20,20,0.5), rgba(20,20,20,0.5)), 
    url("../assets/dirt-gardening-grow-1214405.jpg");
  background-size: cover;
  background-position: center;
  
}
.or{
  position: absolute;
  top: 265px;
  left: 480px;
  width: 40px;
  height: 40px;
  background: #ffcc9a;
  border-radius: 50%;
  line-height: 40px;
  text-align: center;
  font-size: 12px;
  font-weight: 600;
  font-family: sans-serif;
}
.container {
  display: block;
  position: relative;
  top: 15px;
  padding-left: 35px;
  margin-bottom: 12px;
  cursor: pointer;
  color: white;
  font-size: 14px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/* Hide the browser's default checkbox */
.container input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
  height: 0;
  width: 0;
}

/* Create a custom checkbox */
.checkmark {
  position: absolute;
  border: #fff;
  top: 0;
  left: 155px;
  height: 10px;
  width: 10px;
  background-color: transparent;
  border: 3px solid white;
  border-radius: 2px;
}
.container input:checked ~ .checkmark {
  background-color: #2196F3;
}

/* On mouse-over, add a grey background color */
.container:hover input ~ .checkmark {
  background-color: #ccc;
}

/* Create the checkmark/indicator (hidden when not checked) */
.checkmark:after {
  content: "";
  position: absolute;
  display: none;
}

/* Show the checkmark when checked */
.container input:checked ~ .checkmark:after {
  display: block;
}

/* Style the checkmark/indicator */
.container .checkmark:after {
  left: 2px;
  top: 0px;
  width: 3px;
  height: 6px;
  border: solid white;
  border-width: 0 2px 2px 0;
  -webkit-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  transform: rotate(45deg);
}
input:focus, textarea:focus, select:focus{
        outline: none;
        
}
/* The Modal (background) */
.modal {
  display: block; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: #474e5d;
  padding-top: 50px;
}

/* Modal Content/Box */
.modal-content {
  background-color: #fefefe;
  margin: 5% auto 15% auto; /* 5% from the top, 15% from the bottom and centered */
  border: 1px solid #888;
  width: 80%; /* Could be more or less, depending on screen size */
}

/* Style the horizontal ruler */
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}
 
/* The Close Button (x) */
.close {
  position: absolute;
  left: 1200px;
  top: 15px;
  font-size: 40px;
  font-weight: bold;
  color: #f1f1f1;
}

.close:hover,
.close:focus {
  color: #f44336;
  cursor: pointer;
}
</style>
