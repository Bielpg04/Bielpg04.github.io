<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
    <nav class="w-full fixed top-0 left-0 bg-black shadow-md z-50">
    <div class="max-w-7xl mx-auto px-4 py-3 flex items-center justify-between">
      <div class="text-xl font-bold">MySite</div>
      <ul class="flex space-x-6">
        <li><a href="#" class="text-gray-700 hover:text-blue-600">Home</a></li>
        <li><a href="#" class="text-gray-700 hover:text-blue-600">About</a></li>
        <li><a href="#" class="text-gray-700 hover:text-blue-600">Contact</a></li>
      </ul>
    </div>
     </nav>
</template>

<style scoped>
</style>
