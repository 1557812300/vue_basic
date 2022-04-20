<template>
  <school></school>
  <student></student>
</template>

<script>
import School from './School.vue'
import Student from './Student.vue'
//引入组件：
export default {
    name:'APP'
    components: { School, Student },

}
</script>

<style>

</style>