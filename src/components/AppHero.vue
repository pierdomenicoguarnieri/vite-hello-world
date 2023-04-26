<script>
export default {
  data(){
    return{
      contentImg: "../public/vite.svg"
    }
  }
}
</script>

<template>
  <div class="pg-jumbotron">
    <img :src="contentImg" :alt="contentImg">
  </div>
</template>

<style scoped>
  .pg-jumbotron{
    height: 300px;
    width: 300px;
    margin-top: 50px;
  }
  
  .pg-jumbotron img{
    height: 100%;
    will-change: filter;
    transition: filter 300ms;
  }

  .pg-jumbotron img:hover{
    filter: drop-shadow(0 0 2em rgba(100, 108, 255, 0.667));
  }
</style>