<template>
    <MenuItem v-slot="{ active }">
        <a href="#" class="block px-4 py-2 text-sm text-gray-700 relative" >
            Upload Files

            <input type="file" class="absolute left-0 top-0 bottom-0 right-0 cursor-pointer opacity-0" >

        </a>
    </MenuItem>
</template>

<script setup>
// Imports
import {MenuItem} from '@headlessui/vue'
</script>

<style scoped>

</style>
