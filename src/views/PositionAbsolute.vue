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
    position: relative;
    .inner {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
    }
}
</style>
