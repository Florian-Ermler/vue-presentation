<template>
    <point-of-interest id="vueOrigin">
        <h1 class="text-center font-bold underline">How to start</h1>

        <div class="text-center mt-5"><a href="https://vuejs.org/" class="underline"> Visit Vuejs.org</a></div>
    </point-of-interest>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import PointOfInterest from '../point-of-interest';

export default defineComponent({
    components: {
        PointOfInterest,
    },

    setup() {},
});
</script>
