<template>
    <point-of-interest id="basicJs">
        <h1 class="text-center font-bold underline">Basics:</h1>
        <div class="flex flex-col mt-10 justify-center items-center">
            <img
                src="https://upload.wikimedia.org/wikipedia/commons/d/d4/Javascript-shield.svg"
                alt="html logo"
                class="object-contain w-56"
            />
            <div>Hi</div>
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
    props: {},
    setup(props) {
        return {};
    },
});
</script>
