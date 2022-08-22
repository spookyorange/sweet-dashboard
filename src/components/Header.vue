<script setup>
import LinkItem from "./header_components/LinkItem.vue";
</script>

<template>
  <div class="bg-purple-500 sticky top-0">
    <div class="flex items-center w-screen p-2">
      <MenuIcon class="h-12 w-12 md:hidden" />
      <h2 class="text-3xl mx-auto font-bold">Sweet Dashboard!</h2>
    </div>
    <ul class="header">
      <LinkItem text="Dashboard" />
      <LinkItem text="Add Stuff" />
      <LinkItem text="More Options" />
      <LinkItem text="Track Employee" />
      <LinkItem text="Support" />
    </ul>
  </div>
</template>

<script>
import { MenuIcon } from "@heroicons/vue/solid";

export default {
  components: { MenuIcon },
};
</script>
