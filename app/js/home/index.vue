<template>
    <div>
        <heador/>
        <hslider/>
        <novice/>
        <borrow/>
        <money/>

    </div>
</template>

<script>
import Heador from '../public/Header.vue'
import Hslider from './Hslider.vue'
import Novice from './Novice.vue'
import Borrow from './Borrow.vue'
import Money from './Money.vue'

export default {
  components: {
    Heador,
    Hslider,
    Novice,
    Borrow,
    Money
  }
}
</script>

<style lang="scss" module>
@import '../../css/element.scss'
</style>
