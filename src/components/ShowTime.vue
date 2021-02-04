<template>
  <div class="centre">
    <h1>今天是{{ year }}年{{ month }}月{{ date }}日</h1>
  </div>
</template>

<script>

export default {
  name: "Calender",
  data: function (){
    return {
      year: new Date().getFullYear(),
      month: (new Date().getMonth())+1,//Javascript默认0月为一月
      date: new Date().getDate()

    };
  },
  /*
  props:{
    date:new Date()
  }
  传参测试
  */
}
</script>

<style scoped>
.centre{
  text-align:center;
}
</style>