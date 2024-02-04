<template>
  <header-nav-bar></header-nav-bar>
  <main class="w-[80%] m-auto">
    <slot />
  </main>
</template>
<script setup lang="ts"></script>
<style>
body {
  overflow-x: hidden;
}
</style>
