<template>
  <!-- Footer start -->
  <div class="bg-black w-full flex justify-center items-center md:justify-evenly flex-col md:flex-row gap-8 p-8">
    <!-- Overview start -->
    <div class="text-stone-100 text-center">
      <p class="tracking-widest font-semibold text-stone-100">KONTER</p>
      <p class="tracking-widest font-light text-stone-100">EPITECH ESP PROJET, LE TEAM: </p>
      <div class="flex justify-center flex-wrap gap-8 mt-3"> <!-- Flex container for team members -->
        <div class="team-member">
          <a href="https://www.linkedin.com/in/camille-kerserho" target="_blank" class="flex items-center gap-2">
            <span class="name">Camille</span>
            <img src="@/assets/logo_linkedin_gray.png" alt="LinkedIn Camille" class="socialIcon w-8 h-8"/>
          </a>
        </div>
        <div class="team-member">
          <a href="https://www.linkedin.com/in/romain-ber" target="_blank" class="flex items-center gap-2">
            <span class="name">Romain</span>
            <img src="@/assets/logo_linkedin_gray.png" alt="LinkedIn Romain" class="socialIcon w-8 h-8"/>
          </a>
        </div>
        <div class="team-member">
          <a href="https://www.linkedin.com/in/camilogzlez" target="_blank" class="flex items-center gap-2">
            <span class="name">Camilo</span>
            <img src="@/assets/logo_linkedin_gray.png" alt="LinkedIn Camilo" class="socialIcon w-8 h-8"/>
          </a>
        </div>
      </div>
    </div>
    <!-- Overview end -->
  </div>
  <!-- Footer end -->
</template>

<script>
export default {
}
</script>

<style scoped>
/* Style for each team member */
.team-member {
    cursor: pointer;
}

/* Flex container for team members */
.flex-wrap {
    flex-wrap: wrap; /* Wrap items on smaller screens */
}

/* Hover effect for name and LinkedIn icon together */
.team-member a:hover .name,
.team-member a:hover .socialIcon {
    color: #1da1f2; /* Change color on hover */
    transform: scale(1.1); /* Slight scale-up effect */
    transition: all 0.3s ease; /* Smooth transition */
}

/* Centering the entire footer section */
footer {
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Make sure the items are responsive */
@media (max-width: 768px) {
    .team-member {
        flex-direction: column; /* Stack items vertically on smaller screens */
        align-items: center;
    }
}
</style>
