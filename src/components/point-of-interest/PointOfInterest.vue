<template>
    <div class="m-5 p-5 rounded shadow-2xl w-2/3 text-3xl">
        <slot />
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'PointOfInterest',
    setup() {
        return {};
    },
});
</script>
