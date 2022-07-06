<template>
    <div class="grid grid-cols-2 gap-4 h-screen ">
        <div class="w-6/12">

        </div>
        <div class="flex m-auto overflow-hidden">
            <div class="rounded-xl shrink bg-gradient-to-r from-gray-900 to-gray-700 w-full m-2">
                <div class="flex flex-col justify-between h-full p-4">
                    <img class="rounded-lg m-auto" src="~/assets/images/PHS_Splash.png" />
                </div>
            </div>
            <div class="rounded-xl shrink bg-gradient-to-r from-gray-900 to-gray-700 w-full m-2">
                <div class="flex flex-col justify-between h-full p-4">
                    <img class="rounded-lg m-auto" src="~/assets/images/PHS_Splash.png" />
                </div>
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