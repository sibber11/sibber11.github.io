<script setup>
import vueSvg from '../assets/vue.svg';
</script>
<template>
    <section class="scroll-mt-32 snap-center flex flex-col bg-gray-900 p-8 gap-4 h-screen">
        <h2 class="text-5xl uppercase text-white">Technologies</h2>
        <div class="flex gap-4">
            <article class="w-1/2">
                <h3 class="text-3xl py-4 text-white">Frontend</h3>
                <ul class="grid lg:grid-cols-4 sm:grid-cols-2 gap-4 py-4 text-xl text-white font-semibold">
                    <li
                        class="p-4 rounded shadow flex flex-col justify-between gap-2 items-center">
                        <img src="../assets/html-5.png" alt="">
                        <div>
                            HTML
                        </div>
                    </li>
                    <li
                        class="p-4 rounded shadow flex flex-col justify-between gap-2 items-center">
                        <img src="../assets/css-3.png" alt="">
                        <div>
                            CSS
                        </div>
                    </li>
                    <li
                        class="p-4 rounded shadow flex flex-col justify-between gap-2 items-center">
                        <img src="../assets/js.png" alt="">
                        <div>
                            JavaScript
                        </div>
                    </li>
                    <li
                        class="p-4 rounded shadow flex flex-col justify-between gap-2 items-center">
                        <img src="../assets/vue.svg" class="w-full" alt="">
                        <div>
                            Vue
                        </div>
                    </li>
                    <li
                        class="p-4 rounded shadow flex flex-col justify-between gap-2 items-center">
                        <svg viewBox="0 0 50 31" class="text-slate-900 dark:text-white w-full">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M25.517 0C18.712 0 14.46 3.382 12.758 10.146c2.552-3.382 5.529-4.65 8.931-3.805 1.941.482 3.329 1.882 4.864 3.432 2.502 2.524 5.398 5.445 11.722 5.445 6.804 0 11.057-3.382 12.758-10.145-2.551 3.382-5.528 4.65-8.93 3.804-1.942-.482-3.33-1.882-4.865-3.431C34.736 2.92 31.841 0 25.517 0zM12.758 15.218C5.954 15.218 1.701 18.6 0 25.364c2.552-3.382 5.529-4.65 8.93-3.805 1.942.482 3.33 1.882 4.865 3.432 2.502 2.524 5.397 5.445 11.722 5.445 6.804 0 11.057-3.381 12.758-10.145-2.552 3.382-5.529 4.65-8.931 3.805-1.941-.483-3.329-1.883-4.864-3.432-2.502-2.524-5.398-5.446-11.722-5.446z"
                                fill="#38bdf8"></path>
                        </svg>
                        <div>
                            Tailwind
                        </div>
                    </li>
                </ul>
            </article>
            <article class="w-1/2">
                <h3 class="text-3xl py-4 text-white">Backend</h3>
                <ul class="grid lg:grid-cols-4 sm:grid-cols-2 gap-4 py-4 text-xl text-white font-semibold">
                    <li
                        class="p-4 rounded shadow flex flex-col justify-between gap-2 items-center">
                        <img src="../assets/php.png" alt="">
                        <div>
                            PHP
                        </div>
                </li>
                <li
                    class="p-4 rounded shadow flex flex-col justify-between gap-2 items-center">
                    <img src="../assets/laravel.svg" class="w-full" alt="">
                    <div>
                        Laravel
                    </div>
                </li>
            </ul>
        </article>
    </div>
</section></template>