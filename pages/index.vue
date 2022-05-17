<template>
  <div>
    <div id="header" class="bg-[url('/hero-bg.jpg')] px-20">
      <div id="menu" class="grid grid-cols-2 py-5">
        <div id="menu-left">
          <img src="logo.png" class="w-[150px]" alt="" />
        </div>
        <div id="menu-right">
          <ul class="grid grid-cols-4 text-lg font-oswald text-white uppercase pt-5">
            <li>About Us</li>
            <li>Our Menu</li>
            <li>Locations</li>
            <li>Contacts</li>
          </ul>
        </div>
      </div>
      <div class="grid grid-cols-2 pb-20 pt-10">
        <img src="hero-burger.png" class="pr-8 mt-10" alt="" />
        <div>
          <h1 class="text-8xl text-white text-center font-lilita uppercase">
            New Property In Town
          </h1>
          <h2 class="text-6xl text-white text-center font-lilita uppercase my-5">
            Luxury Condo
          </h2>
          <p class="text-white font-roboto font-light text-center">
            Get the latest property in KL from luxury to the cheapest property in town
          </p>
        </div>
      </div>
    </div>
    <div id="section-1" class="text-center bg-[url('/about.jpg')] pb-60 bg-cover">
      <h1 class="text-6xl uppercase font-oswald text-center pt-20 px-24">
        Property in KL is booming
      </h1>
      <p class="font-roboto font-light text-gray-500 text-center text-lg py-6 px-28">
        Thinking when is the right time to invest in property.Now is the time check out
        the lastest property in town
      </p>
      <button class="font-oswald uppercase bg-red-500 text-white py-3 px-8">
        Explore Property
      </button>
    </div>
    <div id="section-3" class="text-center">
      <h2 class="text-6xl font-oswald text-red-500 uppercase font-medium pt-20">
        Property Listing
      </h2>
      <p class="text-gray-500 font-light text-xl my-10 px-20">
        If you are looking to latest property in KL for Investment or Ownstay
      </p>
      <div class="grid grid-cols-2 px-40 gap-5">
        <div id="left-item-column">
          <Item
            image="crispy-chicken.jpg"
            title="Property In Kuala Lumpur"
            description="get the cheapest property in town"
            price="RM300,000"
          /><Item
            image="crispy-chicken.jpg"
            title="Property In Petaling Jaya"
            description="get the cheapest property in town"
            price="RM200,000"
          />
        </div>
        <div id="right-item-column">
          <Item
            image="crispy-chicken.jpg"
            title="Property In Johor Bahru"
            description="get the cheapest property in town"
            price="RM200,000"
          /><Item
            image="crispy-chicken.jpg"
            title="Property In Singapore"
            description="get the cheapest property in town"
            price="RM1,000,000"
          />
        </div>
      </div>
    </div>
  </div>
</template>
