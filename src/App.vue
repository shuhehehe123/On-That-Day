<template>
  <Heading></Heading>
  <Form></Form>
</template>

<script>
//import ShowTime from "@/components/ShowTime";
//这行为原来的显示时间
import Form from "@/components/Form";
import Heading from "@/components/Heading";

export default {
  name: 'App',
  components: {
    Heading,
    Form,

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
