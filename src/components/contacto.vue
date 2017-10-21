<template>
  <div>
    <h1>Contacto</h1>
  <ul>
    <li v-for="item in arreglo">
      {{item}}
    </li>
  </ul>
  </div>
</template>

<script>
export default{
  data(){
  return {
    arreglo:[
      'Comenzar el ejemplo',
      'Terminar el ejemplo'
    ]
  }

  }
}
</script>

<style>
</style>
