<template>
    <point-of-interest id="basicHtml">
        <h1 class="text-center font-bold underline">Basics:</h1>
        <div class="flex flex-col mt-10 justify-center items-center">
            <img
                src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg"
                alt="html logo"
                class="object-contain w-80"
            />
            <div>
                <p class="mt-2">
                    <span class="font-bold"> HTML (Hypertext Markup Language) </span> is the code that is used to
                    structure a web page and its content.
                </p>
                <p class="mt-2">
                    It's is <span class="font-bold">NOT</span> a programming language it's a markup language!
                </p>
                <p class="mt-2">
                    The <span class="font-bold"> W3C (World Wide Web Consortium) </span> founded in 1994, is the main
                    international standards organization for the World Wide Web
                </p>
                <p class="mt-2">
                    They are tasked to ensure the growth of the Web with their guidelines and also take part in
                    educating developers.
                </p>
                <div class="m-5 p-5 rounded shadow-2xl w-2/3 text-3xl bg-gray-900 text-white" id="bloatedFiles">
                    <p>&lt;!DOCTYPE html&gt;</p>
                    <p>&lt;html lang="en"&gt;</p>
                    <p class="ml-4">&lt;head&gt;</p>
                    <p class="ml-8">&lt;title&gt;</p>
                    <p class="ml-12">This is the websites title!</p>
                    <p class="ml-8">&lt;/title&gt;</p>
                    <p class="ml-8">&lt;meta charset="UTF-8" /&gt;</p>
                    <p class="ml-4">&lt;/head&gt;</p>
                    <p class="ml-4">&lt;body&gt;</p>
                    <div class="ml-8">
                        &lt;div&gt;
                        <p class="ml-12">&lt;p&gt;Hello E3FI&lt;p&gt;</p>
                        <p class="ml-12">&lt;p&gt;This is HTML!&lt;p&gt;</p>
                        <p class="ml-12">
                            &lt;p&gt;And this is how HTML will eventually look like without Vue or another modular
                            Framework: &lt;p&gt;
                        </p>
                        <p class="ml-12">
                            <a href="https://github.com/Florian-Ermler/vue-presentation/tree/main/src/bloated.html">
                                &lt;a
                                href="https://github.com/Florian-Ermler/vue-presentation/tree/main/src/bloated.html"&gt;
                                &lt;/a&gt;
                            </a>
                        </p>
                        &lt;div&gt;
                    </div>
                    <p class="ml-4">&lt;/body&gt;</p>
                    <p>&lt;html&gt;</p>
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
