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
        <router-link to="/" class="btn btn-rabbit back-btn mnn"><i class="fas fa-angle-left bbn">  </i>   <span class="back2home">Back to Home</span> </router-link>
    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <h1 class="conttt">Contact</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <p class="subt">Im based in Cape Town in RSA, near epping industrial , drop me a line</p>

    </div>
  </div>

  <div class="row">
    <div class="col">
     <form class="form_edit" method="post"  action="https://formspree.io/f/mlezjjjp"> 
        <div class="form-group">
            <input type="name" class="form-control bgg mnnm" id="exampleInputName" placeholder="Name">
        </div>

        <div class="form-group">
        <input type="email" class="form-control bgg mnnm" id="exampleInputEmail1" placeholder="Email">
        </div>

        <div class="form-group">
        <textarea class="form-control bgg mnnm" rows="5" placeholder="Message"></textarea>
        </div>
   <button type="submit" class="mnn btn btn-rabbit submit bgg bggn">Send Message</button>
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
  margin-left: -69%;
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

.mnnm {
  background-color: #fff !important;
    color: #111 !important;
    border: 1px solid #111;
}

.contact-text {
    margin-left: -16%;
    margin-top: 1%;
}

.subt {
    font-style: italic;
    font-weight: 600;
    font-size: 20px;
    color: #3b3b3b;
    line-height: 28px;
    font-family: "Crimson";
    margin-top: 15px;
    margin-bottom: 20px;
    padding-right: 40px;
    margin-left: -10.1%;
}

.conttt {
  margin-left: -94.7%;
  margin-top: 5%;
  font-size: 39px;
  font-family: "Josefin Sans";
  
}

.btn {
  padding: 10px 60px;
    height: 45px;
    font-size: 16px;
}

.bgg {
  margin-bottom: 5%;
  margin-left: -9.6%;
}

.bggn {
  margin-left: -71.7%;
}
</style>