<template>
  <div class="hello headerrr">
    <h1>{{ msg }}</h1>
  </div>
    <p class="intro">I am Junior Web developer able to build a Web presence from the ground up - from concept, navigation, layout and programming to UX and SEO. Skilled at writing well-designed, testable and efficient code using current best practices in Web development. Fast learner, hard worker and team player who is proficient in an array of scripting languages and multimedia Web tools.</p>

    <div class="container">

  <div class="row">

    <div class="col">
      <router-link :to="{ name: 'About' }" class="btn btn-rabbit mnn">About</router-link>
    </div>
    
  </div>


  <div class="row">

    <div class="col">
      <router-link :to="{ name: 'Work' }" class="btn btn-rabbit mnn">Work</router-link>
    </div>

  </div>

    <div class="row">

    <div class="col">
     <router-link :to="{ name: 'Contact' }" class="btn btn-rabbit mnn">Contact</router-link> 
    </div>

  </div>
  
</div>



</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.headerrr {
  margin-top: 12%;
  margin-bottom: 10%;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
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

.intro {
  margin-bottom: 10%;
}
</style>
