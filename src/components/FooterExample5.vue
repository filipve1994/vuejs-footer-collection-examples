<template>
  <div class="font-poppins bg-gray-100">
    <div class="max-w-screen-xl py-10 px-4 sm:px-6 text-gray-800 sm:flex justify-between mx-auto">
      <div class="p-5 sm:w-8/12">
        <h3 class="font-bold text-3xl text-indigo-600 mb-4">Componentity</h3>

        <div class="flex text-gray-500 uppercase text-sm">
          <a href="#" class="mr-2 hover:text-indigo-600">Home</a>
          <a href="#" class="mr-2 hover:text-indigo-600">About Us</a>
          <a href="#" class="mr-2 hover:text-indigo-600">Contact Us</a>
          <a href="#" class="mr-2 hover:text-indigo-600">Support Us</a>
        </div>

      </div>
      <div class="p-5 sm:w-4/12">
        <h3 class="font-medium text-lg text-indigo-600 mb-4">Subscribe to our Newsletter</h3>
        <form class="mt-4">
          <input class="border rounded w-full px-4 py-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" type="email" placeholder="username@email.com">
        </form>
      </div>
    </div>
    <div class="flex py-5 m-auto text-gray-800 text-sm flex-col items-center border-t max-w-screen-xl">
      <p>© Copyright 2020. All Rights Reserved.</p>
    </div>
  </div>

</template>

<!--https://codepen.io/componentity/pen/ZEWpJMJ -->
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "FooterExample5",
  props: {},
  data() {
    return {};
  },
  setup(props) {
    return {};
  }
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

body, .font-poppins  {
  font-family: 'Poppins', sans-serif !important;
}

</style>
