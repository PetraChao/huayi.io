<template>
  <div class="header">
    <img class="logo" alt="Vue logo" src="../assets/logo.png">
    <div>贵州华亿河山科技有限公司</div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    // msg: String
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
.logo{
  width: 50px;
  float: left;
}
.header{
  line-height: 50px;
  overflow: hidden;
  margin: 10px;
}
</style>
