<template>
    <div class="board-content">
        <column />
        <column />
        <column />
    </div>
</template>

<script lang="ts">
import column from '@/components/Column/index.vue';

import { defineComponent } from 'vue'

export default defineComponent({
  components: { column },
})

</script>

<style src="./style.scss" lang="scss" scoped></style>