<template>
    <div class="grid grid-cols-2 gap-4 h-screen ">
        <div class="w-6/12">

        </div>
        <div class="flex m-auto overflow-hidden min-w-full">
            <div class="absolute max-h-64 right-0">
                <img class="rounded-lg m-auto max-h-64 rellax border-4 border-black top-0" data-rellax-speed="4" data-rellax-percentage="0.5"
                    src="~/assets/images/PHS_Game.png" />
            </div>
            <div class="absolute max-h-64">
                <img class="rounded-lg m-auto max-h-64 rellax border-4 border-black" data-rellax-speed="6" data-rellax-percentage="0.5"
                    src="~/assets/images/PHS_Game.png" />
            </div>
            <div class="absolute max-h-64 right-64">
                <img class="rounded-lg m-auto max-h-64 rellax border-4 border-black top-4" data-rellax-speed="8" data-rellax-percentage="0.5"
                    src="~/assets/images/PHS_Splash.png" />
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