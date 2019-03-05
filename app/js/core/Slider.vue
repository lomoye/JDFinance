<template>
   <div>
      <section :class="cname">
         <swiper :options="options" :not-next-tick="options.notNextTick">
            <swiper-slide v-for="item in items" :key="item.href">
               <router-link :to="{ name: item.href }">
                  <img :src="item.src" alt="">
               </router-link>
               <div class="swiper-pagination" v-if="options.pagination"/>
            </swiper-slide>
         </swiper>
      </section>
   </div>
</template>

<script>
import {Swiper, SwiperSlide} from "vue-awesome-swiper" 
export default {
   data() {
       return {}
   },
   props: {
      options: {
         type: Object,
         default() {
            return {
               autoplay: true,
               loop: true,
               pagination: {
                  el: '.swiper-pagination'
               },
               notNextTick: false
            }
         }
      },
      items: {
         type: Array,
         default() {
            return []
         }
      }
   },
  components: {
     Swiper,
     SwiperSlide
  }
}
</script>

<style lang="scss">
@import "~swiper/dist/css/swiper.css";
</style>
