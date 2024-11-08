<template>
  <section id="about-section" class="px-12 lg:px-32 py-16 relative text-center">
    <div class="absolute inset-x-0 top-0 h-1 bg-gradient-to-r from-pink-500 via-cyan-500 to-violet-500"></div>

    <div class="relative">
      <div class="flex justify-center items-center relative group" @click="showModal = true">
        <img src="@/assets/tv.jpg" alt="tv image" class="w-full max-w-4xl h-auto">
        
        <!-- Play button overlay, appears on hover -->
        <img src="@/assets/play.png" alt="play button" class="play-button absolute opacity-0 group-hover:opacity-100 transition-opacity duration-300">
      </div>

      <div v-if="showModal" class="fixed inset-0 z-50 flex items-center justify-center bg-black bg-opacity-75">
        <div class="relative bg-white rounded-lg shadow-lg p-4 w-11/12 max-w-3xl">
          <button @click="showModal = false" class="absolute top-0 right-1 text-gray-500 hover:text-gray-700 text-xl">
            &times;
          </button>
          <div class="video relative pb-9/16 h-0 overflow-hidden max-w-full">
            <iframe 
              width="100%" 
              height="100%" 
              class="absolute top-0 left-0 w-full h-full"
              src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
              title="YouTube video player" 
              frameborder="0" 
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
              allowfullscreen>
            </iframe>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      showModal: false,
    };
  },
};
</script>

<style scoped>
.video {
  padding-bottom: 56.25%;
}

.play-button {
  width: 100px;
  height: 100px;
  cursor: pointer;
  transform: translate(-74px, 55px); /* Default position for desktop */
}

.group:hover .play-button {
  opacity: 1;
}

@media (max-width: 640px) { /* Adjust for smaller screens */
  .play-button {
    transform: translate(-35%, 20px); /* Center and adjust position for mobile */
  }
}

@media (max-width: 450px) { /* Adjust for smaller screens */
  .play-button {
    transform: translate(-25%, 15px); /* Center and adjust position for mobile */
  }
}
</style>

