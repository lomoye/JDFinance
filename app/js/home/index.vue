<template>
    <div>
        <heador/>
        <hslider/>
        <novice/>

    </div>
</template>

<script>
import Heador from '../public/Header.vue'
import Hslider from '../home/Hslider.vue'
import Novice from '../home/Novice.vue'

export default {
  components: {
    Heador,
    Hslider,
    Novice
  }
}
</script>

<style lang="scss" module>
@import '../../css/element.scss'
</style>
