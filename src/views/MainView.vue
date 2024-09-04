<template>
    <div class="h-screen bg-slate-100 font-mono">
        <h1 class="text-blue-400 text-xl text-center p-4">RAMDOM IMAGES APP WITH VUE</h1>
        <div class="flex justify-around">
            <InputLayout />
            <ImagesLayout />
        </div>
    </div>

</template>

<script setup lang="ts">
import ImagesLayout from '@/components/Images/ImagesLayout.vue';
import InputLayout from '@/components/inputs/InputLayout.vue';

</script>