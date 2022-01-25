<template>
  <div class="hello headerrr">
    <h1>{{ msg }}</h1>
  </div>
   
<div class="container">
  <div class="row">

    <div class="col-sm">
      <img src="https://i.postimg.cc/gcVmwn8T/wrk.jpg" alt="me" class="abt-image">
    </div>

    <div class="col-sm">
       <div class="container">

  <div class="row">
    <div class="col">
      <router-link to="/" class="btn btn-rabbit back-btn mnn">Back to Home</router-link>
    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <h1 class="back-btn">Work</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet cumque tempora ducimus assumenda nemo ipsum, numquam exercitationem? Provident culpa amet tempora veritatis at ut harum, perspiciatis dolorum pariatur. Eius eligendi necessitatibus accusamus veniam fugit id assumenda fuga quam commodi at. Iure quidem illo libero laborum rerum, sapiente odit voluptas temporibus aperiam ab earum accusantium deserunt hic ipsa quam debitis autem. Quod tempora harum numquam aliquid enim blanditiis, impedit ipsa expedita reiciendis. Quisquam debitis asperiores natus at repudiandae, illum sit! Explicabo cum unde id nobis neque enim consequuntur fugit earum voluptatem facere adipisci, dolores, iste optio animi dicta obcaecati accusamus expedita!</p>

    </div>
  </div>

</div>

    </div>
  
  </div>
</div>

   


</template>

<script>

import * as mdb from 'mdb-ui-kit';
import {input} from 'mdb-ui-kit';

export default {
  
}
</script>

<style scoped>

@import '~mdb-ui-kit/css/mdb.min.css';
.abt-image {
  width: 85%;
}

.back-btn {
  margin-left: -90%;
  margin-top: 15%;
}

.mnn {
    background-color: #fff;
    color: #111;
    font-style: italic;
    border: 1px solid #111;
    border-radius: 0px !important;
    transition: all 0.4s ease-in-out;
    margin-bottom: 20px;
    font-family: "Crimson";
    font-size: 13px;
}

  
</style>