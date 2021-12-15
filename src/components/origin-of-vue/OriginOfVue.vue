<template>
    <point-of-interest id="vueOrigin">
        <h1 class="text-center">Origin of Vue</h1>
        <img src="https://cdn-media-1.freecodecamp.org/images/0*xkJgg-6HskYrQ3N7.jpeg" alt="evan you profile" />
        <div>Hi</div>
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
