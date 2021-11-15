<template>
  <h2 class="mb-[12px] font-bold text-[24px]">scroll-behavior</h2>
  <div class="flex gap-[40px]">
    <nav class="flex gap-[12px] mb-[40px]">
      <a
        href="#page-1"
        class="flex items-center justify-center w-[40px] h-[40px] bg-gray-300"
        >1</a
      >
      <a
        href="#page-2"
        class="flex items-center justify-center w-[40px] h-[40px] bg-gray-300"
        >2</a
      >
      <a
        href="#page-3"
        class="flex items-center justify-center w-[40px] h-[40px] bg-gray-300"
        >3</a
      >
    </nav>

    <div class="h-[280px] w-[280px] scroll-smooth overflow-y-scroll">
      <div id="page-1" class="w-[200px] h-[200px] bg-blue-200">1</div>
      <div id="page-2" class="w-[200px] h-[200px] mt-[20px] bg-pink-200">2</div>
      <div id="page-3" class="w-[200px] h-[200px] mt-[20px] bg-yellow-200">
        3
      </div>
    </div>
  </div>
</template>
