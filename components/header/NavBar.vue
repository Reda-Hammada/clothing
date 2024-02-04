<script setup lang="ts"></script>
<template>
  <header class="w-[80%] m-auto h-[100px] mb-32">
    <nav class="flex justify-center">
      <div class="w-[100%] -mt-16">
        <NuxtImg class="w-[240px] h-[240px]" src="/images/clothing-logo.png" />
      </div>
      <div class="mr-32">
        <ul class="text-[18px] flex mt-6">
          <li class="mr-12 cursor-pointer">Home</li>
          <li class="mr-12 cursor-pointer">Collections</li>
          <li class="mr-12 cursor-pointer">About</li>
          <li class="mr-12 cursor-pointer">Contact</li>
        </ul>
      </div>
      <div>
        <ul class="text-[18px] flex mt-6">
          <li class="mr-12 cursor-pointer">
            <Icon name="mdi:cards-heart-outline" />
          </li>
          <li class="mr-12 cursor-pointer">
            <Icon name="solar:bag-4-outline" />
          </li>
          <li class="mr-12 cursor-pointer">
            <Icon name="simple-line-icons:magnifier" />
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>
