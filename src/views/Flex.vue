<template>
    <div class="outer">
        <div class="inner">灰色区域，居中了！</div>
    </div>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.outer {
    // 关键代码
    display: flex;
    // 水平居中
    //justify-content: center;
    // 垂直居中
    align-items: center;
}
</style>
