<template>
    <li>
        <span class="mr-5">-</span>
        <a :href="link" class="underline text-blue-800">{{ link }}</a>
        <span>&nbsp;{{ date }}</span>
    </li>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'SourceLink',
    props: {
        link: { type: String },
        date: { type: String },
    },
    setup(props) {
        const link = props.link;
        const date = props.date;
        return { link, date };
    },
});
</script>
