<script setup lang="ts"></script>

<template>
  <div class="bg-blue-500">
    <div
      class="flex justify-center container mx-auto my-auto w-screen h-screen items-center flex-col"
    >
      <div class="text-slate-100 items-center">
        <svg
          class="w-10 h-10 mx-auto pb-3"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
          />
        </svg>
        <div class="text-center pb-3">
          Welcome back!
        </div>
      </div>

      <div
        class="w-full md:w-3/4 lg:w-1/2 flex flex-col items-center bg-slate-50 rounded-md pt-12"
      >
        <!-- email input -->
        <div class="w-3/4 mb-6">
          <input
            id="email"
            type="email"
            name="email"
            class="w-full py-4 px-8 bg-slate-200 placeholder:font-semibold rounded hover:ring-1 hover:ring-gray-600 outline-slate-500 border-solid border-2 border-slate-300"
            placeholder="Email adress"
          >
        </div>
        <!-- password input -->
        <div class="w-3/4 mb-6">
          <input
            id="password"
            type="password"
            name="password"
            class="w-full py-4 px-8 bg-slate-200 placeholder:font-semibold rounded hover:ring-1 hover:ring-gray-600 outline-slate-500 border-solid border-2 border-slate-300"
            placeholder="Password"
          >
        </div>
        <!-- button -->
        <div class="w-3/4 mb-12">
          <button
            type="submit"
            class="py-4 bg-blue-500 w-full rounded text-blue-50 font-bold hover:bg-blue-700"
          >
            LOGIN
          </button>
        </div>
      </div>
      <div
        class="flex justify-center container mx-auto mt-6 text-slate-100 text-sm"
      >
        <div
          class="flex flex-col sm:flex-row justify-between md:w-1/2 items-center"
        >
          <div class="flex">
            Forgot your password
          </div>
          <div class="flex">
            Don't have an account? Get Started
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scope></style>
