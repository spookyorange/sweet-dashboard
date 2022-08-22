<script setup>
import FooterItem from "./footer_components/FooterItem.vue";
</script>

<template>
  <ul class="footer">
    <FooterItem text="some stuff" />
    <FooterItem text="about" />
    <FooterItem text="your company" />
    <FooterItem text="i do not" />
    <FooterItem text="give a damn" />
  </ul>
  <p
    class="w-screen flex justify-center bg-purple-500 text-sm text-gray-700 p-2 pb-4"
  >
    This dashboard is under MIT license, so yeah...
  </p>
</template>
