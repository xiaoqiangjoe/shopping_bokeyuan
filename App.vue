<template>
    <div><h3>{{msg}}</h3></div>
</template>

<script>
    export default {
        data(){
            return{
                msg:'单文件测试'
            }
        }
    }
</script>

<style scoped>
    h3{
        color: red;
    }
</style>