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
        <sources />
    </main>
    <button
        @click="toTop"
        class="
            fixed
            right-5
            bottom-5
            z-50
            shadow-xl
            rounded-full
            bg-slate-200
            w-10
            h-10
            text-3xl
            flex
            justify-center
            items-center
        "
    >
        ^
    </button>
</template>

<script lang="ts">
import { computed, defineComponent, onMounted } from 'vue';
import TableOfContents from './components/table-of-contents';
import OriginOfVue from './components/origin-of-vue';
import Sources from './components/sources';

export default defineComponent({
    components: {
        TableOfContents,
        OriginOfVue,
        Sources,
    },
    setup() {
        const toTop = function () {
            window.scrollTo({
                top: 0,
                behavior: 'smooth',
            });
        };

        return { toTop };
    },
});
</script>

<script setup lang="ts"></script>
