<script setup lang="ts">
import AspectRatio from './components/AspectRatio.vue';
import Border from './components/Border.vue';
import Column from './components/Column.vue';
import OpenVariant from './components/OpenVariant.vue';
import ScrollBehavior from './components/ScrollBehavior.vue';
import ScrollSnap from './components/ScrollSnap.vue';
import TextIndent from './components/TextIndent.vue';
</script>

<template>
  <div class="m-[20px]">
    <AspectRatio />
    <div class="h-[60px] mb-[12px] border-b-[1px] border-gray-500"></div>
    <ScrollSnap />
    <div class="h-[60px] mb-[12px] border-b-[1px] border-gray-500"></div>
    <ScrollBehavior />
    <div class="h-[60px] mb-[12px] border-b-[1px] border-gray-500"></div>
    <TextIndent />
    <div class="h-[60px] mb-[12px] border-b-[1px] border-gray-500"></div>
    <Border />
    <div class="h-[60px] mb-[12px] border-b-[1px] border-gray-500"></div>
    <OpenVariant />
    <div class="h-[60px] mb-[12px] border-b-[1px] border-gray-500"></div>
    <Column />
  </div>
</template>

<style></style>
