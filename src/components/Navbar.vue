<script setup>
import { RouterLink, useRoute } from "vue-router";

const isActiveLink = (routePath) => {
  const route = useRoute();
  return route.path === routePath;
};
</script>

<template>
  <header class="bg-[#212b37] text-white py-6">
    <div class="container mx-auto flex items-center justify-between">
      <!-- Logo Section -->
      <div class="flex items-center space-x-2">
        <img src="https://via.placeholder.com/40" alt="Logo" class="h-10" />
        <a href="#" class="text-2xl font-bold text-[#F18C2D]">Mëkan Store</a>
      </div>

      <!-- Navigation Links -->
      <nav class="flex items-center space-x-6">
        <ul class="flex space-x-6">
          <li>
            <a
              href="#home"
              class="text-lg hover:text-[#F18C2D] transition duration-300"
              >Accueil</a
            >
          </li>
          <li>
            <a
              href="#products"
              class="text-lg hover:text-[#F18C2D] transition duration-300"
              >Nos Produits</a
            >
          </li>
          <li>
            <a
              href="#services"
              class="text-lg hover:text-[#F18C2D] transition duration-300"
              >Services</a
            >
          </li>
          <li>
            <a
              href="#about"
              class="text-lg hover:text-[#F18C2D] transition duration-300"
              >À propos</a
            >
          </li>
          <li>
            <a
              href="#contact"
              class="text-lg hover:text-[#F18C2D] transition duration-300"
              >Contact</a
            >
          </li>
        </ul>

        <!-- Login and Sign Up Buttons -->
        <div class="ml-6 flex items-center space-x-4">
          <a
            href="#login"
            class="px-6 py-2 bg-[#F18C2D] text-white font-semibold rounded hover:bg-[#d17624] transition duration-300"
            >Login</a
          >
          <a
            href="#signup"
            class="px-6 py-2 border border-[#F18C2D] text-[#F18C2D] font-semibold rounded hover:bg-[#F18C2D] hover:text-white transition duration-300"
            >Sign Up</a
          >
        </div>
      </nav>
    </div>
  </header>
</template>
