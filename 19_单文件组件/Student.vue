<template>
    <!-- 组件结构 -->
    <div>
        <h2>学生姓名:{{ name }}</h2>
        <h2>学生年龄:{{ age }}</h2>
        <!-- <button @click="showName">点我提示学校名</button> -->
    </div>
</template>

<script>
export default {
    name: "Student",
    data() {
        return {
            name: "张三",
            address: "20",
        }
    },
    methods: {
        showName() {
            alert(this.name)
        }
    },
}
</script>

<style>
/*组件的样式*/
</style>