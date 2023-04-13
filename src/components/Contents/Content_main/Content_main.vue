<script setup lang="ts">
import Search from './Search/Search.vue'
import TableContainer from './TableMain/TableContainer.vue'
</script>

<template>
    <div id="contents_main">
        <Search/>
        <TableContainer/>
    </div>
</template>


<style scoped lang="scss">
    #contents_main {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    // overflow-x: scroll;
    padding: 0px;
    gap: 24px;
    width: 100%;
    height: 100%;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
    }
</style>