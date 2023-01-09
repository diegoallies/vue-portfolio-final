<template>
  <div class="home" id="index">
    <div class="container">
  <div class="row">
    <div class="col-sm w3-animate-right"> 
      <!-- Left Column -->
<div class="imageContainer">
   <img src="https://i.postimg.cc/j2PbJmmr/1765-DB0-F-3-C1-B-4347-BD57-E8-BED21-AF08-E.jpg" alt="Diego Allies" class="home-image">
</div>
    </div>
    <div class="col-sm w3-animate-left">
       <!-- Right Column -->
         <h1><HelloWorld msg="I am Diego Allies"/></h1> 
    </div>
  </div>
</div>
  </div>
  <Footer />
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Footer
  }
  
}
</script>

<style scoped>
.imageContainer {
  width: 85%;
  height: 90%;
  margin-left: -5%;
}

.home-image{
  width: 100%;
  height: 100%;
}

/* media querries */

@media only screen and (max-width: 553px) {
  .home-image {
    margin-top: 15%;
    margin-bottom: 15%;
    margin-left: -5%;
    margin-right: -5%;
  }

  .col-sm {
    margin-left: 0%;
    margin-right: 0%;
  }

  .footrrr {
    margin-top: 10%;
  }



}
</style>
