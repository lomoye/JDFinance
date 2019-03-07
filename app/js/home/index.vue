<template>
    <div>
        <heador/>
        <hslider/>
        <novice/>
        <borrow/>
        <money/>
        <product/>
        <life/>

    </div>
</template>

<script>
import Heador from '../public/Header.vue'
import Hslider from './Hslider.vue'
import Novice from './Novice.vue'
import Borrow from './Borrow.vue'
import Money from './Money.vue'
import Product from './Product.vue'
import Life from './Life.vue'

export default {
  components: {
    Heador,
    Hslider,
    Novice,
    Borrow,
    Money,
    Product,
    Life
  }
}
</script>

<style lang="scss" module>
@import '../../css/element.scss'
</style>
