<template>
  <div class="hello">
    
    
    <p>
      El equipo Birras Team se formo en ...
      </p>
  </div>
</template>

<script>
export default {
  name: 'SobreNosotros', 
  data() {
  return {
    
  }
},
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hello {
  text-align: center;
}
</style>
