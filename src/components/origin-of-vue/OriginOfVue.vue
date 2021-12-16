<template>
    <point-of-interest id="vueOrigin">
        <h1 class="text-center font-bold underline">Origin of Vue</h1>
        <div class="flex flex-row mt-10">
            <img
                src="https://cdn-media-1.freecodecamp.org/images/0*xkJgg-6HskYrQ3N7.jpeg"
                alt="evan you profile"
                class="object-contain w-1/3"
            />
            <div class="ml-5">
                <p>Name: Evan You</p>
                <p class="mt-5">
                    former Google developer where he worked with AngularJS on a number of porjects. After some time he
                    thought to himself:
                </p>
                <p class="italic mt-5">
                    "What if I could just extract the part that I really liked about Angular and build something really
                    lightweight."
                </p>
                <p class="mt-5">-> first source code commit to the project was dated in July 2013</p>
                <p>--> the project was then released in February 2014 with version 0.9 Animatrix</p>
            </div>
        </div>
    </point-of-interest>
    <point-of-interest id="whatIsFramework">
        <div class="flex flex-col mt-10 justify-center items-center">
            <img
                src="https://mlwzfwt7aajx.i.optimole.com/ehEQlfA-ucW_wjTd/w:800/h:450/q:75/https://www.techtually.com/wp-content/uploads/2020/04/What-is-framework-in-programming-language.jpg"
                alt="what is a framework"
                class="object-contain w-2/3"
            />
            <div class="ml-5">
                <p class="text-center mt-10 underline font-bold">Frameworks vs. Programming Languages</p>
                <p class="mt-5">Programming Languages are <span class="font-bold">USED</span> to create Frameworks</p>
                <p>
                    Frameworks are targeted to help solve specific usecases and help developers working faster and more
                    efficient
                </p>
                <p class="mt-5">as an example:</p>
                <p>C# -> ASP.NET MVC -> Wep Apps</p>
                <p></p>
                <p class="text-center mt-10 underline font-bold">Frameworks vs. Libraries</p>
                <p class="italic mt-5">"Your code calls the library, but the framework calls your code"</p>
                <p>or to put it in other words:</p>
                <p>a Framework acts as your foundation and a library solves specific problems</p>
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
});
</script>
