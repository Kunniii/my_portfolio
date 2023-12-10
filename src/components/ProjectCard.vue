<script setup>
const props = defineProps({
  image,
  title,
  url,
  description,
});
</script>
<template>
  <div class="card overflow-hidden">
    <a :href="props.url">
      <img
        :src="props.image"
        class="w-64 h-48 object-cover"
      />
      <div class="p-2">
        <h1 class="font-bold text-lg">{{ props.title }}</h1>
      </div>
    </a>
  </div>
</template>
