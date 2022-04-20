<template>
    <div class="a2">
        <h2>学生姓名：{{name}}</h2>
        <h2>学生年龄：{{age}}</h2>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name:'小米',
            age:16
        }
    },
}
</script>

<style>
    .a2{
        border: 2em;
        border-block-color: pink;
    }
</style>