<script>
  import AppTitle from "@/components/AppTitle.vue"

  export default{
    name: "Home",
    components: {
      AppTitle,
    },
    data(){
      return{

      }
    }
  }
</script>

<template>
  <div class="pg-wrapper">
    <AppTitle/>
  </div>
</template>

<style scoped>
  .pg-wrapper{
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>