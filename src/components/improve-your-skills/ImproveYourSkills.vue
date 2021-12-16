<template>
    <point-of-interest id="vueMastery">
        <h1 class="text-center font-bold underline">Improve and support Vue</h1>
        <div class="flex flex-col mt-10 justify-center items-center">
            <a href="https://www.vuemastery.com/">
                <img
                    src="https://www.vuemastery.com/images/vuemastery-white.svg"
                    alt="vue mastery logo"
                    class="bg-slate-800"
                />
            </a>
            <a href="https://vuejs.org/support-vuejs/" class="font-bold mt-5">Sponsor Vue.js Development</a>
        </div>
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
