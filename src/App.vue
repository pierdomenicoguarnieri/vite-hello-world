<script>
  import AppTitle from "@/components/AppTitle.vue"
  import AppHero from "@/components/AppHero.vue"

  export default{
    name: "Home",
    components: {
      AppTitle,
      AppHero,
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
    <AppHero/>
  </div>
</template>

<style scoped>
  .pg-wrapper{
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
</style>