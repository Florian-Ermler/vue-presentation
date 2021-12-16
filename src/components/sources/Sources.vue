<template>
    <point-of-interest id="sources">
        <h1 class="text-center">Sources</h1>
        <ul>
            <source-link :link="'https://vuejs.org/images/logo.svg'" :date="'02.05.2022'" />
            <source-link :link="'https://cdn-media-1.freecodecamp.org/images/0*xkJgg-6HskYrQ3N7.jpeg'" />
            <source-link
                :link="'https://mlwzfwt7aajx.i.optimole.com/ehEQlfA-ucW_wjTd/w:800/h:450/q:75/https://www.techtually.com/wp-content/uploads/2020/04/What-is-framework-in-programming-language.jpg'"
            />
            <source-link :link="'https://en.wikipedia.org/wiki/Vue.js'" />
            <source-link :link="'https://makemeaprogrammer.com/what-is-a-programming-framework/'" />
            <source-link :link="'https://cocosolution.com/en/what-is-a-framework/'" />
            <source-link :link="'https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg'" />
            <source-link :link="'https://upload.wikimedia.org/wikipedia/commons/d/d4/Javascript-shield.svg'" />
            <source-link
                :link="'https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics'"
            />
            <source-link :link="'https://www.w3schools.com/html/'" />
            <source-link :link="'https://en.wikipedia.org/wiki/World_Wide_Web_Consortium'" />
            <source-link :link="'https://vuejs.org/'" />
            <source-link :link="'https://jsonplaceholder.typicode.com/comments'" />
            <source-link :link="'https://developer.mozilla.org/de/docs/Web/JavaScript'" />
            <source-link :link="'https://www.w3schools.com/js/'" />
            <source-link :link="'https://www.javascript.com/'" />
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
    setup() {},
});
</script>
