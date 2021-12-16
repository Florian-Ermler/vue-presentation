<template>
    <header class="sticky top-0 z-50 bg-slate-600">
        <h1 class="flex flex-row justify-center items-center p-5">
            <img src="https://vuejs.org/images/logo.svg" alt="vue-logo" class="h-32" />
            <p class="text-4xl font-bold underline">Vue.js a modern, modular compund framework</p>
        </h1>
    </header>
    <main class="flex flex-col justify-center items-center">
        <table-of-contents />
        <origin-of-vue />
        <basic-html />
        <basic-js />
        <conclusion />
        <how-to-start />
        <improve-your-skills />
        <exercise />
        <sources />
    </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import TableOfContents from './components/table-of-contents';
import OriginOfVue from './components/origin-of-vue';
import BasicHtml from './components/basic-html';
import BasicJs from './components/basic-js';
import Conclusion from './components/conclusion';
import HowToStart from './components/how-to-start';
import ImproveYourSkills from './components/improve-your-skills';
import Exercise from './components/exercise';
import Sources from './components/sources';

export default defineComponent({
    components: {
        TableOfContents,
        OriginOfVue,
        BasicHtml,
        BasicJs,
        Conclusion,
        HowToStart,
        ImproveYourSkills,
        Exercise,
        Sources,
    },
    setup() {},
});
</script>

<script setup lang="ts"></script>
