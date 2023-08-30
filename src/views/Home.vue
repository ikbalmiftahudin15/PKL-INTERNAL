<template>
  <br>
  <br>
 
  <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
    <div class="flex flex-col items-center justify-between w-full mb-10 lg:flex-row">
      <div class="mb-16 lg:mb-0 lg:max-w-lg lg:pr-5">
        <div class="max-w-xl mb-6">
          <div>
            <p class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
              OnlineShopphing
            </p>
          </div>
          <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
            Masih bingung dengan onlineshop?<br class="hidden md:block" />
           
            <span class="inline-block text-deep-purple-accent-400">OnlineShopphing</span>
          </h2>
          <p class="text-base text-gray-700 md:text-lg">
            OnlineShopphing hadir untuk kalian, untuk memudahkan mencari barang dengan kualitas yang bagus dan harga terjangkau.
          </p>
        </div>
        <div class="flex items-center space-x-3">
          <a href="/" class="w-32 transition duration-300 hover:shadow-lg">
            <img src="https://ganeshaoperation.com/img/diskon/diskonguru.png" class="object-cover object-top w-full h-auto mx-auto" alt="" />
          </a>
          <a href="/" class="w-32 transition duration-300 hover:shadow-lg">
            <img src="../assets/img/Capture.PNG" class="object-cover object-top w-full h-auto mx-auto" alt="" />
          </a>
        </div>
      </div>
      <div class="flex items-center justify-center lg:w-1/2">
        <div class="w-2/5">
          <img class="object-cover" src="https://kitwind.io/assets/kometa/one-girl-phone.png" alt="" />
        </div>
        <div class="w-5/12 -ml-16 lg:-ml-32">
          <img class="object-cover" src=" https://www.tailwind-kit.com/images/object/10.png" alt="" />
        </div>
      </div>
  </div>
  </div>

<br><br><br>
            <!-- source: https://github.com/mfg888/Responsive-Tailwind-CSS-Grid/blob/main/index.html -->
           
<div class="text-center p-10">
    <h1 class="font-bold text-4xl mb-4">Best Product OnlineShopphing</h1>
    <p>Ayo kunjungi OnlineShopphing dengan product yang kualitan 100%</p>
</div>

  <main class=" py-2  flex items-center justify-center flex-wrap">
    <!--     primera card -->
    <div class="bg-white w-72 h-96 shadow-md rounded m-3">
      <div class="h-3/4 w-full">
        <img class="w-full h-full object-cover rounded-t" src="https://media.dinomarket.com/docs/imgTD/2019-12/pic_iphone11promax_All1_061219081219_ll.jpg.jpg" alt="piña">
      </div>
      <div class="w-full h-1/4 p-3">
        <a href="#" class=" hover:text-yellow-600 text-gray-700">
          <span class="text-lg font-semibold uppercase tracking-wide ">Iphone 11 Pro Max</span>
        </a>
        <p class="text-gray-600 text-sm leading-5 mt-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
    <!--     segunda card -->
    <div class="bg-white w-72 h-96 shadow-md rounded m-3">
      <div class="h-3/4 w-full">
        <img class="w-full h-full object-cover rounded-t" src="https://www.footlocker.id/media/catalog/product/cache/e81e4f913a1cad058ef66fea8e95c839/0/1/01-NIKE-FFSSBNIK5-NIKDX0137002-White.jpg" alt="piña">
      </div>
      <div class="w-full h-1/4 p-3">
        <a href="#" class=" hover:text-yellow-600 text-gray-700">
          <span class="text-lg font-semibold uppercase tracking-wide ">Air Jordan Max</span>
        </a>
        <p class="text-gray-600 text-sm leading-5 mt-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
    <!--     tercera card -->
    <div class="bg-white w-72 h-96 shadow-md rounded m-3">
      <div class="h-3/4 w-full">
        <img class="w-full h-full object-cover rounded-t" src="https://www.luckyelektronik.com/wp-content/uploads/2023/06/POLYTRON-PLD-55UV5920.jpg" alt="piña">
      </div>
      <div class="w-full h-1/4 p-3">
        <a href="#" class=" hover:text-yellow-600 text-gray-700">
          <span class="text-lg font-semibold uppercase tracking-wide ">Tv led</span>
        </a>
        <p class="text-gray-600 text-sm leading-5 mt-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>

  </main>


<!-- 🛑 Grid Section - Ends Here -->



<br>
<!--product-->
<div class="text-center p-10">
    <h1 class="font-bold text-4xl mb-4">Product OnlineShopphing</h1>
    <p>Product dengan kualitas dan harga yang pas.</p>
</div>
<div class="w-fit mx-auto grid grid-cols-1 lg:grid-cols-3 md:grid-cols-2 justify-items-center justify-center gap-y-20 gap-x-14 mt-10 mb-5">
      <div v-for="product in getProduk.slice(1,4)" :key="product.slug">
        <div
          class="relative m-10 w-full max-w-xs overflow-hidden rounded-lg bg-gray shadow-md"
        >
          <a href="#">
            <img
              class="h-50 rounded-t-lg object-cover"
              src="https://cf.shopee.co.id/file/93c0fac70b325d766f306c3c31798d75"
              alt="product image"
            />
          </a>
          <span
            class="absolute top-0 left-0 w-28 translate-y-4 -translate-x-6 -rotate-45 bg-black text-center text-sm text-white"
            >Sale</span
          >
          <div class="mt-4 px-5 pb-5">
            <a href="#">
              <h5 class="text-xl font-semibold tracking-tight text-slate-900">
                {{ product.name }}
              </h5>
            </a>
            <div class="mt-2.5 mb-5 flex items-center">
              <span
                class="mr-2 rounded bg-yellow-200 px-2.5 py-0.5 text-xs font-semibold"
                >5.0</span
              >
              <svg
                aria-hidden="true"
                class="h-5 w-5 text-yellow-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                ></path>
              </svg>
              <svg
                aria-hidden="true"
                class="h-5 w-5 text-yellow-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                ></path>
              </svg>
              <svg
                aria-hidden="true"
                class="h-5 w-5 text-yellow-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                ></path>
              </svg>
              <svg
                aria-hidden="true"
                class="h-5 w-5 text-yellow-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                ></path>
              </svg>
              <svg
                aria-hidden="true"
                class="h-5 w-5 text-yellow-300"
                fill="currentColor"
                viewBox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                ></path>
              </svg>
            </div>
            <div class="flex items-center justify-between">
              <p>
                <span class="text-3xl font-bold text-slate-900"
                  >Rp.{{ product.base_price }}</span
                >
              </p>
            </div>
            <div>
              <router-link
                :to="{ name: 'SingleProduk', params: { slug: product.slug } }"
                class="flex items-center rounded-md bg-slate-900 px-5 py-2.5 text-center text-sm font-medium text-white hover:bg-gray-700 focus:outline-none focus:ring-4 focus:ring-blue-300 mt-5"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="mr-2 h-6 w-6"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
                  />
                </svg>
                Details
              </router-link>
            </div>
          </div>
        </div>
      </div>
  </div>


</template>

<script>
import { mapGetters, mapActions } from "vuex";

export default {
  computed: {
    ...mapGetters("product", ["getProduk"]),
  },
  methods: {
    ...mapActions("product", ["fetchProduk"]),
  },
  created() {
    this.fetchProduk();
  },
};
</script>
