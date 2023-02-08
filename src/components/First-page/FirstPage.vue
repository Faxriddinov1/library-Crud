<template>
    <div class="cont">
      <h1 class="h1">access</h1>
        <header>Login Form</header>
        <form action="cont">
          <div class="field">
            <span class="fa fa-user"></span>
            <input type="text" required placeholder="Email or Phone " class="email"><br/>
            <small class="small">Password</small> <a href="" class="a">Return password</a>
          </div>
          <div class="field space">
            <span class="fa fa-lock"></span>
            <input type="password" class="pass-key" required placeholder="Password" ><br/>
            <div class="eyeButton">
          <span @mousedown="show = !show" @mouseup="show = !show" @touchstart="show = !show" @touchend="show = !show" style="cursor: pointer;">eye_icon</span>
        
          </div>
          <div class="field">
            
          <input type="submit"  value="login" class="login">
          </div>
          </div>
          <div>
            <small>Don't have an account?</small><a href="../Add-email/AddEmail.vue">Add an account</a> 
          </div>
        </form>
        <div class="links">
          </div>
 
 
</div>
</template>
<script>




export default {
    components: { }
}
</script>
<style>

.h1{
   margin-left: 50px;

}
.cont{
 margin-left: 200px;
 margin-top: 200px;
  
}

.email{
  padding: 10px;
}
.small{
  margin-top: 30px;
}
.a{
  margin-left: 190px;
}

.pass-key{
  padding: 10px;
}



.field input{
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

.login{
  margin-top: 30px;
  padding: 5px;
}

.eyeButton {
  position: absolute;
  right: 5px;
  bottom: 4px;
  top: 23px;
}

</style>