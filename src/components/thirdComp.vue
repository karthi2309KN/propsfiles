<template>
<div class="content">
  <h2>Third Component</h2>
  <button @click="counter++"> {{counter}}click</button>
</div>
</template>

<script>
export default {
  name:"thirdComp",
  data() {
    return {
      counter:0
    };
  }
}
</script>

<style scoped>
h2{
  color: aqua;
}
.content{
  background-color: firebrick;
}

</style>