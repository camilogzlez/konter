<template>
  <!-- Contact section start -->
  <section id="contact-section" class="relative flex justify-center items-center">
    <!-- Wrapping the entire section with the link -->
    <a href="https://forms.gle/YOUR_GOOGLE_FORM_LINK" target="_blank" rel="noopener noreferrer" class="block w-full h-full flex justify-center items-center">
      <div class="relative overflow-hidden">
        <!-- Image inside the link with hover effect -->
        <img src="@/assets/monster.png" alt="img" class="object-cover max-w-xs sm:max-w-sm md:max-w-md lg:max-w-lg transition-transform duration-300 ease-in-out hover:scale-105 hover:shadow-lg">
      </div>
    </a>
  </section>
  <!-- Contact section end -->
</template>

<script>
export default {}
</script>

<style scoped>
#contact-section {
  position: relative;
  height: 60vh; /* Default height for the section */
}

a img {
  pointer-events: none; /* Ensure the image doesn't block the link */
  transition: transform 0.3s ease-in-out;
}

/* Adjust styles for smaller screens */
@media (max-width: 900px) {
  #contact-section {
    height: 85vh; /* Adjusted height for smaller screens */
  }
}

@media (max-width: 480px) {
  #contact-section {
    height: 35vh; /* Adjusted height for smaller screens */
  }

  /* Ensure the image covers the area without shrinking too much */
  a img {
    object-fit: cover; /* Ensure image covers the area without distortion */
  }
}

a:hover img {
  transform: scale(1.05);
  box-shadow: 0 10px 15px rgba(0, 0, 0, 0.3);
}
</style>
