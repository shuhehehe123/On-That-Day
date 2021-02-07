<template>
  <Heading></Heading>
  <Body></Body>
</template>

<script>
//import ShowTime from "@/components/ShowTime";
//这行为原来的显示时间
import Heading from "@/components/Heading";
import Body from "@/components/Body";

export default {
  name: 'App',
  components: {
    Heading,
    Body,

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
