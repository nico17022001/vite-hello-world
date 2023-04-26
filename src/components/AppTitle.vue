<script>
export default {
  name: "AppTitle",
  data(){
    return{
      titolo: "La mia prima app con Vite!"
    }
  }
}
</script>

<template>
  <div id="sfondo">
    <h1>{{ titolo }}</h1>
  </div>
</template>

<style scoped>
  h1{
    color: white;
  }
  #sfondo{
    display: flex;
    justify-content: center;
    align-items: center;
    background: rgb(2,0,36);
    background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,212,255,1) 100%);
    width: 100vw;
    height: 100vh;
  }

</style>