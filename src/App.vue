<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Navbar from "./components/Navbar.vue"
import "./assets/main.css"
</script>

<template>
  <header>
      <Navbar />
  </header>

  <RouterView />
</template>

<style>
</style>
