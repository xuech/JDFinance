<template lang="html">
    <div>
        <Heador/>
        <HSlider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Mission/>
        <Product/>
        <Footer/>
        <Navi/>
    </div>
</template>

<script>
import Heador from "../public/JDHeader.vue"
import Navi from "../public/JDNavigation.vue"
import Footer from "../public/JDFooter.vue"
import HSlider from "../home/hslider.vue"
import Novice from "../home/novice.vue"
import Borrow from "../home/borrow.vue"
import Money from "../home/money.vue"
import Mission from "../home/mission.vue"
import Product from "./product.vue"

export default {
    components:{
        Heador,
        HSlider,
        Novice,
        Borrow,
        Money,
        Mission,
        Product,
        Footer,
        Navi
    }
}
</script>

<style lang="scss" module>

</style>
