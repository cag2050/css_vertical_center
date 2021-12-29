<template>
    <div id="app">
        <div id="nav">
            <router-link to="/">Home</router-link>
            |
            <router-link to="/about">About</router-link>
            |
            <router-link to="/Base">Base</router-link>
            |
            <router-link to="/Flex">align-items: center;</router-link>
            |
            <router-link to="/LineHeight">align-items: center;</router-link>
            |
            <router-link to="/PositionAbsolute"
                >position: absolute;</router-link
            >
            |
        </div>
        <div>---下面是内容---</div>
        <router-view />
    </div>
</template>

<style lang="less">
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    //text-align: center;
    color: #2c3e50;
}

#nav {
    //padding: 30px;

    a {
        font-weight: bold;
        color: #2c3e50;

        &.router-link-exact-active {
            color: #42b983;
        }
    }
}

// 公共样式
.outer {
    background-color: yellow;
    width: 600px;
    height: 400px;

    .inner {
        width: 400px;
        height: 200px;
        background-color: #ccc;
    }
}
</style>
