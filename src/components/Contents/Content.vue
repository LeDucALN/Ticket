<script setup lang="ts">
import Content_title from './Content_title/Content_title.vue'
import Content_main from './Content_main/Content_main.vue'

</script>

<template>
    <div id="contents">
        <Content_title />
        <Content_main />
    </div>
    
</template>

<style scoped lang="scss">
#contents {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 16px 24px;
        gap: 12px;
        width: 100%;
        height: 100%;
        // overflow-y: scroll;
        background-color: antiquewhite;
    }
</style>

