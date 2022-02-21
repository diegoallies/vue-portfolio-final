<template>
  <div class="home" id="index">

    <div class="container">
  <div class="row">
    <div class="col-sm w3-animate-right"> 
      <!-- Left Column -->
      <img src="https://i.postimg.cc/1zQVXvL3/exa.jpg" alt="Diego Allies" class="home-image">

    </div>
    <div class="col-sm w3-animate-left">
       <!-- Right Column -->
         <h1><HelloWorld msg="I am Diego Allies"/></h1> 
    </div>
  </div>
</div>
  </div>


<div class="container entireFooter">
  <div class="row">
    <div class="col-sm footSide">

<!-- footer side -->

    </div>
    <div class="col-sm">
      
<!-- Footer -->
<footer class="footrrr">
  <!-- Copyright -->
  <div class="footer-copyright text-center py-3">© 2022 Copyright:
    <a href="https://diegoallies-portfolio-final.netlify.app//">Diego Allies Productions</a>
  </div>
  <!-- Copyright -->
</footer>
<!-- Footer -->


    </div>
    <div class="col-sm footSide">
  <!-- footer side -->
    </div>
  </div>
</div>

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
.home-image {
  width: 86%;
  height: 90%;
}

/* footer style */

.footrrr {
  color: #3b3b3b;
  margin-bottom: -100%;
}

.footSide {
  border-top-style: double;
  margin-bottom: -1%;
  margin-top: 2.5%;
  border-color: rgb(32, 50, 83);
}

.entireFooter {
  margin-top: -4.5%;
}

/* footer style */
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
