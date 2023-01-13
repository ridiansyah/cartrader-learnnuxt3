<template>
  <div>
    <!-- Navbar -->
    <header
      class="sticky top-0 z-50 flex justify-between items-center space-x-1 border-b bg-white p-4 shadow-md"
    >
      <a class="text-3xl font-mono" href="">cartrader</a>
    </header>
    <!-- Navbar -->
    <!-- Home Hero -->
    <div
      class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url(https://www.autocar.co.uk/sites/autocar.co.uk/files/styles/gallery_slide/public/images/car-reviews/first-drives/legacy/1-mini-electric-2020-uk-fd-hero-front.jpg?itok=OFilSlQ3)]"
    >
      <div class="z-10 absolute w-full h-full flex justify-center items-center">
        <div class="text-center w-1/2">
          <h1 class="text-8xl font-serif mb-10 text-white">Find your drive</h1>
          <!-- Home Search Bar -->
          <div
            class="font-serif w-[1000px] text-2xl rounded-full bg-white flex justify-between overflow-hidden drop-shadow-2xl mx-auto"
          >
            <input
              type="text"
              class="py-3 px-5 w-full text-2xl rounded-full focus:outline-none"
              placeholder="Search by City..."
            />
            <button class="bg-sky-500 px-10 text-white">Search</button>
          </div>
          <!-- Home Search Bar -->
        </div>
      </div>
      <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
    </div>
    <!-- Home Hero -->
  </div>
</template>
