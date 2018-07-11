<template>
    <button class="g-button">按钮</button>
</template>

<script>
    export default {
    }
</script>

<style lang="scss">

    .g-button{
        padding:0 1em;
        height:var(--botton-height);
        border-color: var(--button-border-color);
        border-radius: var(--button-border-redius);
        font-size: var(--font-size);
        &:hover{
                border-color: var(--button-border-hover);
        }
        &:active{
                border-color: var(--button-border-active);
        }
        &:focus{
                outline: none;
        }
    }

</style>