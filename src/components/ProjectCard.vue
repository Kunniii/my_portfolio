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
    <a
      :href="props.url"
      target="_blank"
    >
      <img
        :src="props.image"
        class="w-96 h-48 object-cover"
      />
      <div class="p-2">
        <h1 class="font-bold text-lg">{{ props.title }}</h1>
        <p class="overflow-hidden h-24">
          {{ props.description }}
        </p>
      </div>
      <div class="px-4 grid grid-cols-8 gap-2">
        <img
          v-for="name in props.tech"
          :src="getImage(name.toLowerCase())"
          class="my-auto"
          :alt="name"
          :title="name"
        />
      </div>
    </a>
  </div>
</template>
