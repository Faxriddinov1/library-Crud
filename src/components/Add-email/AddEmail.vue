<template>
  <div class="body">
    <div class="cont">
        <h1 class="h1">registertion</h1>
        <header>Add new Email</header>
        <form action="cont">
          <div class="field">
            <span class="fa fa-user"></span>
            <input type="text" required placeholder="Create new email " class="email"><br/>
            <small>Write your new Email</small> <br>
            <input type="text" required placeholder="Email or Phone " class="email"><br/>
            <small class="small">Password</small> <a href="" class="a">Return password</a>
          </div>
          <div class="field space">
            <span class="fa fa-lock"></span>
            <input type="password" class="pass-key" required placeholder="Password" ><br/>
          </div>
          <div class="field">
            
          <input type="submit"  value="login" class="login">
          </div>
          <div>
            <small>Don't have an account?</small><a href="../Add-email/AddEmail.vue">Add an account</a>
          </div>
        </form>
        <div class="links">
          </div> 
 </div>
 <div class="img">
          <img src="/images/img.avif" alt="">
        </div>
 </div>

</template>
<script>


export default {
   
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
  height: 25px;
  width: 100%;
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
.body{
  display: flex;
  justify-content: space-around;
  align-items: center;
  
}


</style>