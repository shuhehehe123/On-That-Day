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
  position:fixed;
  border-style:solid;
  border-color: #87c5f6;
  width:100%;
  height:auto;
  top:0;
  margin-bottom:5px;
  background: #d2eaf3;

  /*left:250px;
  float:top;*/
}
</style>