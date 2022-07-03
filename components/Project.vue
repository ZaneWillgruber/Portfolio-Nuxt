<template>
    <div class="grid grid-cols-2 gap-4 h-screen ">
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
        <div class="">
            <img class="rellax object-scale-down h-48 w-96" data-rellax-speed="4" data-rellax-percentage=".025" src="~/assets/images/PHS_Splash.png" />
            <img class="rellax object-scale-down h-48 w-96 ml-32" data-rellax-speed="10" src="~/assets/images/PHS_Splash.png" />
        </div>
    </div>
</template>

<script>
import Rellax from 'rellax';

export default {
    name: 'Project',
    mounted() {
        const rellax = new Rellax(".rellax", {
            center: true
        })
        return rellax
    }
}
</script>