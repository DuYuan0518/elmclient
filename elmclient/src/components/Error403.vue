<template>
  <div class="wrapper">
    <img src="../assets/error403.png"><br>
    <router-link to="/index">服务器繁忙中，返回重试</router-link>
  </div>
</template>

<script>
export default {
  name: "Error403"
}
</script>

<style scoped>
  .wrapper{
    text-align: center;
  }
  .wrapper img{
    width: 100%;
    margin: 120px 0 20px;
  }
  .wrapper a{
    color: #0097EF;
  }
</style>
