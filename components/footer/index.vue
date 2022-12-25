<template>
  <div class="mt-20 md:px-0 px-12">
    <!-- ------ UPPER FOOTER ------ -->

    <div class="md:flex justify-between">
      <div class="my-auto">
        <p class="logo text-4xl font-bold mb-3">Crafteza.</p>
        <p class="text-gray-500 mb-3">
          400 University Drive Suite 200 Coral Gables, FL 33134 USA
        </p>
      </div>
      <div>
        <p class="twentieth font-bold mb-8">ABOUT</p>
        <div class="mb-5">
          <a
            href="#"
            class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >
            Shop
          </a>
        </div>
        <div class="mb-5">
          <a
            href="#"
            class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >
            Delivery
          </a>
        </div>
        <div class="mb-5">
          <a
            href="#"
            class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >
            Returns
          </a>
        </div>
      </div>
      <div>
        <p class="twentieth font-bold mb-8">HELP</p>
        <div class="mb-5">
          <a
            href="#"
            class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >
            Payment Options
          </a>
        </div>
        <div class="mb-5">
          <a
            href="#"
            class="text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >
            Contact Us
          </a>
        </div>
      </div>
      <div>
        <p class="sacramento mb-4 text-4xl">Subscribe Our Newsletter</p>
        <PrelineSubscribeForm />
      </div>
    </div>

    <!-- ------ LOWER FOOTER ------ -->

    <hr class="my-8 border-gray-500" />
    <div class="md:flex justify-between text-center">
      <p class="text-gray-500 mb-5 md:mb-0">
        &copy; 2022 - All Copyrights Reserved
      </p>
      <div class="flex gap-10">
        <a
          href="#"
          class="inline-block text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >About Us</a
        >
        <a
          href="#"
          class="inline-block text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >Blog</a
        >
        <a
          href="#"
          class="inline-block text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >FAQs</a
        >
        <a
          href="#"
          class="inline-block text-gray-500 hover:text-orange-600 cursor-pointer transition duration-200 ease-in"
          >Contact</a
        >
      </div>
    </div>
  </div>
</template>

<script>
import FacebookIcon from "@mui/icons-material/Facebook";

export default {
  components: {
    FacebookIcon,
  },
};
</script>

<style lang="sass" scoped></style>
