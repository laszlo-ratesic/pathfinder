<template>
  <main class="px-4 py-10 text-center text-gray-700 dark:text-gray-200">
    <pixelarticons-list class="icon-btn mx-2 text-2xl" />
    <div>Create List</div>
    <p class="mt-2 opacity-50">
      Enter a list item
    </p>

    <input v-model="storageDemo" class="border border-gray-400 rounded px-2 py-1 mt-2" />

    <div class="mt-4">
      Created by laszlo-ratesic & DevJonTaylor <pixelarticons-zap class="align-middle" />
    </div>
  </main>
</template>

<script setup lang="ts">
import { storageDemo } from '~/logic/storage'
</script>
