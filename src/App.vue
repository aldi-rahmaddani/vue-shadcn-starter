<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav class="px-4 py-6 flex items-center gap-x-4">
      <RouterLink class="text-green-500 hover:underline" to="/">Home</RouterLink>
      <RouterLink class="text-green-500 hover:underline" to="/about">About</RouterLink>
    </nav>
  </header>
  <div class="px-4 py-10">
    <RouterView />
  </div>
</template>
