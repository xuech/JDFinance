<template lang="html">
    <div>
        <Heador/>
        <HSlider/>
        <Novice/>
        <Borrow/>
    </div>
</template>

<script>
import Heador from "../public/JDHeader.vue"
import HSlider from "../home/hslider.vue"
import Novice from "../home/novice.vue"
import Borrow from "../home/borrow.vue"
export default {
    components:{
        Heador,
        HSlider,
        Novice,
        Borrow
    }
}
</script>

<style lang="scss" module>

</style>
