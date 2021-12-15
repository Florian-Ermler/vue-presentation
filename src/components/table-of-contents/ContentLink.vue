<template>
    <li>
        <a :href="link" class="hover:underline hover:cursor-pointer"> <slot /> </a>
    </li>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import PointOfInterest from '../point-of-interest';

export default defineComponent({
    name: 'TableOfContents',
    components: {
        PointOfInterest,
    },
    props: {
        link: { type: String },
    },
    setup(props) {
        const link = props.link;
        return { link };
    },
});
</script>
