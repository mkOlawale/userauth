<template>
  <div class="hi">
    <div class="container">
      <div class="image">
        <img src="@/assets/Koala.jpg">
      </div>
      <h1 class="form-header">Welcome</h1>
      <h2 class="account">Abeebolaking1@gmail.com</h2>
            <button class="btn">log out</button>
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
.image {
  margin: 0 auto;
  /* position: relative; */
  text-align: center;
}
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
    text-align: center;
  }
  .hi{
    background-color: #2264f39a;
    height: 100vh;
    position: relative;
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
  img{
    height: 100px;
    width: 100px;
    object-fit: cover;
    border-radius: 50%;
    /* margin: auto; */
    /* position: absolute; */
  }
  .btn{
    padding: 10px;
    margin: 5px;
    background-color: #2622f3f8;
    border: none;
    float: right;
    color: white;
    /* font-size: 15px; */
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

