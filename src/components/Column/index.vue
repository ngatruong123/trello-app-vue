<template>
    <div class="column">
        <header>
            Brainstorm
        </header>
        <ul class="task-list">
            <Task class="task-item" />
            <li class="task-item">Add what you'd like to work on below</li>
            <li class="task-item">Add what you'd like to work on below</li>
            <li class="task-item">Add what you'd like to work on below</li>
            <li class="task-item">Add what you'd like to work on below</li>
        </ul>
        <footer> Add another card</footer>
    </div>
</template>

<script lang="ts">
import Task from '@/components/Task/index.vue';
// import { initialData } from '@/initialData/initialData';

import { defineComponent } from 'vue'

export default defineComponent({
  components: { Task },
})

</script>

<style src="./style.scss" lang="scss" scoped></style>