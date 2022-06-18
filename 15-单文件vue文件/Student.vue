<template>
<div>
    <h1 class="demo">{{name}}</h1>
</div>
  
</template>

<script>
export default {
    name:'Student',
    data() {
        return {
            name: '张三',
        };
    },

}
</script>

<style>
.demo{
    background: red;
}
</style>