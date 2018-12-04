<template lang="html">
    <div>
        <Heador/>
        <HSlider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Product/>
    </div>
</template>

<script>
import Heador from "../public/JDHeader.vue"
import HSlider from "../home/hslider.vue"
import Novice from "../home/novice.vue"
import Borrow from "../home/borrow.vue"
import Money from "../home/money.vue"
import Product from "./product.vue"

export default {
    components:{
        Heador,
        HSlider,
        Novice,
        Borrow,
        Money,
        Product
    }
}
</script>

<style lang="scss" module>

</style>
