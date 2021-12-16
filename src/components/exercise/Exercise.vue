<template>
    <point-of-interest id="exercise">
        <h1 class="text-center font-bold underline mb-10">Exercise</h1>
        <p
            class="codepen"
            data-height="600"
            data-default-tab="html,result"
            data-slug-hash="RwLVNzm"
            data-editable="true"
            data-user="florian-ermler"
            style="
                height: 600px;
                box-sizing: border-box;
                display: flex;
                align-items: center;
                justify-content: center;
                border: 2px solid;
                margin: 1em 0;
                padding: 1em;
            "
        >
            <span
                >See the Pen <a href="https://codepen.io/florian-ermler/pen/RwLVNzm"> Vue.js: Reactivity Quiz</a> by
                Florian-Ermler (<a href="https://codepen.io/florian-ermler">@florian-ermler</a>) on
                <a href="https://codepen.io">CodePen</a>.</span
            >
        </p>
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
