<template>
    <div>
        <heador/>
        <hslider/>
        <novice/>
        <borrow/>
        <money/>
        <product/>
        <life/>
        <footor/>

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
import Footor from '../public/Footer.vue'
 
export default {
  components: {
    Heador,
    Hslider,
    Novice,
    Borrow,
    Money,
    Product,
    Life,
    Footor
  }
}
</script>

<style lang="scss" module>

</style>
