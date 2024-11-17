<script setup>
import { defineProps } from "vue";

defineProps({
  title: {
    type: String,
    default: "Become a Vue Dev",
  },
  subtitle: {
    type: String,
    default: "Find the Vue job that fits your skills and needs",
  },
});
</script>

<template>
<section class="bg-[#212b37] text-white min-h-screen flex items-center px-6 md:px-12">
  <div class="container mx-auto flex flex-col md:flex-row items-center justify-between">
    <!-- Text Section -->
    <div class="max-w-lg">
      <h1 class="text-4xl md:text-5xl font-bold leading-tight text-[#F18C2D]">
        Mëkan Store : Technologie de pointe et design créatif
      </h1>
      <p class="mt-4 text-lg text-[#d1d5db]">
        Découvrez nos ordinateurs, téléphones et services de design graphique pour propulser votre entreprise.
      </p>
      <button class="mt-6 px-6 py-3 bg-[#F18C2D] text-white font-semibold rounded hover:bg-[#d17624] transition duration-300">
        Explorez nos offres
      </button>
    </div>

    <!-- Image Section -->
    <div class="mt-8 md:mt-0 md:ml-12">
      <img
        src="https://via.placeholder.com/500x500"
        alt="Hero image"
        class="max-w-full rounded-md shadow-lg"
      />
    </div>
  </div>
</section>


</template>
