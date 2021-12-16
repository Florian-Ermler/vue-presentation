<template>
    <point-of-interest id="basicJs">
        <h1 class="text-center font-bold underline">Basics:</h1>
        <div class="flex flex-col mt-10 justify-center items-center">
            <img
                src="https://upload.wikimedia.org/wikipedia/commons/d/d4/Javascript-shield.svg"
                alt="html logo"
                class="object-contain w-56"
            />
            <div>
                <p class="mt-2">
                    <span class="font-bold">JS (JavaScript) </span>is mostly used for client-side rendering in the
                    frontend of web apps but not exclusively as it is also used as backend like node.js
                </p>
                <p class="mt-2">it's the most used programming/script language in the world</p>
                <p class="mt-2">and it is really easy to learn!</p>
                <div class="m-5 p-5 rounded shadow-2xl w-2/3 text-3xl bg-gray-900 text-white" id="bloatedFiles">
                    <p>function initiateGreeting(attentionLvl) {</p>
                    <p class="ml-4">if(attentionLvl >= 80) {</p>
                    <p class="ml-8">document.getElementById('greeting').style.display = "block";</p>
                    <p class="ml-4">}</p>
                    <p class="ml-4">else if(attentionLvl >= 40) {</p>
                    <p class="ml-8">const element = document.getElementById('greeting');</p>
                    <p class="ml-8">element.innerHtml = createGrimMessage();</p>
                    <p class="ml-8">element.style.display = "block"</p>
                    <p class="ml-4">}</p>
                    <p class="ml-4">else {</p>
                    <p class="ml-8">throwItem(pickupNearestItem(), getRandomTarget())</p>
                    <p class="ml-4">}</p>
                    <p>}</p>
                </div>
            </div>
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
