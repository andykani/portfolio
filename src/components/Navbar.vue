<script setup lang="ts">
import { reactive } from 'vue';

    const state = reactive({

    })
</script>

<template>

    <nav class="navigation">
        <div class="navigation-title">
            <router-link to="/">AK</router-link>
        </div>
        <div class="navigation-links">
            <router-link to="/projects">Réalisations</router-link>
            <router-link to="/contact">Me contacter</router-link>
        </div>
    </nav>

      
  
</template>

<style scoped>
    .navigation{
        display: grid;
        justify-content: center;
        padding: 1rem .5rem;
        grid-template-columns:  1fr 1fr;
    }

    .navigation-links{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        font-size: .75rem;
    }
</style>