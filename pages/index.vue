<template>
    <div id="app">
        <div class="box">
            <div class="title">Latest Posts</div>
        </div>
    </div>
</template>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }
    .box {
        width: 50%;
        margin: auto;
        padding-top: 1.5em;
        padding-bottom: 1.5em;
        border-bottom: solid 1px #2c3e50;
    }
    .title {
        margin: 1em;
        font-weight: bold;
    }
    .title-light {
        margin: 1em;
        font-style: italic;
    }
    img {
        width: 70%;
        max-width: 500px;
        padding: 1em;
    }
    .post-list {
        vertical-align: middle;
        padding: 0;
    }
    .cell {
        vertical-align: middle;
        display: inline-block;
    }
    a {
        color: #2c3e50;
        background-color: transparent;
        text-decoration: none;
        display: inline-block;
        padding: 5px;
    }
    ul {
        list-style: none;
        margin: 0;
    }
</style>