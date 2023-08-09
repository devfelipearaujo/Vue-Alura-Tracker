<template>
<div class="box has-text-weight-bol">
<slot></slot>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
   name:'Box',
})
</script>

<style scoped>
.box {
   background: #FAF0CA
} 
</style>