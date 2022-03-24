<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>

  <Contador/>
  <Cuadrado/>
  <Botones/>

</template>

<script>
  import Contador from "../components/contador.vue";
  import Cuadrado from "../components/cuadrado.vue";
  import Botones from "../components/botones.vue";

  export default {
    name: 'HomeView',
    components: {
      Contador,
      Cuadrado,
      Botones
    }
  }

</script>

<style>

  div{
    margin-bottom: 10px;
  }

  .botones button{
    font-size: 40px;
  }

  .counter{
    font-size: 40px;
  }

  .cuadrado{
    font-size: 40px;
  }


</style>
