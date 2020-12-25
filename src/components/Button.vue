<template>
<button class="ds-button" @click="emit('click')">
 <slot/>
</button>
</template>

<script setup>
/* eslint-disable */
import {defineEmit} from 'vue'
const emit = defineEmit(['click'])

</script>

<style>
.ds-button {
  background-color: red;
}
</style>
