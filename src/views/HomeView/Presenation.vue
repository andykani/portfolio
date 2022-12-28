<script lang="ts" setup >
import {skills} from "../../utils/data"
import Skill from "./Skill.vue"
 
</script>

<template>
    <div class="presentation">
        <span>Bonjour, je suis</span>
        <span>Andy Kani</span>
        <span>Développeur Web PHP FullStack</span>
    </div>

    <div class="skills">
        <div class="skills-header">
            <h5>Mes compétences</h5>
            <h3>Services</h3>
        </div>
        <div class="skills-container px-2 grid grid-cols-1 gap-y-2">

            <Skill v-for="(skill, index) in skills" :key="index" :item="skill"/>
        </div>

    </div>
</template>