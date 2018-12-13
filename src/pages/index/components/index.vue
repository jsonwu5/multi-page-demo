<template>
  <div class="content">
    <span>欢迎访问首页</span><br>
    <div>
      <a class="link" href="user.html">用户详情</a>
      <a class="link" href="about.html">关于我们</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'index'
}
</script>

<style scoped>
  .content {
    width: 100%;
    height: 100%;
    background-color: #f4ecd9;
    text-align: center;
    font-size: 30px;
    color: black;
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .link {
    border: 1px solid #ff9300;
    border-radius: 4px;
    padding: 5px;
    color: #ff9300;
    text-decoration: none;
    width: 200px;
    margin: 0 auto;
  }
</style>
