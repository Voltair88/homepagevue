<template>
  <swiper
    :modules="modules"
    :slides-per-view="1"
    :space-between="50"
    navigation
    :pagination="{ clickable: true }"
    :scrollbar="{ draggable: true }"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
  >
    <swiper-slide>
      <img src="../assets/ZeldaArena.webp" alt="Zelda Arena" />
      <h1>Zelda Arena</h1>
      <p>
        A game made in Typescript and Javascript where you eliminate the enemy
        to get the highest score
      </p>
    </swiper-slide>
    <swiper-slide>
      <img src="../assets/Freshkeeper.webp" alt="Freshkeeper" />
      <h1>Freshkeeper</h1>
      <p>
        A game made in Typescript and Javascript where you eliminate the enemy
        to get the highest score
      </p>
    </swiper-slide>
  </swiper>
</template>
<script lang="ts">
import { Navigation, Pagination, Scrollbar, A11y } from "swiper";
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";
import "swiper/css/scrollbar";
export default {
  components: {
    Swiper,
    SwiperSlide,
  },
};
</script>

<style scoped>
.swiper {
  width: 80%;
  margin: auto;
  padding: auto;
}

.swiper-slide {
  font-size: 18px;
  text-align: center;
  background: antiquewhite;
}
.swiper-slide img {
  width: auto;
  height: 500px;
  border-radius: 10px;
}
h1,
p {
  position: absolute;
  bottom: 0;
  left: 0;
}
</style>