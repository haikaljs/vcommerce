<template>
    <div
        class="min-h-full flex items-center justify-center py-12 px-4 sm:px-6 lg:px-8"
    >
        <div class="mx-w-md w-full space-y-8">
            <div>
                <h2
                    class="mt-6 text-center text-3xl font-entrabold text-gray-900"
                >
                    {{ title }}
                </h2>
            </div>

            <router-view></router-view>
        </div>
    </div>
</template>

<script setup>
const { title } = defineProps({
    title: String,
});
</script>
