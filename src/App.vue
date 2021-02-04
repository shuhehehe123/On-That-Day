<template>
  <ShowTime></ShowTime>
</template>

<script>
import ShowTime from "@/components/ShowTime";

export default {
  name: 'App',
  components: {
    ShowTime,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
