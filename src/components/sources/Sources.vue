<template>
    <point-of-interest id="sources">
        <h1 class="text-center">Sources</h1>
        <ul>
            <source-link :link="'https://vuejs.org/images/logo.svg'" :date="'02.05.2022'" />
            <source-link :link="'https://cdn-media-1.freecodecamp.org/images/0*xkJgg-6HskYrQ3N7.jpeg'" />
            <li>c</li>
            <li>d</li>
            <li>e</li>
            <li>f</li>
        </ul>
    </point-of-interest>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import PointOfInterest from '../point-of-interest';
import SourceLink from './SourceLink.vue';

export default defineComponent({
    name: 'Sources',
    components: {
        PointOfInterest,
        SourceLink,
    },
    setup() {
        return {};
    },
});
</script>
