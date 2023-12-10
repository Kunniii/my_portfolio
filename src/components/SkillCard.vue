<script setup>
const props = defineProps(["name", "level"]);

function getImage(skillName) {
  return "/skills/" + skillName + ".png";
}
</script>

<template>
  <div
    class="skill-card flex flex-col justify-center"
    :title="props.name.toUpperCase()"
  >
    <img
      :src="getImage(props.name)"
      class="object-fit"
      alt=""
    />
  </div>
</template>
