<template>
    <div class="grid grid-cols-2 gap-4 h-screen ">
        <div>

        </div>
        <div class="flex m-auto">
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