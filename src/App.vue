<template>
  <Navbar />
  <div class="wrapper">
    <p class="subtitle">THE DEVELOPER COMPANY</p>
    <p class="ingress">
      Software designed for possibilities. DevComp is a consultancy firm based
      in Uppsala, Sweden. We offer digital solutions tailor made to your needs
      and liking. Contact us if you need to further develop your business with a
      custom software solution.
    </p>
    <div class="contact-container">
      <p class="contact" style="margin-bottom: 10px">Contact us at:</p>
      <a class="contact" href="mailto:info@devcompany.se">info@devcompany.se</a>
    </div>
    <p
      class="ingress"
      style="text-align: center; margin-top: 30px; font-size: 15px"
    >
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
