<template>
    <div class="grid grid-cols-2 gap-4 h-screen ">
        <div class="w-6/12">

        </div>
        <div class="flex m-auto overflow-hidden">
            <div class="absolute max-h-64 ">
                <img class="rounded-lg m-auto max-h-64 rellax" data-rellax-speed="4" data-rellax-percentage="0.5"
                    src="~/assets/images/PHS_Splash.png" />
            </div>
            <div class="">
                <img class="rounded-lg m-auto" src="~/assets/images/PHS_Splash.png" />
            </div>
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