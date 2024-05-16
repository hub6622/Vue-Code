<script>
export default {
    data(){
        return{
            msg:"ppg666",
            hello:"hello world",
            html:"<a href='https://www.baidu.com'>百度</a>"
        }
    }
}
</script>

<template>
  <h3>文本插值</h3>
  <p>{{ msg }}</p>
  <p>{{ hello }}</p>
  <h3>html传输</h3>
  <p v-html="html"></p>
</template>
