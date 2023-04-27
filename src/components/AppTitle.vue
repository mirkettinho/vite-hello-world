
<script>
export default {
  name: "titolo",
  data(){
    return{
      title: "Hello World"
    }
  }
}
</script>

<template>
  <h1>{{ title }}</h1>
</template>

<style scoped>
h1{
  color: green;
}
</style>