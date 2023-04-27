
<script>
export default {
  name: "titolo",
  data(){
    return{
      title: "La mia prima app con Vite!"
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