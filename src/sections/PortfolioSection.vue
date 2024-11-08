<template>
  <!-- Specialites section start -->
  <section id="portfolio-section" class="px-4 lg:px-8 py-16 relative">
    <!-- Specialites Section -->
    <div class="mb-8">
      <!-- Title for Specialites -->
      <div class="relative mb-4 md:w-1/3">
        <div class="absolute inset-0 rounded-lg -translate-x-1 translate-y-1 bg-gradient-to-br from-pink-500 via-cyan-500 to-violet-500" style="height: 62px;"></div>
        <div class="relative bg-black rounded-lg p-4">
          <p class="ml-2 text-xl font-comic-sans text-white">SPÉCIALITÉS</p>
        </div>
      </div>

      <!-- Grid for Specialites -->
      <div class="flex justify-start">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
          <!-- Box 1 -->
          <div class="flex items-center justify-center w-40 h-40  bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
            <p class="text-xl font-semibold">IA</p>
          </div>
          <!-- Box 2 -->
          <div class="flex items-center justify-center w-40 h-40  bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
            <p class="text-xl font-semibold">DATA</p>
          </div>
          <!-- Box 3 -->
          <div class="flex items-center justify-center w-40 h-40  bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
            <p class="text-xl font-semibold">CLOUD</p>
          </div>
          <!-- Box 4 -->
          <div class="flex items-center justify-center w-40 h-40  bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
            <p class="text-xl font-semibold">DEVOPS</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Impact Section -->
    <div class="mb-8">
      <!-- Title for Impact -->
      <div class="relative mb-4 md:w-1/3 text-left ml-auto">
        <div class="absolute inset-0 rounded-lg -translate-x-1 translate-y-1 bg-gradient-to-br from-pink-500 via-cyan-500 to-violet-500" style="height: 65px;"></div>
        <div class="relative bg-white border-2 border-black rounded-lg p-4">
          <p class="ml-2 text-xl font-comic-sans text-black">IMPACT</p>
        </div>
      </div>

      <!-- Grid for Impact -->
      <!-- Grid for Impact -->
<div class="flex justify-end">
  <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
    <!-- Box 1 (with smaller text) -->
    <div class="flex items-center justify-center w-40 h-40 bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
      <p class="text-xs font-semibold text-center">DEMOCRATISATION DE LA LITTÉRATURE</p> <!-- Smaller text -->
    </div>
    <!-- Box 2 -->
    <div class="flex items-center justify-center w-40 h-40 bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
      <p class="text-sm font-semibold text-center">DÉFICIENCES VISUELLES ET AUDITIVES</p>
    </div>
    <!-- Box 3 -->
    <div class="flex items-center justify-center w-40 h-40 bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
      <p class="text-sm font-semibold text-center">BARRIÈRES DE LANGUE</p>
    </div>
    <!-- Box 4 -->
    <div class="flex items-center justify-center w-40 h-40 bg-white text-black border border-black shadow-md shadow-gray-400 font-comic-sans">
      <p class="text-sm font-semibold text-center">ÉDUCATION</p>
    </div>
  </div>
</div>

    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Comic+Sans+MS&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Patrick+Hand&display=swap');

.font-comic-sans {
    font-family: 'Comic Sans MS', 'Comic Sans', cursive, 'Patrick Hand', sans-serif;
}
</style>
