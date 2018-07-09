<template>
    <div id="app">
        <p>
            STHO's electron webpack vue boilerplate
            <br>
            Knock yourself out! 
        </p>    
    </div>    
</template>
<script lang="ts">
    import Vue from "vue";
    import {Component} from "vue-property-decorator";

    @Component({
        name: "app"
    })
    export default class App extends Vue {
        
    }
</script>
<style lang="scss">
    *, *:after, *:before {
        box-sizing: border-box;
    }
    
    html, body {
        margin: 0;
        padding: 0;
        border: 0;
        font-family: Arial, sans-serif;
        height: 100%;
        width: 100%;
    }
    
    #app {
        width: 100%;
        height: 100%;
        background: #222;
        color: white;
        position: relative;
        
        p {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
        }
    }
</style>