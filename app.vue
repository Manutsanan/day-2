<template>
  <div class="w-full h-screen flex justify-center items-center gap-6">
    <div>Golf</div>
    <!-- 1 -->
    <div
      class="grid grid-cols-1 h-[500px] w-[500px] rounded-lg border-4 border-black"
    >
      <div
        class="flex justify-center items-center bg-rose-500 text-white text-4xl rounded-t"
      >
        Box 1
      </div>
      <div
        class="flex justify-center items-center bg-blue-500 text-white text-4xl rounded-b"
      >
        Box 2
      </div>
    </div>

    <!-- 2 -->
    <div
      class="grid grid-cols-2 h-[500px] w-[500px] rounded-lg border-4 border-black"
    >
      <div
        class="flex justify-center items-center bg-rose-500 text-white text-4xl rounded-l"
      >
        Box 1
      </div>
      <div
        class="flex justify-center items-center bg-blue-500 text-white text-4xl rounded-r"
      >
        Box 2
      </div>
    </div>

    <!-- 3 -->
    <div
      class="grid grid-cols-3 h-[500px] w-[500px] rounded-lg border-4 border-black"
    >
      <div
        class="flex justify-center items-center bg-rose-500 text-white text-4xl rounded-l"
      >
        Box 1
      </div>
      <div
        class="flex justify-center items-center bg-blue-500 text-white text-4xl"
      >
        Box 2
      </div>
      <div
        class="flex justify-center items-center bg-rose-500 text-white text-4xl rounded-r"
      >
        Box 3
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
//
</script>

<style>
/*  */
</style>
