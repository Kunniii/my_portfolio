<script setup>
import { ref } from "vue";
import ProjectCard from "../components/ProjectCard.vue";

const projects = ref([]);

fetch("https://raw.githubusercontent.com/Kunniii/my_cv/data/projects.json")
  .then((data) => data.json())
  .then((data) => {
    projects.value = data;
    console.log(projects.value);
  })
  .catch((e) => {
    console.log(e);
  });
</script>

<template>
  <div class="projects-container">
    <ProjectCard
      v-if="projects"
      v-for="project in projects"
      :key="project.name"
      :image="project.img"
      :title="project.name"
      :url="project.url"
    ></ProjectCard>
  </div>
</template>
