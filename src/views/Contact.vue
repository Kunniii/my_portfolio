<script setup>
import { ref } from "vue";
const name = ref("");
</script>

<template>
  <h2 class="text-center font-bold text-5xl pt-5 pb-10">Contact Me</h2>
  <hr class="pb-10 w-96 mx-auto" />
  <footer
    class="bg-white text-black mx-auto rounded-xl px-4 py-12 mb-10 shadow-lg w-[90%] lg:w-2/5 md:w-3/4"
  >
    <div class="flex flex-col gap-4">
      <h2 class="text-2xl font-bold">Get in touch!</h2>
      <form class="flex flex-col gap-4">
        <label
          for="name"
          class="text-sm"
          >Name</label
        >
        <input
          type="text"
          id="name"
          class="bg-gray-100 border border-gray-50 rounded-lg py-2 px-4"
        />
        <label
          for="message"
          class="text-sm"
          >Message</label
        >
        <textarea
          id="message"
          class="bg-gray-100 border border-gray-50 rounded-lg py-2 px-4"
        ></textarea>
        <button
          type="submit"
          class="bg-black hover:scale-[1.025] duration-300 text-white font-bold py-2 px-4 rounded-lg"
        >
          Send
        </button>
      </form>
    </div>
  </footer>
</template>
