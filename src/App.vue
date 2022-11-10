<script setup>
 import SideBar from "./components/SideBar"
 import ImageGallery from "./components/ImageGallery"
 import { ref } from "vue";

 const isWithColor = ref(true)

 const onSelectOption = (isColor) => {
  isWithColor.value = isColor
 }
</script>

<template>
  <VApp>
    <SideBar @selectOption="onSelectOption" />
    <VMain>
      <ImageGallery :isWithColor="isWithColor" />
    </VMain>
  </VApp>
</template>
