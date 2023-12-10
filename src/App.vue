<script setup>
import NavBar from "./components/NavBar.vue";
import MyInfo from "./views/MyInfo.vue";
import Projects from "./views/Projects.vue";
import Skills from "./views/Skills.vue";
</script>

<template>
  <NavBar></NavBar>
  <div class="flex flex-col mt-12">
    <span id="info"></span>
    <MyInfo></MyInfo>
    <span id="projects"></span>
    <Projects></Projects>
    <span id="skills"></span>
    <Skills></Skills>
  </div>
</template>
