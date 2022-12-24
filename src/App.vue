<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="h-screen bg-gradient-to-r from-cyan-500 to-blue-500">
    <header>
      <nav class="flex sm:justify-center space-x-4">
        <RouterLink to="/" class="text-white text-lg">Home</RouterLink>
        <RouterLink to="/login" class="text-white text-lg">Login</RouterLink>
      </nav>
    </header>

    <RouterView />
  </div>
</template>
