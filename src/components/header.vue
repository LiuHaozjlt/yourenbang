<template>
  <div class="yrb-head">
    <div class="yrb-head-logo">
      <img src="" alt="">
    </div>
    <div class="yrb-head-rit">
      <div v-for="(item,index) in cot" :key="index">{{item.text}}</div>
    </div>
    
  </div>
</template>

<script>
export default {
  data(){
    return{
      cot:[{text:'加入我们'},{text:'了解详情'}]
    }
  }
}
</script>

<style>
  .yrb-head-rit{
    border:2px solid red;
  }
</style>



 

 