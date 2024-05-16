<script>
export default {
  data(){
    return{
      msg:"ppg666",
      dynamicclass:"appClass",
      dynamicid:"appId",
      buttonCondition:false,
      Attrs:{
        class:"appClass",
        id:"appId"
      }
    }
  }
}
</script>

<template>
  <p>{{ msg }}</p>
  <button :disabled="buttonCondition">Button</button><br>
  <a href="#" v-bind:class="dynamicclass" :id="dynamicid">000</a>
  <div v-bind="Attrs">666</div>
</template>

<style>
.appClass{
  color: red;
  font-size: 30px;
}
</style>