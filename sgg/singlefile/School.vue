<template>
  <div>
    <p>学校名称：{{name}}</p>
    <p>学校口号：{{slogan}}</p>
  </div>
</template>

<script>
export default {
  data(){
    return {
      name:"群众路小学",
      slogan:"为中华之崛起而读书！"
    }
  }
}
</script>

<style scoped>
  p{
    background-color: aquamarine;
  }
</style>