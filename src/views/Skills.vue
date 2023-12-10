<script setup>
import SkillCard from "../components/SkillCard.vue";
</script>
<template>
  <h2 class="text-center font-bold text-5xl pt-5 pb-10">Skills</h2>
  <hr class="pb-10 w-96 mx-auto" />

  <h3 class="text-center font-bold text-3xl py-10">Programming Languages</h3>
  <div class="skills-container">
    <SkillCard :name="'python'"></SkillCard>
    <SkillCard :name="'js'"></SkillCard>
    <SkillCard :name="'go'"></SkillCard>
    <SkillCard :name="'html'"></SkillCard>
    <SkillCard :name="'css'"></SkillCard>
  </div>

  <h3 class="text-center font-bold text-3xl py-10">Tools</h3>
  <div class="skills-container">
    <SkillCard :name="'linux'"></SkillCard>
    <SkillCard :name="'docker'"></SkillCard>
    <SkillCard :name="'git'"></SkillCard>
    <SkillCard :name="'bun'"></SkillCard>
    <SkillCard :name="'gh-action'"></SkillCard>
    <SkillCard :name="'node'"></SkillCard>
    <SkillCard :name="'mysql'"></SkillCard>
    <SkillCard :name="'postgresql'"></SkillCard>
    <SkillCard :name="'mongodb'"></SkillCard>
    <SkillCard :name="'elasticsearch'"></SkillCard>
  </div>

  <h3 class="text-center font-bold text-3xl py-10">Frameworks</h3>
  <div class="skills-container">
    <SkillCard :name="'react'"></SkillCard>
    <SkillCard :name="'vue'"></SkillCard>
    <SkillCard :name="'tailwind'"></SkillCard>
    <SkillCard :name="'vite'"></SkillCard>
    <SkillCard :name="'flask'"></SkillCard>
    <SkillCard :name="'django'"></SkillCard>
    <SkillCard :name="'fast_api'"></SkillCard>
    <SkillCard :name="'gin'"></SkillCard>
  </div>
</template>
