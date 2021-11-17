<template>
  <div class="accent-red-500 text-[20px]">
    <div class="font-bold">radio</div>
    <div>
      <input id="huey" type="radio" name="drone" value="huey" checked />
      <label for="huey" class="ml-[4px]">Huey</label>
    </div>
    <div class="accent-indigo-500">
      <input id="dewey" type="radio" name="drone" value="dewey" />
      <label for="dewey" class="ml-[4px]">Dewey</label>
    </div>
    <div class="accent-amber-500">
      <input id="louie" type="radio" name="drone" value="louie" />
      <label for="louie" class="ml-[4px]">Louie</label>
    </div>
  </div>

  <div class="mt-[12px] accent-green-500 text-[20px]">
    <div class="font-bold">checkbox</div>
    <div>
      <input id="scales" type="checkbox" name="scales" checked />
      <label for="scales" class="ml-[4px]">Scales</label>
    </div>

    <div>
      <input id="horns" type="checkbox" name="horns" />
      <label for="horns" class="ml-[4px]">Horns</label>
    </div>
  </div>
</template>
