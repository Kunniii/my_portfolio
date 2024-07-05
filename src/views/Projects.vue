<script setup>
  import { ref } from "vue";
  import ProjectCard from "../components/ProjectCard.vue";

  const projects = ref(null);

  fetch("https://raw.githubusercontent.com/Kunniii/my_portfolio/data/projects.json")
    .then((data) => data.json())
    .then((data) => (projects.value = data))
    .catch((e) => {
      console.log(e);
    });
</script>

<template v-if="projects">
  <h2 class="text-center font-bold text-5xl pt-5 pb-10">My Projects</h2>
  <hr class="pb-10 w-96 mx-auto" />
  <div class="projects-container">
    <ProjectCard
      v-for="project in projects"
      :key="project.name"
      :image="project.img"
      :title="project.name"
      :url="project.url"
      :description="project.description"
      :tech="project.tech"
    ></ProjectCard>
  </div>
</template>
