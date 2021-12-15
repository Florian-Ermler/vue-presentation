<template>
    <point-of-interest>
        <p class="font-bold">What is Vue</p>
        <ul class="list-disc list-inside">
            <li><a href="#vueOrigin" class="hover:underline">Origin and goals</a></li>
            <li><a href="#whatIsVue" class="hover:underline">What is a Framework?</a></li>
        </ul>

        <p class="font-bold pt-5">Basics: HTML</p>
        <ul class="list-disc list-inside">
            <li><a href="#whatIsVue" class="hover:underline">What is HTML?</a></li>
            <li><a href="#whatIsVue" class="hover:underline">Bloated files</a></li>
            <li><a href="#whatIsVue" class="hover:underline">How to render conditional views</a></li>
        </ul>

        <p class="font-bold pt-5">Basics: JavaScript</p>
        <ul class="list-disc list-inside">
            <content-link :link="'#abc'"> What is JavaScript </content-link>
            <content-link :link="'#abc'">The modern way of web</content-link>
        </ul>

        <p class="font-bold pt-5">Conclusion</p>
        <content-link :link="'#abc'">Maintainability drawbacks without Vue</content-link>
        <content-link :link="'#abc'">Vue's solution</content-link>

        <p class="font-bold pt-5">Gettig started with Vue</p>
        <ul class="list-disc list-inside">
            <content-link :link="'#abc'">First steps</content-link>
            <content-link :link="'#abc'">How to build your first component</content-link>
        </ul>

        <p class="font-bold pt-5">More about Vue</p>
        <ul class="list-disc list-inside">
            <content-link :link="'#abc'">Achive Vue Mastery</content-link>
            <content-link :link="'#abc'">Supporting the devs</content-link>
        </ul>

        <a href="#sources" class="font-bold pt-5 hover:underline">Sources</a>
    </point-of-interest>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import PointOfInterest from '../point-of-interest';
import ContentLink from './ContentLink.vue';

export default defineComponent({
    name: 'TableOfContents',
    components: {
        PointOfInterest,
        ContentLink,
    },
    setup() {
        return {};
    },
});
</script>
