<template>
  <div>
    <home-header></home-header>
    <div>首页</div>
  </div>
</template>

<script>
import Header from './components/Header'
export default {
  name: 'Home',
  components: {
    HomeHeader: Header
  }
}
</script>
