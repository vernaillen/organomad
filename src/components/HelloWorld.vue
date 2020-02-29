<template>
  <div>
    <h1>{{ title }}</h1>
    <h2>{{ subtitle }}</h2>
    <h5>coming soon</h5>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    props: {
      title: String,
      subtitle: String
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  margin: 100px 0;
}
</style>
