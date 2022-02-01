<template>

  <transition name="fade" mode="out-in">

    <router-view/>

  </transition>


</template>

<script>

import * as mdb from 'mdb-ui-kit';
import {input} from 'mdb-ui-kit';

export default {
  
}
</script>

<style>

@import '~mdb-ui-kit/css/mdb.min.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100vw;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
/* animation */
.w3-animate-right {

  position:relative;
  animation:animateright 1.2s
  }
  
  @keyframes animateright {
    from{right:-500px;opacity:0.6} 
    to{right:0;opacity:1}}

/* gap */

.w3-animate-left {
  position:relative;
  animation:animateleft 1.2s
  }
  
  @keyframes animateleft {
    from{left:-500px;opacity:0.6}
    to{left:0;opacity:1}
    }

@media only screen and (max-width: 553px) {

  .col-sm {
    margin-left: 0%;
    margin-right: 0%;
  }

  .footrrr {
    margin-top: 10%;
  }



}


</style>
