<template>
    <div class="px-16 border">
        <div class="relative flex items-center justify-between h-16 px-8">
            <div class="flex-shrink-0 flex items-center">
                <p class="px-3 py-2 rounded-md text-lg font-bold">Zane Wilgruber</p>
                <h1>
                    
                </h1>
            </div>
            <div class="hidden sm:block sm:ml-6">
                <div class="flex space-x-4 float-right">
                    <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
                    <a href="#" class="bg-gray-900 text-white px-3 py-2 rounded-md text-sm font-medium"
                        aria-current="page">Dashboard</a>

                    <a href="#"
                        class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Team</a>

                    <a href="#"
                        class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Projects</a>

                    <a href="#"
                        class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Calendar</a>

                    <a href="https://github.com/ZaneWillgruber"
                        class="text-gray-500 hover:text-black rounded-md text-2xl font-bold m-auto"><font-awesome-icon class="py-1" :icon="['fa-brands', 'fa-github']" /></a>
                    
                    <a href="https://authenticchops.itch.io/"
                        class="text-gray-500 hover:text-black rounded-md text-2xl font-bold m-auto"><font-awesome-icon class="py-1" :icon="['fa-brands', 'fa-itch-io']" /></a>

                    <a href="https://twitter.com/zanetwill"
                        class="text-gray-500 hover:text-black rounded-md text-2xl font-bold m-auto"><font-awesome-icon class="py-1" :icon="['fa-brands', 'fa-twitter']" /></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>
</style>