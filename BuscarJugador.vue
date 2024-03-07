<template>
    <div>
        <div class="label">
            Buscar Jugador Birras Team: 
        </div>
        <div class="input">
            <input v-on:keydown.enter="obtenerJugador" v-model="jugador">
        </div>
    </div>

</template>
<script>
export default {
  name: 'BuscarJugador', 
  data() {
  return {
    jugador : "",
    player : "Jugador:\nLuis\nPosicion\nDrive-Reves",
   
    
  }
},
methods : {
    obtenerJugador () {
      alert(this.player);
    }
},
  props: {
  }
}
</script>
<style scoped>
</style>