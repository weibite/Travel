<template>
  <div>
    <home-header></home-header>
    <scroll-banner></scroll-banner>
  </div>
</template>

<script>
import Header from './components/Header'
import ScrollBanner from './components/ScrollBanner'
export default {
  name: 'Home',
  components: {
    HomeHeader: Header,
    ScrollBanner
  }
}
</script>
