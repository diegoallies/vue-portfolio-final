<template>
  
   
<div class="container">
  <div class="row">

    <div class="col-sm w3-animate-left">
    <router-link to="/" class="btn btn-rabbit back-btn mnn bnnn mbv"><i class="fas fa-angle-left bbn">  </i>   <span class="back2home">Back to Home</span> </router-link>
      <img src="https://i.postimg.cc/c4Y3sc1q/D85-ADA04-101-D-40-F4-9521-EFE0957-CFCAE.jpg" alt="me" class="abt-image">
    </div>

    <div class="col-sm w3-animate-right">
       <div class="container">

  <div class="row">
    <div class="col">
     <router-link to="/" class="btn btn-rabbit back-btn mnn bnnn cvvv"><i class="fas fa-angle-left bbn">  </i>   <span class="back2home">Back to Home</span> </router-link>
    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <h1 class="back-btn workkk">Skills</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     
     

    </div>
  </div>

  

  <div class="row">
    <div class="col">
     

<div class="row d-flex justify-content-center mt-100 push-away">
    <div class="col">
      
        <div > <div class="progress yellow"> <span class="progress-left"> <span class="progress-bar"></span> </span> <span class="progress-right"> <span class="progress-bar"></span> </span>
            <div class="progress-value"> <i class="fab fa-js slg"></i> </div>
        </div> </div>

       <div> <div class="progress green"> <span class="progress-left"> <span class="progress-bar"></span> </span> <span class="progress-right"> <span class="progress-bar"></span> </span>
            <div class="progress-value"> <i class="fab fa-vuejs slg"></i> </div>
        </div> </div> 

        <div> <div class="progress grey"> <span class="progress-left"> <span class="progress-bar"></span> </span> <span class="progress-right"> <span class="progress-bar"></span> </span>
            <div class="progress-value"> <i class="fab fa-html5 slg"></i> </div>
        </div> </div> 

       <div>  <div class="progress blue"> <span class="progress-left"> <span class="progress-bar"></span> </span> <span class="progress-right"> <span class="progress-bar"></span> </span>
            <div class="progress-value"> <i class="fab fa-css3 slg"></i> </div>
        </div> </div> 

        <div> <div class="progress greene"> <span class="progress-left"> <span class="progress-bar"></span> </span> <span class="progress-right"> <span class="progress-bar"></span> </span>
            <div class="progress-value"> <i class="fab fa-node slg"></i> </div>
        </div> </div> 

      <div>   <div class="progress purple"> <span class="progress-left"> <span class="progress-bar"></span> </span> <span class="progress-right"> <span class="progress-bar"></span> </span>
            <div class="progress-value"> <i class="fab fa-bootstrap slg"></i> </div>
        </div> </div> 
        

    </div>
</div>


    </div>
  </div>

</div>

    </div>
  
  </div>
</div>

   

  <Footer />

</template>

<script>

import * as mdb from 'mdb-ui-kit';
import {input} from 'mdb-ui-kit';
import Footer from '@/components/Footer.vue'


export default {
    components: {
        Footer
    }
  
}
</script>

<style scoped>

@import '~mdb-ui-kit/css/mdb.min.css';
.abt-image {
  width: 85%;
  height: 90%;
  margin-left: -1%;
}

.back-btn {
  margin-left: -68%;
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

.workkk {
  margin-left: -100%;
  margin-top: 5%;
  font-size: 39px;
  font-family: "Josefin Sans";
  
}

.txttt {
  margin-left: -8.7%;
  margin-top: 5%;
  text-align: initial;
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

.btn {
  padding: 10px 60px;
    height: 45px;
    font-size: 16px;
}

/* new  code */



.progress {
    width: 126px;
    height: 126px !important;
    float: left;
    line-height: 150px;
    background: none;
    margin: 20px;
    box-shadow: none;
    position: relative
}

.progress:after {
    content: "";
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: 12px solid #fff;
    position: absolute;
    top: 0;
    left: 0
}

.progress>span {
    width: 50%;
    height: 100%;
    overflow: hidden;
    position: absolute;
    top: 0;
    z-index: 1
}

.progress .progress-left {
    left: 0
}

.progress .progress-bar {
    width: 100%;
    height: 100%;
    background: none;
    border-width: 12px;
    border-style: solid;
    position: absolute;
    top: 0
}

.progress .progress-left .progress-bar {
    left: 100%;
    border-top-right-radius: 80px;
    border-bottom-right-radius: 80px;
    border-left: 0;
    -webkit-transform-origin: center left;
    transform-origin: center left
}

.progress .progress-right {
    right: 0
}

.progress .progress-right .progress-bar {
    left: -100%;
    border-top-left-radius: 80px;
    border-bottom-left-radius: 80px;
    border-right: 0;
    -webkit-transform-origin: center right;
    transform-origin: center right;
    animation: loading-1 1.8s linear forwards
}

.progress .progress-value {
    width: 90%;
    height: 90%;
    border-radius: 50%;
    background: #000;
    font-size: 50px;
    color: rgb(255, 255, 255);
    line-height: 135px;
    text-align: center;
    position: absolute;
    top: 5%;
    left: 5%
}

.progress.blue .progress-bar {
    border-color: #049dff
}

.progress.blue .progress-left .progress-bar {
    animation: loading-2 0.5s linear forwards 0.8s
}

.progress.blue .progress-right .progress-bar {
    animation: loading-1 0.8s linear forwards
}

.progress.purple .progress-right .progress-bar {
    animation: loading-1 0.8s linear forwards
}

.progress.grey .progress-right .progress-bar {
    animation: loading-1 0.8s linear forwards
}


.progress.grey .progress-left .progress-bar {
    animation: loading-grey 0.5s linear forwards 0.8s
}

.progress.purple .progress-left .progress-bar {
    animation: loading-grey 0.5s linear forwards 0.8s
}


.progress.greene .progress-right .progress-bar {
    animation: loading-node 0.5s linear forwards 0.1s
}



.progress.green .progress-left .progress-bar {
    animation: loading-5 0.5s linear forwards 0.8s
}

.progress.green .progress-right .progress-bar {
    animation: loading-1 0.8s linear forwards 0s
}



.progress.yellow .progress-bar {
    border-color: #fdba04
}

.progress.purple .progress-bar {
    border-color: #951ab4
} 

.progress.grey .progress-bar {
    border-color: #5f5f5f
}

.progress.green .progress-bar {
    border-color: #42e719
}

.progress.greene .progress-bar {
    border-color: #42e719
}

.progress.yellow .progress-right .progress-bar {
    animation: loading-1 0.8s linear forwards
}


.progress.yellow .progress-left .progress-bar {
    animation: loading-15 0.5s linear forwards 0.8s
}


@keyframes loading-1 {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(180deg);
        transform: rotate(180deg)
    }
}

@keyframes loading-grey {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(160deg);
        transform: rotate(160deg)
    }
}


@keyframes loading-15 {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(70deg);
        transform: rotate(70deg)
    }
}

@keyframes loading-5 {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg)
    }
}


@keyframes loading-vue {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(80deg);
        transform: rotate(80deg)
    }
}


@keyframes loading-node {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(30deg);
        transform: rotate(30deg)
    }
}


@keyframes loading-2 {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(144deg);
        transform: rotate(144deg)
    }
}

@keyframes loading-3 {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(135deg);
        transform: rotate(135deg)
    }

  
}

/* new code */


/* new code */

.mbv {
    visibility: hidden;
}
/* footer style */
@media only screen and (max-width: 553px) {
  .abt-image {
    margin-top: 5%;
    margin-bottom: 15%;
    margin-left: -5%;
    margin-right: -5%;
  }

  .back-btn {
    margin-left: 0%;

  }

  .workkk {
      margin-left: -70%;
  }

  .abttt {
    margin-left: 0;
  }

  .mbv {
    visibility: visible;
  }

  .cvvv {
    visibility: hidden;
  }

  

.progress {
    width: 84px;
    height: 84px !important;
    float: left;
    line-height: 100px;
    background: none;
    margin: 20px;
    box-shadow: none;
    position: relative
}

.progress:after {
    content: "";
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: 12px solid #fff;
    position: absolute;
    top: 0;
    left: 0
}

.progress>span {
    width: 50%;
    height: 100%;
    overflow: hidden;
    position: absolute;
    top: 0;
    z-index: 1
}

.progress .progress-left {
    left: 0
}

.progress .progress-bar {
    width: 100%;
    height: 100%;
    background: none;
    border-width: 8px;
    border-style: solid;
    position: absolute;
    top: 0
}

.progress .progress-left .progress-bar {
    left: 100%;
    border-top-right-radius: 53px;
    border-bottom-right-radius: 53px;
    border-left: 0;
    -webkit-transform-origin: center left;
    transform-origin: center left
}

.progress .progress-right {
    right: 0
}

.progress .progress-right .progress-bar {
    left: -100%;
    border-top-left-radius: 53px;
    border-bottom-left-radius: 53px;
    border-right: 0;
    -webkit-transform-origin: center right;
    transform-origin: center right;
    animation: loading-1 1.8s linear forwards
}

.progress .progress-value {
    width: 90%;
    height: 90%;
    border-radius: 50%;
    background: #000;
    font-size: 33px;
    color: rgb(255, 255, 255);
    line-height: 90px;
    text-align: center;
    position: absolute;
    top: 5%;
    left: 5%
}
 .push-away {
     margin-bottom: 7%;
     margin-left: -11%;
 }


}
</style>