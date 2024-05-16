<template>
    <h3>条件渲染</h3>
    <div v-if="type === 'A'">could you see me???</div>
    <div v-else-if="type === 'B'">看我</div>
    <div v-else>666</div>
</template>

<script>
export default {
    data(){
        return{
            flag:false,
            type:"A"
        }
    }
}
</script>