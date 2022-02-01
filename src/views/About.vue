<template>

   
<div class="container">
  <div class="row">

    <div class="col-sm">
      <img src="https://i.postimg.cc/3NHmJdmT/exab.jpg" alt="me" class="abt-image">
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
     
      <h1 class="abttt">About</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <h1 class="subt txttt">Hi, I am Diego Allies. A freelance web designer, front & back end developer.</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <p class="main-txt txttt">"I am a fast learner who works well in a team as well as being capable of working individually. I thrive in an environment where I am able to take initiative and use my problem-solving skills. Furthermore, I aspire to be a Full-Stack Developer. <br><br> My passion for programming came from my level of skill in it. I have naturally always solved problems that are coding related and found that I have a good understanding of how it all works. This has motivated me to study further and continue in this field." </p>
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
  margin-left: -70%;
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

.main-txt {
  margin-top: 5%;
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
}

.abttt {
  margin-left: -100%;
  margin-top: 5%;
  font-size: 39px;
  font-family: "Josefin Sans";
  
}

.txttt {
  margin-left: -10%;
  text-align: initial;
}

p {
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}

.back2home {
  margin-left: 0%;
}

.btn {
  padding: 10px 60px;
    height: 45px;
    font-size: 16px;
}


</style>