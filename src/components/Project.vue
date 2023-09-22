<template>
    <div class="bg-gray-800 rounded shadow-gray-600 shadow-md border-2 border-gray-600 hover:scale-105 transition-transform flex flex-col gap-2 p-4">
        <h3 class="text-xl font-bold">
            <slot name="head">

            </slot>
        </h3>
        <div class="text-sm">
            <slot name="body">

            </slot>
        </div>
        <div class="overflow-clip max-h-64">
            <slot name="image">

            </slot>
        </div>
    </div>
</template>