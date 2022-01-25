<template>
  <div class="home">


    <div class="container">
  <div class="row">
    <div class="col-sm"> 
      <!-- Left Column -->
      <img src="https://i.postimg.cc/nhnss46M/exa.jpg" alt="image" class="home-image">
    </div>
    <div class="col-sm">
       <!-- Right Column -->
          <HelloWorld msg="I am Diego Allies"/>
    </div>
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
}


</style>
