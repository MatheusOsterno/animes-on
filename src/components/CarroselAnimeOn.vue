<template>
    <swiper
      :slidesPerView="1"
      :spaceBetween="30"
      :loop="true"
      :pagination="{
        clickable: true,
      }"
      :navigation="true"
      :modules="modules"
      class="mySwiper"
>
      <swiper-slide><img src="@/img/hero/1046568.jpg" alt=""></swiper-slide>
      <swiper-slide><img src="@/img/hero/13.jpg" alt=""></swiper-slide>
      <swiper-slide><img src="@/img/hero/download.jpg" alt=""></swiper-slide>
      <swiper-slide><img src="@/img/hero/naruto-uzumaki-naruto-38828-2560x1600.jpg" alt=""></swiper-slide>
      <swiper-slide><img src="@/img/hero/hero-1.jpg" alt=""></swiper-slide>
      <swiper-slide><img src="@/img/hero/jujutsu_kaisen_itadori_yuuji_wallpaper_by_muztnafi_deg6kcz-350t.jpg" alt=""></swiper-slide>
    </swiper>
  </template>
  <script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from "swiper/vue";
  
  // Import Swiper styles
  import "swiper/css";
  
  import "swiper/css/pagination";
  import "swiper/css/navigation";
  
  // import required modules
  import { Pagination, Navigation } from "swiper";
  
  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Pagination, Navigation],
      };
    },
  };
  </script>

<style scoped>
#app { height: 100% }
html,
body {
  position: relative;
  height: 100%;
}

body {
  background: rgb(0, 0, 0);
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-size: 30px;
  color: #000;
  margin: 0;
  padding: 0;
}

.swiper {
    margin-top: 20px;
  width: 100%;
  height: 100%;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;


  /* Center slide text vertically */
  display: -webkit-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  -webkit-align-items: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.swiper {
  margin-left: auto;
  margin-right: auto;
}

.mySwiper img {

    border-radius: 40px;
    border-bottom: 35px solid rgb(176, 0, 0,.8);
    height: 650px;
    width: 1100px;
}

@media (max-width: 1024px) {
    .mySwiper img {
        border-bottom: 30px solid white;
        border-radius: 40px 40px 0 0;
        height: 350px;
        width: 600px;
}
}
    
</style>