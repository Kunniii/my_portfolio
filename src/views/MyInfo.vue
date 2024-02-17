<script setup></script>

<template>
  <h2 class="text-center font-bold text-5xl pt-5 pb-3">HELLO!</h2>
  <hr class="pb-3 w-96 mx-auto" />

  <div class="py-5 flex flex-col md:flex-row gap-10 mx-auto">
    <div>
      <img
        src="/img/me_square.jpg"
        alt="My Image"
        class="w-64 rounded-2xl shadow-md"
      />
    </div>
    <div class="flex flex-col justify-between">
      <div>
        <p>My name is</p>
        <h2 class="my-2 font-bold text-2xl">Nguyen Phi Truong</h2>
        <p class="my-2 w-60 text-justify">
          A full-stack developer, Cyber security, and on my way to be a DevOps.
        </p>
        <p class="my-4 underline">
          <a href="mailto:truongnphi@codechovui.dev">truongnphi@codechovui.dev</a>
        </p>
      </div>
      <div>
        <a href="#contact"
          ><button
            class="hover:bg-black hover:text-white text-xl duration-200 font-bold button text-black hover:scale-105 border-2 border-black bg-white w-full"
          >
            Connect with Me!
          </button>
        </a>
      </div>
    </div>
  </div>

  <div class="mx-auto">
    <p class="text-center text-sm">or</p>
    <p class="text-center my-2">Find me on social media</p>
    <a
      href="https://www.linkedin.com/in/phi-tr%C6%B0%E1%BB%9Dng-nguy%E1%BB%85n-351928215/"
      target="_blank"
      class="font-mono hover:underline"
    >
      linkedin
    </a>
    <a>|</a>
    <a
      href="https://fb.com/Nguyen.PhiTruong.5801"
      target="_blank"
      class="font-mono hover:underline"
    >
      facebook
    </a>
    <a>|</a>
    <a
      href="https://x.com/ng_phi_truong"
      target="_blank"
      class="font-mono hover:underline"
    >
      X (twitter)
    </a>
  </div>
</template>
