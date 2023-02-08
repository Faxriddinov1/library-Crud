<template>
    <div class="cont">
        <h3>Password-Reset</h3>
        <small>Enter the email address ,</small><br>
        <small>that you have connected to your phone</small>
        <h4>Email address</h4>
        <form action="cont">
          <div class="field">
            <span class="fa fa-user"></span>
            <input type="text" required placeholder="Email or Phone " class="email"><br/>
            </div>
            <div class="field">
            
            <input type="submit"  value="login" class="login"><br>
            <a href="" class="a">back to the exitpage</a>
            </div>
        </form>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.cont{
 margin-left: 200px;
 margin-top: 200px;
  
}

.email{
  padding: 5px;
}
.small{
  margin-top: 30px;
}
.field input{
margin-top: 10px;
  height: 30%;
  width: 30%;
  color: #222;
  font-size: 16px;
  font-family: 'Poppins',sans-serif;
}


.field input[type="submit"]{
  background: #3498db;
  border: 1px solid #2691d9;
  color: white;
  font-size: 18px;
  letter-spacing: 1px;
  font-weight: 600;
  cursor: pointer;
  font-family: 'Montserrat',sans-serif;
}
.field input[type="submit"]:hover{
  background: #2691d9;
}
.a{
  margin-left: 100px;
}
</style>