<template>
  <div class="XPFirst">
    <h1>{{ msg }}</h1>
    <div>Index</div>
    <br />
    <router-link to="/first/">FirstIndex</router-link>
    <router-link to="/first/helloworld/">HelloWorld</router-link>
    <router-link to="/first/xpfirst/">xpfirst</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'FirstIndex',
  data () {
    return {
      msg: 'FirstIndex欢迎你'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
