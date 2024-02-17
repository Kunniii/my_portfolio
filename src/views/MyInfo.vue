<script setup></script>

<template>
  <h2 class="text-center font-bold text-5xl pt-5 pb-3">HELLO!</h2>
  <hr class="pb-3 w-96 mx-auto" />
  <h3 class="text-center text-xl">My name is</h3>

  <div class="py-5 grid grid-cols-2 gap-5 mx-auto">
    <div>
      <img
        src="/img/me_square.jpg"
        alt="My Image"
        class="w-64 rounded-2xl shadow-md"
      />
    </div>
    <div class="pt-5 flex flex-col justify-between">
      <div>
        <p class="my-2 font-bold text-2xl">Nguyen Phi Truong</p>
        <p class="my-2 w-60 text-justify">
          A full-stack developer, Cyber security, and on my way to be a DevOps.
        </p>
        <p class="my-4 underline">
          <a href="mailto:truongnphi@codechovui.dev">truongnphi@codechovui.dev</a>
        </p>
      </div>
      <div>
        <a href="#footer"
          ><button
            class="bg-blue-500 hover:bg-blue-600 text-white text-xl font-bold button hover-scale-105 w-full"
          >
            Connect with Me!
          </button>
        </a>
      </div>
    </div>
  </div>
</template>
