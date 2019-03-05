<template>
    <div>
        <heador/>
        <hslider/>

    </div>
</template>

<script>
import Heador from '../public/Header.vue'
import Hslider from '../home/Hslider.vue'

export default {
  components: {
    Heador,
    Hslider
  }
}
</script>

<style lang="scss" module>
@import '../../css/element.scss'
</style>
