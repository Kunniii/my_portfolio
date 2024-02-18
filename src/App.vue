<script setup>
import NavBar from "./components/NavBar.vue";
import Contact from "./views/Contact.vue";
import Footer from "./views/Footer.vue";
import MyInfo from "./views/MyInfo.vue";
import Projects from "./views/Projects.vue";
import Skills from "./views/Skills.vue";
</script>
<template>
  <NavBar></NavBar>
  <div class="flex flex-col mt-12">
    <span id="info"></span>
    <MyInfo></MyInfo>
    <span id="skills"></span>
    <Skills></Skills>
    <span id="projects"></span>
    <Projects></Projects>
    <span id="contact"></span>
    <Contact></Contact>

    <Footer></Footer>
  </div>
</template>
