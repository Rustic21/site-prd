<template>
    <div class="container">
      <div class="box-top">
        <!-- <div class="box-img">
          <img src="~/assets/logo/logo2.png" alt=""> 
          <div class="text-index-page">
            <h1>titulo</h1>
          </div>
        </div> -->
        <div class="text-inside">
          <h1>titulo</h1>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae mollitia fugiat accusantium explicabo obcaecati in dolorum, saepe quia neque quidem, velit cum esse tenetur modi nostrum error deleniti nisi sint!
        </div>
      </div>

      <div class="highligths">
        <Highligths></Highligths>
      </div>

      <div class="menu">
        <OurMenu></OurMenu>
      </div>

      <div class="about-us">
        <AboutUs></AboutUs>
      </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.container {
  // margin-top: 64px;
}

.box-top {
  width: 100%;
  height: 60vh;
  background-image: url('~/assets/logo/hero-bg.jpg'); 
  background-size: cover;
  // padding: 300px 0px 200px 0px;
  position: relative; 
  // display: flex;
  // justify-content: center;
}

.text-inside {
  position: absolute;
  top: 250px;
  left: 100px;
  border: 1px solid purple;
  color: white;
  max-width: 50vw;
}

.highligths, .menu, .about-us {
  border: 1px solid red;
  margin: 30px 0px; 
  padding: 25px;
}

@media screen and (max-width: 800px) {
  .text-inside {
    top: 100px;
    left: 30px;
  }
}
</style>