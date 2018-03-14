<template>
  <div class="hello">
    <app-header name="Bank Voice"/>
    <h1>{{msg}}</h1>
  </div>
</template>

<script>
import AppHeader from '../atom/AppHeader.vue'
export default {
  name: 'HelloWorld',
  components: {
    AppHeader
  },
  data () {
    return {
      msg: 'The open platform that allows you to voice out your thoughts'
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
