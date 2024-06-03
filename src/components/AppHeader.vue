<script>

import Links from './Links.vue';
import Jumbtron from './Jumbtron.vue';


export default {
  components: {
   Links,
   Jumbtron,

    
  },
}





</script>




<template>
  <header>
    <div class="number container">
      <div class=" row align-items-start">
        <div class="col">
          (001) 88451234 88455438
        </div>
        <div class="col">
          One of three columns
        </div>
      </div>
    </div>


    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container text-cemter">
        <a class="navbar-brand" href="#"><img class="logo" src="../assets/photo/cropped-icon-32x32.png" alt=""> Phlox Business</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText"
          aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <Links></Links>
  
        <span class="navbar-text">
          <button type="button" class="btn btn-primary">PURCHASE</button>
        </span>
      </div>
    </nav>
    <Jumbtron></Jumbtron>



  </header>










</template>



















<style scoped>
header {
  background-color: 3d3d3d
}

.navbar>.container,{
  position:fixed

}
</style>
