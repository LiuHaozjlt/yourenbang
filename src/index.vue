<template>
    <div>
        <headr/>
        <tab></tab>
        <foot/>
    </div>
</template>

<script>
import headr from '../src/components/header'
import foot from '../src/components/footer'
import slide from './components/slide'
import tab from './components/tab'
export default {
    data(){
        return{

        }
    },
    components:{
        headr,
        foot,
        slide,
        tab
    }
    
}
</script>

<style>
.el-tabs__nav{
    float:none!important;
}
</style>

