<template>
  <div>

    <!-- ------ UPPER FOOTER ------ -->

    <div class="md:flex justify-between">
      <div class="my-auto">
        <p class="logo text-4xl font-bold mb-3">Crafteza.</p>
        <p class="text-gray-500 mb-3">
          400 University Drive Suite 200 Coral Gables, FL 33134 USA
        </p>
      </div>
      <div>
        <p class=" font-bold mb-8">ABOUT</p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer mb-5 transition duration-200 ease-in">
          Shop
        </p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer mb-5 transition duration-200 ease-in">
          Delivery
        </p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in">
          Returns
        </p>
      </div>
      <div>
        <p class="twentieth font-bold mb-8">HELP</p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer mb-5 transition duration-200 ease-in">
          Payment Options
        </p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer mb-5 transition duration-200 ease-in">
          Contact Us
        </p>
      </div>
      <div>
        <p class="twentieth font-bold mb-8">NEWSLETTER</p>
        <PrelineSubscribeForm />
      </div>
    </div>
    
    <!-- ------ LOWER FOOTER ------ -->

    <hr class="my-8 border-gray-500" />
    <div class="md:flex justify-between text-center">
      <p class="text-gray-500 mb-5 md:mb-0">&copy; 2022 - All Copyrights Reserved</p>
      <div class="flex gap-10">
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in">About Us</p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in">Blog</p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in">FAQs</p>
        <p class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in">Contact</p>
      </div>
    </div>
  </div>
</template>

<script>
import FacebookIcon from '@mui/icons-material/Facebook';

export default {
  components: {
    FacebookIcon,
  },
}
</script>

<style lang="sass" scoped>
</style>
