<template>
    <div class="min-h-full bg-gray-200 flex">
        <!-- Sidebar -->
        <Sidebar />
        <!-- Sidebar end -->
        <div class="flex-1">
            <TopHeader />
            <!-- Content -->
            <main class="p-6">
                <router-view></router-view>
            </main>
            <!-- Content -->
        </div>
    </div>
</template>

<script setup>
import Sidebar from "./Sidebar.vue";
import TopHeader from "./TopHeader.vue";

const { title } = defineProps({
    title: String,
});
</script>
