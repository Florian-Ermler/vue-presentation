<template>
    <point-of-interest id="exercise">
        <h1 class="text-center">Exercise</h1>
        <iframe src="https://codepen.io/florian-ermler/pen/RwLVNzm?editors=1010" frameborder="0"></iframe>
    </point-of-interest>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import PointOfInterest from '../point-of-interest';

export default defineComponent({
    components: {
        PointOfInterest,
    },
    props: {},
    setup(props) {
        return {};
    },
});
</script>
