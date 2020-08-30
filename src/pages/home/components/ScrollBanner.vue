<template>
  <div class="wrapper">
    <swiper :options="swiperOptions">
      <swiper-slide v-for="pic of bannerPics"
                    :key="pic.id">
        <img class="swiper-img"
             :src="pic.imgUrl" />
      </swiper-slide>
      <div class="swiper-pagination"
           slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'carrousel',
  data () {
    return {
      swiperOptions: {
        loop: true,
        autoplay: 3000,
        pagination: '.swiper-pagination'
      },
      bannerPics: [{
        id: '0001',
        imgUrl: 'http://img1.qunarzz.com/sight/source/1505/53/02091f1ee43d0a.jpg_r_640x214_2e3256b1.jpg'
      },
      {
        id: '0002',
        imgUrl: 'http://img1.qunarzz.com/sight/source/1811/f3/86173f863bef61.jpg_r_640x214_52b003ac.jpg'
      },
      {
        id: '0003',
        imgUrl: 'http://img1.qunarzz.com/sight/source/1811/7e/476589267ebb41.jpg_r_640x214_bf599709.jpg'
      },
      {
        id: '0004',
        imgUrl: 'http://img1.qunarzz.com/sight/source/1606/85/c6b6bad1b977e.jpg_r_640x214_5c638941.jpg'
      },
      {
        id: '0005',
        imgUrl: 'http://img1.qunarzz.com/sight/source/1505/aa/7baaf8a851d221.jpg_r_640x214_1431200f.jpg'
      }]
    }
  }
}
</script>

<style scoped>
.wrapper {
  overflow: hidden;
  width: 100%;
  height: 0;
  padding-bottom: 36.64%;
}
.swiper-img {
  width: 100%;
}
</style>
