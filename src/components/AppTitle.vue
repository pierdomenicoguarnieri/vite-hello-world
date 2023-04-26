<script>
export default {
  data(){
    return{
      titleMsg: "La mia prima app con Vite!",
    }
  }
}
</script>

<template>
  <h1>{{titleMsg}}</h1>
</template>

<style scoped>
  h1{
    color: white;
    transition: all .5s;
    text-align: center;
  }

  h1:hover{
    color: wheat;
    text-shadow: 0 0 25px;
    cursor: default;
  }
</style>