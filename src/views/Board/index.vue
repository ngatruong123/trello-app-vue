<template>
    <div class="trello-app">
        <AppBar />
        <BoardBar />
        <BoardContent />
        
    </div>
</template>

<script lang="ts">
import AppBar from '@/components/AppBar/index.vue';
import BoardBar from '@/components/BoardBar/index.vue';
import BoardContent from '@/components/BoardContent/index.vue';

import { defineComponent } from 'vue'
export default defineComponent({
  components: { AppBar, BoardBar, BoardContent },
})
</script>

<style src="./style.scss" lang="scss" scoped></style>