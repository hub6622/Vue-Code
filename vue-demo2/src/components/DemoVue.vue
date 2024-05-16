<template>
    <h3>条件渲染</h3>
    <div v-if="type === 'A'">could you see me???</div>
    <div v-else-if="type === 'B'">看我</div>
    <div v-else>666</div>
    <div v-show="flag">能看到</div>
</template>

<script>
export default {
    data(){
        return{
            flag:true,
            type:"A"
        }
    }
}
</script>