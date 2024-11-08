<template>
    <!-- Contact section start -->
    <section id="contact-section" class="px-12 lg:px-32 py-16 relative">
        <!-- Wrapping the entire section with the link -->
        <a href="https://forms.gle/YOUR_GOOGLE_FORM_LINK" target="_blank" rel="noopener noreferrer" class="block w-full h-full">
            <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 overflow-hidden h-full sm:h-[90%] md:h-[85%] lg:h-[100%] -z-50">
                <!-- Image inside the link with hover effect -->
                <img src="@/assets/monster.png" alt="img" class="object-cover w-full h-full transition-transform duration-300 ease-in-out hover:scale-105 hover:shadow-lg">
            </div>
        </a>
        <!-- Main text end -->
    </section>
    <!-- Contact section end -->
</template>

<script>
export default {

}
</script>

<style>
#contact-section {
  height: 50vh; /* Default height for the section */
}

@media (max-width: 768px) {
  #contact-section {
    height: 20vh; /* Adjusted for smaller screens */
  }
}
@media (max-width: 480px) {
  #contact-section {
    height: 10vh; /* Adjusted for smaller screens */
  }
}

a:hover img {
  transform: scale(1.05);
  box-shadow: 0 10px 15px rgba(0, 0, 0, 0.3);
}
</style>
