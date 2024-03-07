<template>
  <div>
    <img alt="Birras logo" id="birrasImg" src="./assets/BirrasTeam.jpg">
    <h1>{{ inicio }}</h1>
    <nav>
      <a href="#">Sobre el equipo</a>
      <a href="#">Plantilla</a>
    </nav>
    <SobreNosotros />
    <Plantilla />
    <BuscarJugador />
   
  </div>
</template>

<script>
import SobreNosotros from './components/SobreNosotros.vue'
import Plantilla from './components/Plantilla.vue'
import BuscarJugador from './components/BuscarJugador.vue'

export default {
  name: 'App',
  data() {
  return {
    inicio : "Birras Team Padel Pro",
  }
},
  components: {
    SobreNosotros,
    Plantilla,
    BuscarJugador,
  },
  methods: {
    

  }


    
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#birrasImg {
  width: 100%;
  max-width: 400px;
  height: auto;
  border-radius: 95%;
}
</style>
