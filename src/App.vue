<template>
  <Navbar />
  <div class="flex flex-col justify-center items-center text-center ">
    <p class="text-white text-2xl sm:text-4xl mt-8 font-bold">
      THE DEVELOPER COMPANY
    </p>
    <p class="text-justify text-white sm:text-3xl my-12 w-10/12 sm:max-w-2xl">
      Software designed for possibilities. DevComp is a consultancy firm based
      in Uppsala, Sweden. We offer digital solutions tailor made to your needs
      and liking. Contact us if you need to further develop your business with a
      custom software solution.
    </p>
    <div
      class="text-white text-2xl sm:text-3xl flex flex-col justify-center items-center font-bold"
    >
      <p class="mb-5">Contact us at:</p>
      <a class="underline" href="mailto:info@devcompany.se"
        >info@devcompany.se</a
      >
    </div>
    <p class=" text-white text-sm m-5">
      This page is currently a work in progress, drop by in the future to see
      what we're up to! 🚀
    </p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Navbar from "./Navbar.vue";
export default defineComponent({
  components: {
    Navbar,
  },
});
</script>
