<template>
  <br>
  <section class="py-12 sm:py-16">
    <div v-if="products">
      <div class="container mx-auto px-4">
        <nav class="flex">
          <ol role="list" class="flex items-center">
            <li class="text-left">
              <div class="-m-1">
                <a href="/"
                  class="rounded-md p-1 text-sm font-medium text-gray-600 focus:text-gray-900 focus:shadow hover:text-gray-800">
                  Home </a>
              </div>
            </li>
          </ol>
        </nav>

        <div class="lg:col-gap-12 xl:col-gap-16 mt-8 grid grid-cols-1 gap-12 lg:mt-12 lg:grid-cols-5 lg:gap-16">
          <div class="lg:col-span-3 lg:row-end-1">
            <div class="lg:flex lg:items-start">
              <div class="lg:order-2 lg:ml-5">
                <div class="max-w-xl overflow-hidden rounded-lg">
                  <img class="h-full w-full max-w-full object-cover" src="https://cf.shopee.co.id/file/93c0fac70b325d766f306c3c31798d75" alt="" />
                </div>
              </div>

              <div class="mt-2 w-full lg:order-1 lg:w-32 lg:flex-shrink-0">
                <div class="flex flex-row items-start lg:flex-col">
                  <button type="button"
                    class="flex-0 aspect-square mb-3 h-20 overflow-hidden rounded-lg border-2 border-gray-900 text-center">
                    <img class="h-full w-full object-cover" src="https://cf.shopee.co.id/file/93c0fac70b325d766f306c3c31798d75" alt="" />
                  </button>
                  <button type="button"
                    class="flex-0 aspect-square mb-3 h-20 overflow-hidden rounded-lg border-2 border-transparent text-center">
                    <img class="h-full w-full object-cover" src="https://cf.shopee.co.id/file/93c0fac70b325d766f306c3c31798d75" alt="" />
                  </button>
                  <button type="button"
                    class="flex-0 aspect-square mb-3 h-20 overflow-hidden rounded-lg border-2 border-transparent text-center">
                    <img class="h-full w-full object-cover" src="https://cf.shopee.co.id/file/93c0fac70b325d766f306c3c31798d75" alt="" />
                  </button>
                </div>
              </div>
            </div>
          </div>

          <div class="lg:col-span-2 lg:row-span-2 lg:row-end-2">
            <h1 class="sm: text-2xl font-bold text-gray-900 sm:text-3xl">{{ products.name }}</h1>

            <div class="mt-5 flex items-center">
              <div class="flex items-center">
                <svg class="block h-4 w-4 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20" fill="currentColor">
                  <path
                    d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                    class=""></path>
                </svg>
                <svg class="block h-4 w-4 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20" fill="currentColor">
                  <path
                    d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                    class=""></path>
                </svg>
                <svg class="block h-4 w-4 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20" fill="currentColor">
                  <path
                    d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                    class=""></path>
                </svg>
                <svg class="block h-4 w-4 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20" fill="currentColor">
                  <path
                    d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                    class=""></path>
                </svg>
                <svg class="block h-4 w-4 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20" fill="currentColor">
                  <path
                    d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                    class=""></path>
                </svg>
              </div>
              <p class="ml-2 text-sm font-medium text-gray-500">1,209 Reviews</p>
            </div>


            <h2 class="mt-8 text-base text-gray-900">Sepatu prape dengan kualitas yang terjamin </h2>
            <div class="absolute top-0 right-1 flex sm:bottom-0 sm:top-auto">
              <button type="button"
                class="flex rounded p-2 text-center text-gray-500 transition-all duration-200 ease-in-out focus:shadow hover:text-gray-900">
                <svg class="block h-5 w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                  stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" class="">
                  </path>
                </svg>
              </button>
            </div>


            <div
              class="mt-10 flex flex-col items-center justify-between space-y-4 border-t border-b py-4 sm:flex-row sm:space-y-0">
              <div class="flex items-end">
                <h1 class="text-3xl font-bold">Rp.{{ products.base_price * cek }}</h1>
                
              </div>

              <div v-if="token">
                <button type="button" @click="addCart(products.id)"
                  class="inline-flex items-center justify-center rounded-md border-2 border-transparent bg-gray-900 bg-none px-12 py-3 text-center text-base font-bold text-white transition-all duration-200 ease-in-out focus:shadow hover:bg-gray-800">
                  <svg xmlns="http://www.w3.org/2000/svg" class="shrink-0 mr-3 h-5 w-5" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                  </svg>
                  + Cart
                </button>
              </div>

              <div v-else>
              <router-link to="/login">
                <button type="button"
                  class="inline-flex items-center justify-center rounded-md border-2 border-transparent bg-gray-900 bg-none px-12 py-3 text-center text-base font-bold text-white transition-all duration-200 ease-in-out focus:shadow hover:bg-gray-800">
                  <svg xmlns="http://www.w3.org/2000/svg" class="shrink-0 mr-3 h-5 w-5" fill="none" viewBox="0 0 24 24"
                    stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                  </svg>
                  + Cart
                </button>
              </router-link>
            </div>
            </div>
            
            <ul class="mt-8 space-y-2">
              <li class="flex items-center text-left text-sm font-medium text-gray-600">
                <svg class="mr-2 block h-5 w-5 align-middle text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none"
                  viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                    class=""></path>
                </svg>
                Free shipping worldwide
              </li>

              <li class="flex items-center text-left text-sm font-medium text-gray-600">
                <svg class="mr-2 block h-5 w-5 align-middle text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none"
                  viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z" class="">
                  </path>
                </svg>
                Cancel Anytime
              </li>
            </ul>
          </div>

          <div class="lg:col-span-3">
            <div class="border-b border-gray-300">
              <nav class="flex gap-4">

                <a href="#" title=""
                  class="inline-flex items-center border-b-2 border-transparent py-4 text-sm font-medium text-gray-600">
                  Reviews
                  <span class="ml-2 block rounded-full bg-gray-500 px-2 py-px text-xs font-bold text-gray-100"> 1,209
                  </span>
                </a>
              </nav>
            </div>
            <ul class="">
  <li class="py-8 text-left border px-4 m-2">
    <div class="flex items-start">
      <img class="block h-10 w-10 max-w-full flex-shrink-0 rounded-full align-middle" src="data:image/png;base64,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" alt="" />

      <div class="ml-6">
        <div class="flex items-center">
          <svg class="block h-6 w-6 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" class=""></path>
          </svg>
          <svg class="block h-6 w-6 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" class=""></path>
          </svg>
          <svg class="block h-6 w-6 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" class=""></path>
          </svg>
          <svg class="block h-6 w-6 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" class=""></path>
          </svg>
          <svg class="block h-6 w-6 align-middle text-yellow-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" class=""></path>
          </svg>
      
        </div>
        <p class="mt-5 text-base text-gray-900">Puas banget gan dengan produk nyab real banget...anak saya suka.</p>
        <p class="mt-5 text-sm font-bold text-gray-900">Ikbal Miftahudin</p>
        <p class="mt-1 text-sm text-gray-600">Agustus 017, 2023</p>
      </div>
      
    </div>
  </li>
</ul>

           
          </div>
        </div>
      </div>
    </div>
    <div v-else>
      <div class="h-screen bg-white">
        <div class="flex justify-center items-center h-full">
          <img class="h-16 w-16" src="https://icons8.com/preloaders/preloaders/1488/Iphone-spinner-2.gif" alt="">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import { mapGetters, mapActions } from "vuex";

export default {
  data(){
    return {
      token : null,
      cek : 1
    }
  },
  computed: {
    ...mapGetters("product", ["getProdukSlug"]),
    products() {
      return this.getProdukSlug(this.$route.params.slug);
    },
  },
  methods: {
    ...mapActions("product", ["fetchSingleProduk"]),
    ...mapActions("product", ["fetchProduk"]),
    ...mapActions("cart", ["fetchCart"]),
    ...mapActions("product",["addCart"]),

    async addCart(productId) {
      try {
        await this.$store.dispatch('product/addCart', productId);
        this.fetchCart();
      } catch (error) {
        console.error(error)
      }
    },

    tambah(){
      this.cek++
    },
    kurang(){
      if(this.cek > 1){
      this.cek--
      }
    }

  },
  beforeMount() {
    this.fetchProduk()
    this.fetchCart()
   
  },
  mounted(){
      const Slug = this.$route.params.slug;
      this.fetchSingleProduk(Slug)
      
      //cek token
      const cektoken = localStorage.getItem('token');
      this.token = cektoken
    }


};
</script>