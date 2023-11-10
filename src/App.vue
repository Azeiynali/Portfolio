<template>
    <div id="app">
        <siteHeader></siteHeader>
    </div>
</template>

<script>
import siteHeader from "./components/header.vue";

export default {
    name: "App",
    components: {
        siteHeader,
    },
};
</script>

<style>
@import url("./static/css/fonts.css");
:root {
    --blue: #4967ff;
    --yellow: #c1fd33;
    --gray: #a3a9c3;
    --dark: #1c2025;
    --red: #ff4f49;
    --base: #54baff;
}
* {
    box-sizing: border-box;
    font-family: "Baloo Bhaijaan 2" !important;
    padding: 0;
    flex-shrink: 0;
    margin: 0;
}
body {
    width: 100vw;
    min-height: 100vh;
    background-color: #0a0c0f;
}
small {
    color: #cacaca;
}
#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #dfe6ec;
    display: flex;
    align-items: center;
    flex-direction: column;
    margin-top: 30px;
}
</style>
