<template>
  <div class="hello">
    父组件
    <Shopmsg></Shopmsg>
    <Shoplist></Shoplist>
  </div>
</template>

<script>
import Shopmsg from "../components/shopmsg"
import Shoplist from "../components/shoplist"

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    Shopmsg,
    Shoplist
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
