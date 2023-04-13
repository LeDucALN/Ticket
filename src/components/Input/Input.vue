<script setup lang="ts">
import { placeholder } from '@babel/types';
import { defineProps } from 'vue';
const props = defineProps({
    width: {
        type: String,
        default: '226px'
    },
    flexgrows: {
        type: Number,
        default: 1,
    },
    place: {
        type: String,
        default: 'placeholder'
    }
})
</script>

<template>
   <input class="inp" type="text" :placeholder="place" :style="{'flex-grow': flexgrows, 'width': width}"/>
</template> 


<style scoped lang="scss">
.inp {
    width: 226px;
    height: 23px;
    font-style: normal;
    font-weight: 300;
    font-size: 15px;
    line-height: 22px;
    color: #000000;
    flex: none;
    order: 2;
    flex-grow: 1;
    border: none;
}



</style>