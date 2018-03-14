<template>
  <header>
    <div class="brand">
      {{name}}
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
  props: {
    name: {
      type: String,
      required: true,
      default: 'AppName'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "../../styles/theme.scss";

header {
  height: 60px;
  line-height: 60px;
}
.brand {
  color: $coral-red;
  font-weight: bold;
  border: 2px solid $coral-red;
  height: 30px;
  line-height: 30px;
  display: inline-block;
  padding: 0 20px;
}
</style>
