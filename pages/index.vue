<template>
  <div class="flex justify-between">
    <div class="flex items-center">
      <div class="w-auto p-4">
        <p class="font-bold text-sm sm:text-2xl space-x-4">WORLDWIDETRAINER</p>
      </div>
      <div>
        <img class="w-10" src="@/assets/logo_low_res.png" />
      </div>
    </div>
    <div class="flex items-center space-x-4">
      <div>
        <img class="w-5" src="@/assets/instagram.svg" />
      </div>
      <div>
        <img class="w-5" src="@/assets/facebook.svg" />
      </div>
      <div>
        <img class="w-5" src="@/assets/twitter.svg" />
      </div>
      <div>
        <button class="bg-gray-400 hover:bg-gray-300 rounded py-1 px-3">Login</button>
      </div>
      <div>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          class="w-5"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M15 9a2 2 0 10-4 0v5a2 2 0 01-2 2h6m-6-4h4m8 0a9 9 0 11-18 0 9 9 0 0118 0z"
          />
        </svg>
      </div>
      <div>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          class="w-5"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
          />
        </svg>
      </div>
      <div>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          class="w-5"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"
          />
        </svg>
      </div>
    </div>
  </div>
</template>

<script>
const imgTest =
  "https://image.tmdb.org/t/p/w500/wwemzKWzjKYJFfCeiB57q3r4Bcm.png";
export default {
  data: () => ({
    imgTest: imgTest,
  }),
};
</script>

<style>
</style>
