<template lang="html">
    <div>
        <Heador/>
        <Footer cname="money"/>
        <Navi/>
    </div>
</template>

<script>
    import Heador from "../public/JDHeader.vue"
    import Navi from "../public/JDNavigation.vue"
    import Footer from "../public/JDFooter.vue"

    export default {
        components:{
            Heador,
            Navi,
            Footer
        }
    }
</script>

<style lang="scss">
    .money{
        margin-top: 0!important;
        ul{
            li:first-child{
                display: none;
            }
        }
    }
</style>