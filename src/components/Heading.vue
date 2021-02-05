<template>
  <div class="heading">
    <h3>今天是{{ year }}年{{ month }}月{{ date }}日</h3>
  </div>
</template>

<script>
export default {
  name: "Heading",
  data: function (){
    return {
      year: new Date().getFullYear(),
      month: (new Date().getMonth())+1,//Javascript默认0月为一月
      date: new Date().getDate()

    };
  }
}
</script>

<style scoped>
.heading{
  text-align:center;
  border-style:solid;
  border-color: #2193d5;
  width:800px;
  height:50px;
  border-width:1.618px;
  position:relative;
  left:250px;
}
</style>