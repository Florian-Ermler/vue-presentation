<template>
    <point-of-interest id="vueOrigin">
        <h1 class="text-center font-bold underline">Conclusion</h1>
        <div>
            <div id="drawbacks">
                <p class="font-bold mt-10">Problems/annoyances of plain HTML and JS</p>
                <p class="mt-5">
                    <span class="font-bold">HTML</span> files, even with outsourced Javascript files are getting bloated
                    over time and it's really annoying to maintian them which is why nearly no one does it.
                </p>
                <p class="mt-5">and</p>
                <p class="mt-5">
                    <span class="font-bold">JavaScript</span> requires a lot of effort to make it maintainable (that's
                    why Vue 3 was build with TypeScipt) and many implementaions are just laborious to use as an aspiring
                    or even senior developer.
                </p>
                <p class="text-center mt-5 font-bold">
                    <a href="https://github.com/Florian-Ermler/vue-presentation">
                        This is where Vue comes into play and rescues your web development career!
                    </a>
                </p>
            </div>
            <div id="solution"></div>
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
