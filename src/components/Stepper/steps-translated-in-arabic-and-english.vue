<script setup></script>

<template>
  <ol role="list" class="space-y-4 md:flex md:space-x-8 md:space-y-0">
    <li class="md:flex-1">
      <!-- Completed Step -->
      <a
        href="#"
        class="group flex flex-col border-l-4 border-red-600 py-2 pl-4 hover:border-red-800 md:border-l-0 md:border-t-4 md:pb-0 md:pl-0 md:pt-4"
      >
        <span class="text-sm font-medium text-red-600 group-hover:text-red-800">Step 1 / الخطوه ١</span>
        <span class="text-sm font-medium">Job details / تفاصيل العمل</span>
      </a>
    </li>
    <li class="md:flex-1">
      <!-- Current Step -->
      <a
        href="#"
        class="flex flex-col border-l-4 border-gray-300 py-2 pl-4 md:border-l-0 md:border-t-4 md:pb-0 md:pl-0 md:pt-4"
        aria-current="step"
      >
        <span class="text-sm font-medium text-gray-600">Step 2 / الخطوة ٢</span>
        <span class="text-sm font-medium">Application form / استمارة الطلب</span>
      </a>
    </li>
    <li class="md:flex-1">
      <!-- Upcoming Step -->
      <a
        href="#"
        class="group flex flex-col border-l-4 border-black py-2 pl-4 hover:border-gray-300 md:border-l-0 md:border-t-4 md:pb-0 md:pl-0 md:pt-4"
      >
        <span
          class="text-sm font-medium text-gray-500 group-hover:text-gray-700"
        >Step 3 / الخطوه 3</span>
        <span class="text-sm font-medium">Preview / معاينة</span>
      </a>
    </li>
  </ol>
</template>

<style scope></style>
