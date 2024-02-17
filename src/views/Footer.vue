<script setup></script>

<template>
  <footer class="bg-black text-white p-4">
    <div class="container mx-auto lg:w-2/5 md:w-3/4 sm:w-full">
      <div class="grid grid-cols-2 gap-20">
        <div class="text-right">
          <h3 class="font-bold text-xl mb-2">Company</h3>
          <ul>
            <li><a href="#info">About Me</a></li>
            <li><a href="#contact">Contact Me</a></li>
          </ul>
        </div>
        <div>
          <h3 class="font-bold text-xl mb-2">Resources</h3>
          <ul>
            <li>
              <a
                href="//codechovui.dev"
                target="_blank"
                >Blog</a
              >
            </li>
            <li><a href="mailto:truongnp@codechovui.dev">Support</a></li>
          </ul>
        </div>
      </div>
      <div class="pt-4 mt-4">
        <p class="text-center">
          Copyright &copy; {{ new Date().getFullYear() }} Nguyen Phi Truong. All rights reserved.
        </p>
      </div>
    </div>
  </footer>
</template>
