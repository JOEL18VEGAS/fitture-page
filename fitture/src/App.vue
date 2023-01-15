<script setup>
import Home from './components/Home.vue'
import 'boxicons'
</script>

<template>
  <header>
    <nav class="flex  justify-between px-32 py-10">
      <div style="@import url('https://fonts.googleapis.com/css2?family=Courgette&display=swap'); font-family: 'Courgette', cursive;" class="flex items-center">
        <img class="h-16" src="./assets/img/musclewhite.svg" alt="logo">
        <h4 class="text-2xl">Fitture</h4>
      </div>
      <div class="flex items-center pr-10">
        <ul style="@import url('https://fonts.googleapis.com/css2?family=Sofia+Sans:wght@200&display=swap'); font-family: 'Sofia Sans', sans-serif;" class="flex justify-center text-lg space-x-28">
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Pricing</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
          <button style="clip-path: polygon(0 0, 100% 0, 100% 62%, 85% 100%, 0 100%);" class="bg-white px-7 py-4  ml-20 text-black font-bold ">Register Now</button>
      </div>
    </nav>
  </header>
  <Home />
</template>

