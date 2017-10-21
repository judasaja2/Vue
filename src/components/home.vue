<template>
  <div>
    <h1>Home</h1>
    <input type="text" placeholder="Texto" v-model="texto">
    <input type="button" value="Cambiar Texto" v-on:click="cambiarTexto">
    <p>{{texto2}}</p>
  </div>
</template>

<script>
export default{
  data(){
    return{
      texto: null,
      texto2: null
    }
  },
  methods:{
    cambiarTexto(){
      this.texto2 = this.texto;
    }
  }
}
</script>

<style>
</style>
