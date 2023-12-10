<script setup>
const props = defineProps({
  image: {
    type: String,
    required: true,
  },
  title: {
    type: String,
    required: true,
  },
  url: {
    type: String,
    required: true,
  },
  description: {
    type: String,
    required: true,
  },
  tech: {
    type: Array,
    required: true,
  },
});

function getImage(skillName) {
  return "/skills/" + skillName + ".png";
}
</script>
<template>
  <div class="project-card overflow-hidden">
    <a :href="props.url">
      <img
        :src="props.image"
        class="w-64 h-48 object-cover"
      />
      <div class="p-2">
        <h1 class="font-bold text-lg">{{ props.title }}</h1>
        <p>{{ props.description }}</p>
      </div>
      <div class="px-2 grid grid-cols-5 gap-2">
        <img
          v-for="name in props.tech"
          :src="getImage(name.toLowerCase())"
          class=""
          :alt="name"
          :title="name"
        />
      </div>
    </a>
  </div>
</template>
