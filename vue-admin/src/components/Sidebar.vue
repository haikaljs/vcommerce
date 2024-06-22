<template>
    <div class="w-[200px] bg-indigo-700 text-white py-4 px-2">
        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center transition-colors hover:bg-black/30 p-2 rounded"
        >
            <span class="mr-2">
                <HomeIcon class="w-5" />
            </span>
            <span class="text-sm">Dashboard</span>
        </router-link>
        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center transition-colors hover:bg-black/30 p-2 rounded"
        >
            <span class="mr-2">
                <TvIcon class="w-5" />
            </span>
            <span class="text-sm">Products</span>
        </router-link>
        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center transition-colors hover:bg-black/30 p-2 rounded"
        >
            <span class="mr-2">
                <UsersIcon class="w-5" />
            </span>
            <span class="text-sm">Users</span>
        </router-link>
        <router-link
            :to="{ name: 'app.dashboard' }"
            class="flex items-center transition-colors hover:bg-black/30 p-2 rounded"
        >
            <span class="mr-2">
                <ChartBarIcon class="w-5" />
            </span>
            <span class="text-sm">Reports</span>
        </router-link>
    </div>
</template>

<script setup>
import {
    HomeIcon,
    TvIcon,
    UsersIcon,
    ChartBarIcon,
} from "@heroicons/vue/24/outline";
</script>

<style scoped></style>
