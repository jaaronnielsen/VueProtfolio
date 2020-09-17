<template>
  <div class="skills">
    <h1>{{ msg }}</h1>
    <h3>Languages</h3>
    <ul>
      <li>PHP</li>
      <li>Java</li>
    </ul>
    <h3>Soft skills</h3>
    <ul>
      <li>Core Docs</li>
      <li>Forum</li>
      <li>Community Chat</li>
      <li>Twitter</li>
      <li>News</li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li>vue-router</li>
      <li>vuex</li>
      <li>vue-devtools</li>
      <li>vue-loader</li>
      <li>awesome-vue</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Resume',
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
</style>
