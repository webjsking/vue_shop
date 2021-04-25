<template>
    <div>
        <el-button type="info" @click="logout">退出</el-button>
    </div>
</template>

<script>
export default {
    methods: {
        logout() {
           this.$router.push("/login"); 
        }
    }
}
</script>

<style Lang="less" scoped>

</style>
