<template>
  <div class="hello headerrr">
    <h1>{{ msg }}</h1>
  </div>
   
<div class="container">
  <div class="row">

    <div class="col-sm">
      <img src="https://i.postimg.cc/8zq0BbVB/contact.jpg" alt="me" class="abt-image">
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
     
      <h1 class="back-btn">Contact</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <p class="">Im based in Cape Town in RSA , near epping industrial , drop me a line</p>

    </div>
  </div>

  <div class="row">
    <div class="col">
     <form class="form_edit"> 
                            <div class="form-group">
                                <input type="name" class="form-control" id="exampleInputName" placeholder="Name">
                            </div>

                            <div class="form-group">
                            <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Email">
                            </div>

                            <div class="form-group">
                            <textarea class="form-control" rows="5" placeholder="Message"></textarea>
                            </div>
                            <button type="submit" class="btn btn-rabbit submit">Send Message</button>
                        </form>
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