<template>
  <div>
    <p>姓名：{{name}}</p>
    <p>年龄：{{age}}</p>
  </div>
</template>

<script>
export default {
  data(){
    return {
      name:"鸡你太忙",
      age:23
    }
  }
}
</script>

<style scoped>
p{
  background-color: pink;
}
</style>