<template>
  <div class="relative isolate overflow-hidden bg-black pt-6 text-white">
    <svg
      id="Windframe_-3HAD1r_84" xmlns="http://www.w3.org/2000/svg"
      class="[mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)] absolute inset-0 h-full w-full opacity-40 -z-10"
    >
      <defs>
        <pattern
          id="b-streaming-template" patternunits="userSpaceOnUse" width="40" height="40"
          patterntransform="scale(12)
      rotate(0)"
        >
          <rect x="0" y="0" width="100%" height="100%" />
          <path
            d="M15 5h10v30H15zM35-5V5H5V-5zM35
      35v10H5V35zM35-15h10v30H35zM55 15v10H25V15zM15 15v10h-30V15zM35 25h10v30H35zM-5 25H5v30H-5zM-5-15H5v30H-5z"
            stroke-width="0.1" class="stroke-white" fill="none"
          />
        </pattern>
      </defs>
      <rect width="800%" height="800%" transform="translate(0,0)" fill="url(#b-streaming-template)" />
    </svg>
    <header class="absolute inset-x-0 top-0 z-50">
      <nav aria-label="Global" class="mx-auto max-w-screen-2xl flex items-center justify-between p-6">
        <div class="flex lg:flex-1">
          <a href="#" class="p-1.5 -m-1.5">
            <span class="sr-only">21 Pixeloids</span>
            <img
              src="https://res.cloudinary.com/speedwares/image/upload/v1659357654/windframe-logo-main_1_lbk3tr.png"
              alt="" class="h-8 w-auto"
            >
          </a>
        </div>
        <div class="flex lg:hidden">
          <button
            fontfamily="Arial" type="button"
            class="mobile-menu-button relative z-[100] inline-flex items-center justify-center rounded-md p-2.5 text-gray-200 -m-2.5"
          >
            <span class="sr-only">Open main menu</span>
            <span class="h-8 w-auto inline-flex items-center justify-center">
              <svg
                class="h-full w-full" fill="none" viewbox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75
                12h16.5m-16.5 5.25h16.5"
                />
              </svg>
            </span>
          </button>
        </div>
        <div class="hidden lg:flex lg:items-center lg:gap-x-12">
          <a href="#" lineheight="6" class="text-sm text-white font-semibold">Features</a>
          <a href="#" lineheight="6" class="text-sm text-white font-semibold">Blog</a>
          <a href="#" lineheight="6" class="text-sm text-white font-semibold">FAQs</a>
          <a href="#" lineheight="6" class="text-sm text-white font-semibold">About us</a>
          <a
            href="tel:917338332079" lineheight="6"
            class="rounded-md bg-[#171718] px-6 py-2.5 text-sm text-white font-semibold"
          >
            Call Now
            <span aria-hidden>→</span>
          </a>
        </div>
      </nav>
      <div role="dialog" aria-modal class="mobile-menu hidden">
        <div class="fixed inset-0 z-50" />
        <div
          class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-black px-10 py-6 text-white sm:max-w-sm sm:ring-1 sm:ring-gray-900/10"
        >
          <div class="flex items-center justify-between">
            <a href="#" class="p-1.5 -m-1.5">
              <span class="sr-only">21 Pixeloids</span>
              <nuxt-img
                src="https://res.cloudinary.com/speedwares/image/upload/v1659284687/windframe-logo-main_daes7r.png"
                alt="Logo of 21 Pixeloids" class="h-8 w-auto"
              />
            </a>
          </div>
          <div class="mt-6 flow-root">
            <div class="-my-6 divide-y divide-gray-500/10">
              <div class="py-6 space-y-2">
                <a
                  href="#" lineheight="7"
                  class="block rounded-lg px-3 py-2 text-xl text-white font-bold -mx-3 hover:bg-gray-800"
                >Features</a>
                <a
                  href="#" lineheight="7"
                  class="block rounded-lg px-3 py-2 text-xl text-white font-bold -mx-3 hover:bg-gray-800"
                >Blog</a>
                <a
                  href="#" lineheight="7"
                  class="block rounded-lg px-3 py-2 text-xl text-white font-bold -mx-3 hover:bg-gray-800"
                >FAQs</a>
                <a
                  href="#" lineheight="7"
                  class="block rounded-lg px-3 py-2 text-xl text-white font-bold -mx-3 hover:bg-gray-800"
                >About
                  us</a>
                <a
                  href="tel:+917338332079" lineheight="7"
                  class="block rounded-lg px-3 py-2.5 text-xl text-white font-bold -mx-3 hover:bg-gray-800"
                >Call Now</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
    <section class="mx-auto mt-20 max-w-2xl w-full text-center md:mt-16 space-y-10">
      <p class="text-justify px-12 md:px-0 text-4xl font-bold tracking-tight lg:text-6xl">
        21 Pixeloids
        <br>
      </p>
      <div class="space-y-3" />
    </section>
    <div class="mx-auto mt-10 flow-root max-w-4xl w-full" />
  </div>
</template>
