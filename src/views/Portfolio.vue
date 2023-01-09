<template>
 
   
<div class="container">
  <div class="row main-page">

    <div class="col-sm w3-animate-left margg">
            <router-link to="/" class="btn btn-rabbit back-btn mnn mbv"><i class="fas fa-angle-left bbn">  </i>   <span class="back2home">Back to Home</span> </router-link>
      <img src="https://i.postimg.cc/KvgP12NH/93-FB55-E4-851-D-43-E4-86-AC-0658-ACD86632.jpg" alt="me" class="abt-image">
    </div>

    <div class="col-sm w3-animate-right">
       <div class="container">

  <div class="row">
    <div class="col">
      <router-link to="/" class="btn btn-rabbit back-btn mnn ccvv"><i class="fas fa-angle-left bbn">  </i>   <span class="back2home">Back to Home</span> </router-link>
    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <h1 class="abttt">Projects</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     
      <h1 class="subt txttt ccvv"> .</h1>

    </div>
  </div>

  <div class="row that-coll">
    <div class="col">
        <div class="pushRight margg">

 <div v-if="portfolios" class="port-cont ccvv downWra">

            <div class="that-col">
<div v-for="portfolio of portfolios" :key="portfolio.id" class="port-cont">
                <img class="ports" :src="portfolio.img" alt="sh"> <br>
                <div class="titlee"> {{portfolio.title}} </div>
                
            </div>



            </div>
            
            <div class="that-col">
<div v-for="portfolio of portfolios1" :key="portfolio.id" class="port-cont">
                <img class="ports" :src="portfolio.img" alt="sh"> <br>
                    <div class="titlee"> {{portfolio.title}} </div>
            </div>



            </div>


            
        </div>

        <!-- new code
        this is where i changed responsivity

        
         -->
 <div v-if="portfolios" class="mbv upWra">

            <div class="row">
<div v-for="portfolio of portfolios" :key="portfolio.id" class="col-sm-12 ccl">
                <div class="moreRes">

     <img class="ports" :src="portfolio.img" alt="sh"> <br>

                    <div class="titlee"> {{portfolio.title}} </div>
  </div>
                
            </div>



            </div>
            
            <div class="row">
<div v-for="portfolio of portfolios1" :key="portfolio.id" class="col-sm-12 ccl">
  <div class="moreRes">

     <img class="ports" :src="portfolio.img" alt="sh"> <br>

                    <div class="titlee"> {{portfolio.title}} </div>
  </div>
               
            </div>



            </div>


            
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
  },

  data(){
      return {
        portfolios: [
        { "title": "SECOND PORTFOLIO", "id": 4, "details": "lorem", "img": "https://i.postimg.cc/DyZbgFyT/sec.png"},
        { "title": "POS PROJECT", "id": 5, "details": "lorem", "img": "https://i.postimg.cc/Y9CpHrP2/Screenshot-from-2022-01-26-11-44-39.png"},
        { "title": "BMI CALCULATOR", "id": 6, "details": "lorem", "img": "https://i.postimg.cc/N0pKTzqM/Screenshot-from-2022-01-26-11-47-35.png"}
    ],

    portfolios1: [
        { "title": "RSA ID GENERATOR", "id": 1, "details": "lorem", "img": "https://i.postimg.cc/bN16HQ6b/id1.png", "class":"first-line1"},
        { "title": "FIRST PORTFOLIO", "id": 2, "details": "lorem", "img": "https://i.postimg.cc/28VfG9sJ/portfolio1.png"},
        { "title": "LEARN CODE", "id": 3, "details": "lorem", "img": "https://i.postimg.cc/BbFRWRJQ/fir.png"},

    ]

    

      }
  },


  
}
</script>

<style scoped>

@import '~mdb-ui-kit/css/mdb.min.css';
.abt-image {
  width: 85%;
  height: 30.5%;
  margin-left: 3.5%;
}

.mbv {
  visibility: hidden;
}

.back-btn {
  margin-left: -70%;
  margin-top: 14%;
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
  margin-left: -8.5%;
  margin-top: 5%;
  font-size: 39px;
  font-family: "Josefin Sans";
  text-align: start;
  
}

.txttt {
  margin-left: -8.5%;
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

.ports {
    width: 180px;
    height: 100px;
}

.port-cont {
    display: inline-block;
    margin-left: -13.28%;
    margin-right: 18%;
    margin-top: 3%;
    padding: 1%;
    text-align: center !important;
    
}

img.ports {
  border-radius: 5%;
  margin-left: -20%;
}




.that-col {
      display: flex;
}

.main-page {
  overflow: hidden;
}

.pushRight {
    margin-right: -20%;
    margin-left: 20%;

}

.margg {
  margin-bottom: -120%;
}

.titlee {
font-family: fantasy;
 margin-left: -20%;
 font-weight: bold;
}


.main-page {
  overflow: hidden;
}

/* new code */

.downWra {
  margin-bottom: -100%;
}

.entireFooter {
  margin-top: -3.6%;
}

@media only screen and (max-width: 553px) {
  .abt-image {
    margin-top: 5%;
    margin-bottom: -10%;
    margin-left: -5%;
    margin-right: -5%;
  }

  .back-btn {
    margin-left: 0%;

  }

  .mbv {
    visibility: visible;
  }

  .ccvv {
    visibility: hidden;
  }

  .upWra {
    margin-top: -100%;
  }

  .margg {
    margin-bottom: 0;
  }

  .ccl {
    margin-left: -27%;
  }

  .abttt {
    margin-left: 0;
  }

  .moreRes {
    margin-top: 5%;
    margin-bottom: 5%;
  }

  



}


</style>