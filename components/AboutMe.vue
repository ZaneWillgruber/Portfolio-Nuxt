<template>
    <div class="grid content-center h-screen ">
            <p class="m-auto text-secondary text-4xl">College student who loves learning and trying new things.</p>
            <p class="m-auto text-secondary text-4xl">Front-end development is my current interest.</p>
    </div>
</template>

<script>
import Rellax from 'rellax';

export default {
    name: 'AboutMe',
    mounted() {
        const rellax = new Rellax(".rellax", {
            center: true
        })
        return rellax
    }
}
</script>