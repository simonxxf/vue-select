<template>
  <div class="city">
    <select >
      <option v-for="item in zipInfo" >
        {{item.name}}
      </option>
    </select>
       
    
  </div>
</template>

<script>
export default {
  components:{},
   props: {
     zipInfo:{
       type:  Array
     }
   },
  data(){
    return {
    }
  },
}
</script>
<style lang='stylus' scoped>
</style>