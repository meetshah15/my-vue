<template>
  <div>
    <h1>I'm {{ msg }}.</h1>
    <h2>This is my first Vue Project</h2>
  </div>
</template>

<script>
export default {
  name: 'Meet',
  props: {
    msg: String
  }
}
</script>

<style scoped>

</style>
