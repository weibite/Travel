<template>
    <div class="header">
      <div class="header-left"><div class="iconfont back-font">&#xe685;</div></div>
      <div class="header-middle"><span class="iconfont">&#xe67d;</span>
      输入城市名称</div>
      <div class="header-right">城市<span class="iconfont">&#xe688;</span></div>
    </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
.header{
  line-height: .86rem;
  display: flex;
  background-color: rgb(76, 157, 250);
  color: white;
}
.header-left{
  width: .64rem;
  float: left;

}
.back-font{
  text-align: center;
  font-size: .4rem;
}
.header-middle{
  flex: 1;
  background: white;
  border-radius: .1rem;
  height: .64rem;
  line-height: .64rem;
  margin-top: .12rem;
  margin-left: .12rem;
  padding-left: .2rem;
  color: #cccccc;
}
.header-right{
  width: 1.24rem;
  float: right;
  text-align: center;
}
</style>
