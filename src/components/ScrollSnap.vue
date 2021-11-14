<template>
  <h2 class="mt-[24px] font-bold text-[24px]">scroll-snap</h2>
  <div
    class="
      flex
      gap-[20px]
      items-center
      overflow-x-auto
      w-[500px]
      mt-[12px]
      snap-x snap-mandatory
    "
  >
    <div
      class="
        flex-shrink-0 flex
        items-center
        justify-center
        w-[300px]
        h-[100px]
        bg-blue-200
        snap-start
      "
    >
      snap-start
    </div>
    <div
      class="
        flex-shrink-0 flex
        items-center
        justify-center
        w-[300px]
        h-[100px]
        bg-rose-200
        snap-center
      "
    >
      snap-center
    </div>
    <div
      class="
        flex-shrink-0 flex
        items-center
        justify-center
        w-[300px]
        h-[100px]
        bg-violet-200
        snap-center
      "
    >
      snap-center
    </div>
    <div
      class="
        flex-shrink-0 flex
        items-center
        justify-center
        w-[300px]
        h-[100px]
        bg-yellow-200
        snap-end
      "
    >
      snap-end
    </div>
  </div>
</template>
