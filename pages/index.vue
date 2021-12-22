<template>
  <div>
    <!-- menu bar -->
    <div class="flex bg-gray-900 text-white py-5">
      <div class="w-1/2 pl-10">🍔 BurgerQueen</div>
      <div class="w-1/2">
        <ul class="flex justify-end mr-20">
          <li class="mr-10">Our menu</li>
          <li class="mr-10">Store locations</li>
          <li class="mr-10">About us</li>
        </ul>
      </div>
    </div>
    <!-- header row -->
    <div class="mx-auto px-3 pt-20 pb-32">
      <header class="text-center">
        <h1 class="text-5xl text-gray-900 font-bold whitespace-pre-line leading-hero">
          DINE IN NOW AVAILABLE
        </h1>
        <p class="text-primary-500 mt-5">Head on over to a joint near you!</p>
      </header>
    </div>

    <!-- first row -->
    <div class="bg-gray-900 px-10 py-10 text-yellow-400">
      <p class="text-3xl mb-5">MYBURGERLAB = YOUR BURGER LAB</p>
      <div class="flex">
        <div class="w-1/4 bg-gray-700 px-5 py-5">
          <div class="text-yellow-400 text-xl font-semibold">BAMBOO CHARCOAL BUNS</div>
          <p class="text-white">
            Fluffy, tasty and oh'so addictive. Our buns are prepared from scratch and
            baked fresh daily.
          </p>
        </div>
        <div class="w-1/4 bg-gray-700 ml-5 px-5 py-5">
          <div class="text-yellow-400 text-xl font-semibold">PATTIES TO DIE FOR</div>
          <p class="text-white">
            From Juicy Beef patties, to Fried Chicken Thighs, to Portobello Mushrooms, or
            even Tofu patties, you're spoilt for choice.
          </p>
        </div>
        <div class="w-1/4 bg-gray-700 ml-5 px-5 py-5">
          <div class="text-yellow-400 text-xl font-semibold">CRAZY COMBINATIONS</div>
          <p class="text-white">
            From Juicy Beef patties, to Fried Chicken Thighs, to Portobello Mushrooms, or
            even Tofu patties, you're spoilt for choice.
          </p>
        </div>
        <div class="w-1/4 bg-gray-700 ml-5 px-5 py-5">
          <div class="text-yellow-400 text-xl font-semibold">HACK-YOUR-OWN</div>
          <p class="text-white">
            From Juicy Beef patties, to Fried Chicken Thighs, to Portobello Mushrooms, or
            even Tofu patties, you're spoilt for choice.
          </p>
        </div>
      </div>
    </div>

    <!-- second row -->
    <div class="pt-20 pb-20 text-center">
      <h2 class="mb-5">Follow us on Social Media</h2>
      <button
        class="bg-blue-500 px-4 py-2 font-semibold text-white inline-flex items-center space-x-2 rounded"
      >
        <svg
          class="w-5 h-5 fill-current"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
        >
          <path
            d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"
          />
        </svg>
        <span>Facebook</span>
      </button>

      <button
        class="bg-blue-300 px-4 py-2 font-semibold text-white inline-flex items-center space-x-2 rounded"
      >
        <svg
          class="w-5 h-5 fill-current"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
        >
          <path
            d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z"
          />
        </svg>
        <span>Twitter</span>
      </button>

      <button
        class="bg-green-500 px-4 py-2 font-semibold text-white inline-flex items-center space-x-2 rounded"
      >
        <svg
          class="w-6 h-6 text-white-400 fill-current"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 448 512"
        >
          <path
            d="M380.9 97.1C339 55.1 283.2 32 223.9 32c-122.4 0-222 99.6-222 222 0 39.1 10.2 77.3 29.6 111L0 480l117.7-30.9c32.4 17.7 68.9 27 106.1 27h.1c122.3 0 224.1-99.6 224.1-222 0-59.3-25.2-115-67.1-157zm-157 341.6c-33.2 0-65.7-8.9-94-25.7l-6.7-4-69.8 18.3L72 359.2l-4.4-7c-18.5-29.4-28.2-63.3-28.2-98.2 0-101.7 82.8-184.5 184.6-184.5 49.3 0 95.6 19.2 130.4 54.1 34.8 34.9 56.2 81.2 56.1 130.5 0 101.8-84.9 184.6-186.6 184.6zm101.2-138.2c-5.5-2.8-32.8-16.2-37.9-18-5.1-1.9-8.8-2.8-12.5 2.8-3.7 5.6-14.3 18-17.6 21.8-3.2 3.7-6.5 4.2-12 1.4-32.6-16.3-54-29.1-75.5-66-5.7-9.8 5.7-9.1 16.3-30.3 1.8-3.7.9-6.9-.5-9.7-1.4-2.8-12.5-30.1-17.1-41.2-4.5-10.8-9.1-9.3-12.5-9.5-3.2-.2-6.9-.2-10.6-.2-3.7 0-9.7 1.4-14.8 6.9-5.1 5.6-19.4 19-19.4 46.3 0 27.3 19.9 53.7 22.6 57.4 2.8 3.7 39.1 59.7 94.8 83.8 35.2 15.2 49 16.5 66.6 13.9 10.7-1.6 32.8-13.4 37.4-26.4 4.6-13 4.6-24.1 3.2-26.4-1.3-2.5-5-3.9-10.5-6.6z"
          ></path>
        </svg>
        <span>WhatsApp</span>
      </button>
    </div>

    <!-- footer row -->
    <div class="bg-gray-700 py-10 text-white">
      <div class="flex max-w-5xl mx-auto">
        <!-- column 1 -->
        <div class="w-1/3 pl-10">
          <h3 class="text-2xl mb-2">🍔 BurgerQueen</h3>
          <p>We are out to make the world a better place. One burger at a time.</p>
        </div>

        <!-- column 2 -->
        <div class="w-1/3 pl-20 pt-3">
          <ul>
            <li>
              <a href="#">Menu</a>
            </li>
            <li>
              <a href="#">Store locations</a>
            </li>
            <li>
              <a href="#">About us</a>
            </li>
          </ul>
        </div>

        <!-- column 3 -->
        <div class="w-1/3 pt-3 pl-10">
          <ul>
            <li>
              <a href="#">Privacy policy</a>
            </li>
            <li>
              <a href="#">Terms of us</a>
            </li>
            <li>
              <a href="#">Contact us</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
