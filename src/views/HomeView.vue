<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main class="flex md:flex-row flex-col-reverse">
    <!-- Left -->
    <div class="basis-full md:basis-4/5 h-100 bg-amber-400 flex flex-col gap-3">
      <div class="bg-violet-400 h-[10rem] mt-5 mx-3 rounded-2xl"></div>
      <div class="bg-violet-400 h-[10rem] mx-3 rounded-2xl"></div>
      <div class="bg-violet-400 h-[10rem] mx-3 rounded-2xl"></div>
      <div class="bg-violet-400 h-[10rem] mx-3 rounded-2xl"></div>
    </div>
    <!-- Right -->
    <div class="basis-full md:basis-1/5 h-100 bg-green-800 flex flex-col gap-3">
      <div class="bg-red-500 mt-5 mx-3 flex flex-col">
        <div class="flex w-full justify-center">
          <img src="https://placehold.co/100x100.png" class="rounded-full"  alt="profile photo"/>
        </div>
        <div class="flex w-full justify-between">
          <p>
            Profile Completion
          </p>
          <p>
            x% completed
          </p>
        </div>
        <div class="w-full text-center">
          <p>Full Name is available for hire.</p>
        </div>
        <div id="resume-completion" class="border-2 h-2">
          <div class="w-3/4 bg-blue-400 h-full"></div>
        </div>
      </div>
      <div class="bg-red-500 h-[10rem] mx-3"></div>
    </div>
  </main>
</template>