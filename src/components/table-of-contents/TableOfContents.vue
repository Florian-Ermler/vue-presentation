<template>
    <point-of-interest>
        <p class="font-bold">What is Vue</p>
        <ul class="list-disc list-inside">
            <li><a href="#vueOrigin" class="hover:underline">Origin and goals</a></li>
            <li><a href="#whatIsFramework" class="hover:underline">What is a Framework?</a></li>
        </ul>

        <p class="font-bold pt-5">Basics: HTML</p>
        <ul class="list-disc list-inside">
            <li><a href="#basicHtml" class="hover:underline">What is HTML?</a></li>
            <li><a href="#bloatedFiles" class="hover:underline">Bloated files</a></li>
        </ul>

        <p class="font-bold pt-5">Basics: JavaScript</p>
        <ul class="list-disc list-inside">
            <content-link :link="'#basicJs'"> What is JavaScript </content-link>
            <content-link :link="'#conditionalRender'"> How to render conditional views </content-link>
        </ul>

        <p class="font-bold pt-5">Conclusion</p>
        <content-link :link="'#drawbacks'">Maintainability drawbacks without Vue</content-link>
        <content-link :link="'#solution'">Vue's solution</content-link>

        <p class="font-bold pt-5">Gettig started with Vue</p>
        <ul class="list-disc list-inside">
            <content-link :link="'#gettingStarted'">First steps</content-link>
            <content-link :link="'#firstComponent'">How to build your first component</content-link>
        </ul>

        <p class="font-bold pt-5">More about Vue</p>
        <ul class="list-disc list-inside">
            <content-link :link="'#vueMastery'">Achive Vue Mastery</content-link>
            <content-link :link="'#support'">Supporting the devs</content-link>
        </ul>

        <p class="pt-5">
            <a href="#exercise" class="font-bold hover:underline">Exercise</a>
        </p>
        <p class="pt-5">
            <a href="#sources" class="font-bold hover:underline">Sources</a>
        </p>
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
});
</script>
