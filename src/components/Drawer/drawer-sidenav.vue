<script setup></script>

<template>
  <button
    x-show="!showSidenav"
    class="fixed top-8 left-8 bg-slate-800 text-slate-100 rounded-full p-4"
    @click="showSidenav = true"
  >
    <svg
      xmlns="http://www.w3.org/2000/svg"
      fill="none"
      viewBox="0 0 24 24"
      stroke-width="1.5"
      stroke="currentColor"
      class="w-6 h-6"
    >
      <path
        stroke-linecap="round"
        stroke-linejoin="round"
        d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
      />
    </svg>
  </button>
  <nav
    class="fixed z-10 h-screen bg-slate-800 w-72 text-slate-100 p-8"
    x-show="showSidenav"
    x-transition:enter="transition ease-out duration-300"
    x-transition:enter-start="-translate-x-72"
    x-transition:enter-end="translate-x-0"
    x-transition:leave="transition ease-in duration-300 "
    x-transition:leave-start="translate-x-0"
    x-transition:leave-end="-translate-x-72"
    x-cloak=""
  >
    <button @click="showSidenav = false">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-6 h-6"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M6 18L18 6M6 6l12 12"
        />
      </svg>
    </button>
  </nav>
</template>

<style scope></style>
