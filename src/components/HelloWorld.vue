<template>
  <div>
    <h1>first component</h1>
    <button @click="counter++">counter||{{counter}}</button>
  </div>

</template>

<script>

export default {
  name: 'HelloWorld',components:{

  },
  props: {
    msg: String
  },
  data(){
    return{
      counter:0
    };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
  margin:0;
  background-color: #42b983;
  justify-content:center;
}
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
button{
  background-color: yellow;
  padding:7px 12px;
  border-radius: 12px;
  border:0;
  box-shadow: #2c3e50;
}
.button:hover{
  background-color: aliceblue;
}
</style>
