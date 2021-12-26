<template>
  <div>
    <div class="flex bg-gray-900 text-white py-5">
      <div class="w-1/2 pl-10">
        <NuxtLink to="/">🍔 Houz Burger</NuxtLink>
      </div>
      <div class="w-1/2">
        <ul class="flex justify-end mr-20">
          <NuxtLink to="/menu"><li class="mr-10">Our menu</li></NuxtLink>
          <li class="mr-10">Store locations</li>
          <li class="mr-10">About us</li>
        </ul>
      </div>
    </div>
    <div class="pl-5 pr-10">
      <!-- appetizer section -->
      <h1 class="py-5 text-3xl">Appetizer</h1>

      <div class="flex mt-5">
        <div class="w-1/4">
          <img
            class="rounded-xl"
            src="https://myburgerlab.com/static/img/menu/products/img_appe_mushroom-fries.jpg"
            alt=""
          />
        </div>
        <div class="w-3/4 px-5">
          <h3 class="uppercase text-blue-900 font-bold">Mushroom Fries</h3>
          <div class="py-2 pr-5">
            Portabella Mushroom Slices bread crumbed and deep fried. Served w/ our
            signature Red Sauce.
          </div>
          <div class="font-bold">RM14.50</div>
        </div>
      </div>

      <div class="flex mt-5">
        <div class="w-1/4">
          <img
            class="rounded-xl"
            src="https://myburgerlab.com/static/img/menu/products/img_appe_nacho-libre.jpg"
            alt=""
          />
        </div>

        <div class="w-3/4 px-5">
          <h3 class="uppercase text-blue-900 font-bold">Nacho Libre</h3>
          <div class="py-2 pr-5">
            Crunchy Corn chips topped with Jalapenos, Cheese Sauce, tangy Salsa. A great
            starter to any meal!
          </div>
          <div class="font-bold">RM12.00</div>
        </div>
      </div>

      <div class="flex mt-5">
        <div class="w-1/4">
          <img
            class="rounded-xl"
            src="https://myburgerlab.com/static/img/menu/products/img_appe_nacho-libre.jpg"
            alt=""
          />
        </div>

        <div class="w-3/4 px-5">
          <h3 class="uppercase text-blue-900 font-bold">Popcorn Chicken</h3>
          <div class="py-2 pr-5">
            Bite-sized Fried Chicken served with Cheese Sauce with a twist of lime. Goes
            well with Salsa too!
          </div>
          <div class="font-bold">RM10.50</div>
        </div>
      </div>
    </div>

    <hr class="mt-5" />

    <!-- main course section -->
    <div class="px-5">
      <h1 class="py-5 text-3xl">Beef</h1>

      <div class="flex mt-5">
        <div class="w-1/4">
          <img
            class="rounded-xl"
            src="https://myburgerlab.com/static/img/menu/products/img_beef_bm.jpg"
            alt=""
          />
        </div>
        <div class="w-3/4 px-5">
          <h3 class="uppercase font-bold text-blue-900">Messy Beauty</h3>
          <div class="py-2">
            It's as messy as the name says! A Beef patty topped with Lettuce, Honey
            Mustard and a Sunny Side Up Egg.
          </div>
          <div class="font-bold">RM23.00</div>
        </div>
      </div>

      <div class="flex mt-5">
        <div class="w-1/4">
          <img
            class="rounded-xl"
            src="https://myburgerlab.com/static/img/menu/products/img_beef_hangover.jpg"
            alt=""
          />
        </div>
        <div class="w-3/4 px-5">
          <h3 class="uppercase font-bold text-blue-900">Rosy Business</h3>
          <div class="py-2">
            Rosy business is a combination of Sweet and Savory. Beef patty topped with a
            Crispy Hash Brown covered with Rose Syrup.
          </div>
          <div class="font-bold">RM21.00</div>
        </div>
      </div>

      <div class="flex mt-5">
        <div class="w-1/4">
          <img
            class="rounded-xl"
            src="https://myburgerlab.com/static/img/menu/products/img_chicken_lab-burger.jpg"
            alt=""
          />
        </div>
        <div class="w-3/4 px-5">
          <h3 class="uppercase font-bold text-blue-900">Old Fashion</h3>
          <div class="py-2">
            Who will say no to a classic Cheeseburger that always hits the spot and makes
            you smile? Served with grilled beef / chicken patty.
          </div>
          <div class="font-bold">RM18.00</div>
        </div>
      </div>
    </div>

    <!-- footer row -->
    <div class="bg-gray-700 py-10 text-white mt-10">
      <div class="flex max-w-5xl mx-auto">
        <!-- column 1 -->
        <div class="w-1/3 pl-10">
          <h3 class="text-2xl mb-2">🍔 Houz Burger</h3>
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
