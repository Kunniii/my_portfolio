<script setup>
import SkillCard from "../components/SkillCard.vue";
</script>
<template>
  <div class="skills-container">
    <SkillCard :name="'tailwind'"></SkillCard>
    <SkillCard :name="'bun'"></SkillCard>
    <SkillCard :name="'css'"></SkillCard>
    <SkillCard :name="'html'"></SkillCard>
    <SkillCard :name="'linux'"></SkillCard>
    <SkillCard :name="'docker'"></SkillCard>
    <SkillCard :name="'nginx'"></SkillCard>
  </div>
</template>
