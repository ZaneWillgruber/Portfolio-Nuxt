<template>
    <div class="grid grid-cols-2 gap-4 sticky top-0">
        <div class="grid-cols-1 grid-rows-3 grid-flow-row-dense sticky">
            <p class="p-6 text-secondary text-2xl font-bold">01</p>
            <div class="flex items-stretch row-span-2">
                <div class="self-start p-16">
                    <h1 class="text-primary font-bold text-7xl">Title</h1>
                    <p class="text-secondary text-2xl">description</p>
                </div>
            </div>
            <div class="self-end">
                <p>type</p>
            </div>

        </div>
    </div>
</template>

<script>
import Rellax from 'rellax';

export default {
    name: 'ProjectDetails',
    mounted() {
        const rellax = new Rellax(".rellax", {
            center: true
        })
        return rellax
    }
}
</script>