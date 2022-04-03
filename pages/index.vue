<template>
<div>
  <div id="header" class="bg-[url('/hero-bg.jpg')] pl-20 pr-20">
    <div id="menu" class="grid grid-cols-2 pt-5 pb-5">
        <div id="menu-left">
          <img src="logo.png" class="w-[150px]" alt="">
        </div>
        <div id="menu-right">
          <div md:flex>
            <ul class="grid grid-cols-4 text-lg font-oswald text-white uppercase pt-5">
              <li>About Us</li>
              <li>Our Menu</li>
              <li>Locations</li>
              <li>Contact Us</li>
            </ul>
          </div>
        </div>
    </div>
    <div class="grid grid-cols-2 pb-20 pt-10">
      <img src="hero-burger.png" class="pr-8 mt-10" alt="" />
      <div>
        <h1 class="text-8xl text-white text-center font-lilita uppercase my-5">Classic Burger</h1>
        <h2 class="text-6xl text-white text-center font-lilita uppercase my-5">
            With Onion
        </h2>
        <p class="text-white font-roboto font-light text-center">
          Our signature burger now comes with onion and cheese.You can customize it to
          your likings. Freshly made to order, all in a brioche style bun.
        </p>
      </div>
    </div>
  </div>

  <div id="section-1" class="text-center bg-[url('/about.jpg')] pb-80 bg-cover">
      <h1 class="text-6xl uppercase font-oswald pt-20 px-24">
        The burger tastes better when you eat it with family
      </h1>
      <p class=" font-roboto font-light text-gray-500 text-center py-6 px-28">
        Spend quality time with your family and eat an
        affordable, nutritious and delicious meal together.
        Not all burgers are fast foods. All our burgers are handmade to
        orders for you and your family members to enjoy.
      </p>
      <button class="font-oswald uppercase bg-red-500 text-white text-center py-3 px-8 rounded-full">
        Explore Full Menu
      </button>
    </div>
    <p class="font-oswald text-center text-lg uppercase text-red-600 pt-40">Our Crazy Burgers</p>
  <div class="grid grid-cols-3 pt-50 pr-10 pl-10">
    <div class="crispy-chicken pl-10 pr-10">
      <img src="crispy-chicken.jpg">
      <p class="font-oswald text-center pt-5 pb-5">Crispy Chicken</p>
    </div>
    <div class="double-burger pl-10 pr-10">
      <img src="double-burger.jpg">
      <p class="font-oswald text-center pt-5 pb-5">Double Burger</p>
    </div>
    <div class="ultimate-bacon pl-10 pr-10">
      <img src="ultimate-bacon.jpg">
      <p class="font-oswald text-center pt-5 pb-5">Ultimate Bacon</p>
    </div>
  </div>
</div>
</template>
