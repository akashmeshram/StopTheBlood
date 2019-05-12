<template>
<div>
    <div><h1>STOP THE BLEED</h1></div>
    <br>
    <div><img src="./images/sample-4.jpg"></div>
    
</div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 70px;
  text-align: center;
  color: red;
}

img {
  display: block;
  width: 640px;
  height: 480px;
  margin-left: auto;
  margin-right: auto;
}

</style>
