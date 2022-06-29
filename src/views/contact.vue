<template>

   
<div class="container">
  <div class="row">

    <div class="col-sm w3-animate-left">
      <router-link to="/" class="btn btn-rabbit back-btn mnn mbv"><i class="fas fa-angle-left bbn">  </i>   <span class="back2home">Back to Home</span> </router-link>
      <img src="https://i.postimg.cc/8zq0BbVB/contact.jpg" alt="me" class="abt-image">
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
     
      <h1 class="conttt">Contact</h1>

    </div>
  </div>

  <div class="row">
    <div class="col">
     <div class="forThat">
  <p class="subt">Im based in Cape Town in RSA, drop me a line</p>


     </div>
    
    </div>
  </div>

  <div class="row">
    <div class="col">
     <form class="form_edit" action="https://formspree.io/f/xnqwyraz" method="POST"> 
        <div class="form-group">
            <input type="name" class="form-control bgg mnnm" id="exampleInputName" placeholder="Name" name="Name">
        </div>

        <div class="form-group">
        <input type="email" class="form-control bgg mnnm" id="exampleInputEmail1" placeholder="Email" name="Email">
        </div>

        <div class="form-group">
        <textarea class="form-control bgg mnnm" rows="5" placeholder="Message" name="Message"> </textarea> 
        </div>
   <button type="submit" class="mnn btn btn-rabbit submit bgg bggn">Send Message</button>
    </form>
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
  data() {
    return {
      name: '',
      email: '',
      message: '',
    }
  },


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
  margin-left: -69%;
  margin-top: 15%;
}

.mbv {
  visibility: hidden;
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
  margin-bottom: 3.8%;
  margin-left: -9.6%;
}

.bggn {
  margin-left: -71.7%;
}


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

  .mbv {
    visibility: visible;
  }

  .ccvv {
    visibility: hidden;
  }

  .conttt {
    margin-left: -59%;
  }

  .subt {
    margin-left: 0%;
    text-align: start;
  }

  .forThat {
    margin-left: 0%;
  }

  form {
    margin-left: 0;
  }

  .mnnm {
    margin-left: 0;
  }

  .mnn {
    margin-left: -17%;
    margin-bottom: 20%;
  }



}
</style>