<script setup>

import 'boxicons'
</script>

<template>
  <main>
    <section>
      <div class="flex justify-between">
        <div class="pl-32 pt-32 lg:w-1/2">
          <h2 id="title-mk" class=" text-8xl">MAKE YOUR</h2>
          <h1 id="title-bd" class="py-10 text-9xl font-bold ">BODY SHAPE</h1>
          <p id="p-title" class="text-xl text-slate-200 w-4/6 mb-20">In regard to using gym work experience to help with my college course I was able to do soon.</p>
          <div>
            <button id="principal-btn" class="flex items-center bg-lime-500 px-12 py-6 text-xl text-black font-bold ">Get Started <span class="w-5"></span> <box-icon name='right-arrow-alt'></box-icon></button>
          </div>
        </div>
        <div id="bg-container w-1/2">
          <!-- <img class="h-1/2" src="../assets/img/person.png" alt="bg"> -->
        </div>
      </div>
    </section>
  </main>
</template>

<style>

@import url('https://fonts.googleapis.com/css2?family=Londrina+Sketch&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Sofia+Sans:wght@900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300&display=swap');

#title-mk {
  font-family: 'Londrina Sketch', cursive;
  color: #fff;
}

#title-bd {
  font-family: 'Sofia Sans', sans-serif;
  color: #fff;
}

#p-title {
  font-family: 'Nunito', sans-serif;
}

#principal-btn {

  clip-path: polygon(0 0, 100% 0, 100% 62%, 88% 100%, 0 100%);
}
</style>
