<template>
    <!-- Main section start -->
    <section class="h-screen px-12 lg:px-32 py-32 mb-8">
        <div class="w-full md:w-1/2 h-full flex flex-col md:justify-center">
            <!-- Main text start -->
            <h1 class="text-3xl sm:text-4xl md:text-5xl xl:text-7xl mb-4 font-semibold">
                Imagine une nouvelle façon d'imaginer
            </h1>
            <!-- Main text end -->
            <!-- Image container start -->
            <div class="absolute bottom-0 right-0 overflow-hidden h-3/4 sm:h-4/5 md:h-5/6 lg:h-3/4 -z-50">
                <img src="@/assets/image.jpg" alt="img" class="object-cover w-full h-full sm:w-3/4 sm:h-3/4 md:w-5/6 md:h-5/6 lg:w-full lg:h-full">
            </div>
            <!-- Image container end -->
        </div>
    </section>
    <!-- Main section end -->
</template>

<script>
export default {

}
</script>

<style scoped>
/* Add custom media queries for finer control */
@media (max-width: 640px) { 
    .object-cover {
        width: 90%; /* Makes image 80% of its original size on small screens */
        height: auto; /* Ensures the image aspect ratio remains intact */
        margin-top: 25%; /* Adds a little space on top to move the image lower */
    }
}
</style>
