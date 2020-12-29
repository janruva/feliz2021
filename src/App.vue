<template>
  <div id="app">
    <HelloWorld msg="Jair Andrés Ruiz"/>
    <div id="mensaje">
      <h2>Te desea..</h2>
      <h2>12 meses de PROSPERIDAD </h2>
      <h2>52 semanas de ALEGRÍA</h2>
      <h2>365 días de ÉXITO</h2>
      <h2>8.760 horas de SALUD</h2>
      <h2>525.600 minutos de SUERTE</h2>
      <h2>3.153.600 segundos de AMOR!</h2>
      </div>
    <div id="imagen">
      <img alt="felizaño" src="./assets/feliz2021.gif">
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Brush Script MT;
  text-align: center;
  color: #d60a0a;
  margin-top: 10px;
  background-color: azure;
}
h2 {
color: #4947c4;
font-family: 'Segoe UI';
background-color: powderblue;
}
#mensaje {
  width: 400px;
  height: 400px;
  display: inline;
}
#imagen {
  width: 500px;
  height: 400px;
  background-color: aquamarine;
  display: inline;
}
</style>
