<template>
    <div class="min-h-screen flex flex-col sm:justify-center items-center pt-6 sm:pt-0 bg-gray-700">
        <div class="mt-28 mb-10 font-black">
            <inertia-link class="text-white text-4xl" href="/">
                SAUC E-Commerce
            </inertia-link>
        </div>

        <div class="lg:w-6/12 md:w-8/12 w-10/12 sm:max-w-md mt-6 px-6 py-4 bg-gray-900 rounded-lg shadow-lg overflow-hidden sm:rounded-lg">
            <slot />
        </div>
    </div>
</template>

<script>

    export default {
        components: {
        }
    }
</script>
