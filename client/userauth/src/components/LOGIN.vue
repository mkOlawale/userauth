<template>
  <div class="hi">
    <div class="container">
      <h1 class="form-header">E-Commerce</h1>
      <h2 class="account">Create Your Free  Account</h2>
      <div class="parralel">
      <span>Don't Have an account</span><a href="/">Sign Up</a>
      </div>
      <div class="input-container">
        <input type="email" placeholder="Email Addres" required>
        <input type="password" placeholder="Password" required>
            <button class="btn">Sign Up</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>
<style scoped>
  .container{
    /* position: absolute; */
    /* top: 15%;
    left: 30%; */
    margin: 0 auto;
     /* top: 50px; */
     /* align-items: center;
     justify-content: center; */
    background-color: #2264f39a;
    height: auto;
    width: 30%;
    padding: 50px;
    box-shadow: 
    12px 12px 16px 0 rgba(0, 0, 0, 0.25),
    -8px -8px 12px 0 rgba(255, 255, 255, 0.3);
  }
  .account{
    /* margin-top: -10px; */
    color: white;
    padding: 10px;
  }
  .hi{
    background-color: #2264f39a;
    height: 100vh;
    position: relative;
  }
  /* .parralel{
    display: flex;
    flex-direction: row;
  }
  p{
    flex:3;
  }
  span{
    flex: 1;
  } */
  span{
    /* margin: 1px 35px; */
    padding: 5px;
    color: white;
  }
  a{
    /* margin: 1px; */
    padding: 1px;
    color: #2e0ab1;
    cursor: pointer;
  }
  .form-header{
    font-size: 25px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    padding-top: 30px;
    padding-left: 10px;
    color: #2622f3f8;
    justify-content: center;
    text-align: center;
  }
  .input-container{
    display: flex;
    flex-direction: column;
    margin: 5px;
    padding: 10px;
  }
  input{
    padding: 15px 15px;
    margin: 5px;
    font-size: 14;
    border: none;
    border-radius: 10px;
  }
  .btn{
    padding: 10px 10px;
    margin: 5px;
    font-size: 14;
    background-color: #2622f3f8;
    border: none;
    color: white;
    font-size: 15px;
    cursor: pointer;
  }
  @media (max-width: 740px){
    .container{
      width: 50%;
    }
    .input{
      width: 100%;
    }
  }
</style>

