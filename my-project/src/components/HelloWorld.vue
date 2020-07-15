<template>
  <div class="hello">
    <h1>Hellow PWA Vue</h1>
    <div class="Gif"><iframe src="https://giphy.com/embed/Nx0rz3jtxtEre" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.Gif {
width:100%;
height:0;
padding-bottom:50%;
position:relative;
max-width: 1000px;
display: block;
margin-left: auto;
margin-right: auto;
  
}
h1 {
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  text-decoration: underline hotpink;
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
</style>
