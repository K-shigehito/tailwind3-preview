<script setup lang="ts">
import BaseHeadding from './components/BaseHeadding.vue';
import AspectRatio from './components/AspectRatio.vue';
import Border from './components/Border.vue';
import Column from './components/Column.vue';
import ScrollBehavior from './components/ScrollBehavior.vue';
import ScrollSnap from './components/ScrollSnap.vue';
import TextIndent from './components/TextIndent.vue';
import OpenVariant from './components/OpenVariant.vue';
import Upload from './components/Upload.vue';
import FlexBasis from './components/FlexBasis.vue';
</script>

<template>
  <div class="flex flex-col gap-[40px] m-[20px] divide-y-[1px] divide-gray-500">
    <div class="pt-[0px]">
      <BaseHeadding>aspect-ratio</BaseHeadding>
      <AspectRatio />
    </div>
    <div class="pt-[12px]">
      <BaseHeadding>scrpll-snap</BaseHeadding>
      <ScrollSnap />
    </div>
    <div class="pt-[12px]">
      <BaseHeadding>scroll-behavior</BaseHeadding>
      <ScrollBehavior />
    </div>
    <div class="pt-[12px]">
      <BaseHeadding>text-indent</BaseHeadding>
      <TextIndent />
    </div>
    <div class="pt-[12px]">
      <BaseHeadding>border-x and border-y</BaseHeadding>
      <Border />
    </div>
    <div class="pt-[12px]">
      <BaseHeadding>column</BaseHeadding>
      <Column />
    </div>
    <div class="pt-[12px]">
      <BaseHeadding>column</BaseHeadding>
      <FlexBasis />
    </div>

    <div class="pt-[12px]">
      <BaseHeadding>open</BaseHeadding>
      <OpenVariant />
    </div>
    <div class="pt-[12px]">
      <BaseHeadding>upload</BaseHeadding>
      <Upload />
    </div>
  </div>
</template>

<style></style>
