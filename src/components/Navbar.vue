<template>
  <nav data-aos="fade-down" data-aos-duration="1300" class="">
    <div class="max-width flex flex-wrap items-center justify-between">
      <h1 class="text-white font-bold text-xl">Sammy</h1>
      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm rounded-lg md:hidden text-white"
        aria-controls="navbar-default"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>

      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul
          class="font-medium flex items-center flex-col p-4 md:p-0 max-[767px]:bg-[#020015] mt-4 md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0"
        >
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-white text-sm font-bold md:p-0"
              >HOME</a
            >
          </li>

          <li class="max-[767px]:py-1">
            <a
              href="#"
              class="block py-2 px-3 text-white text-sm font-bold md:p-0"
              >ABOUT</a
            >
          </li>

          <li class="max-[767px]:py-1">
            <a
              href="#"
              class="block py-2 px-3 text-white text-sm font-bold md:p-0"
              >SERVICES</a
            >
          </li>

          <li class="max-[767px]:py-1">
            <a
              href="#"
              class="block py-2 px-3 text-white text-sm font-bold md:p-0"
              >PROJECTS</a
            >
          </li>

          <li class="max-[767px]:py-1">
            <a
              href="#"
              class="block py-2 px-3 text-white text-sm font-bold md:p-0"
              >PROJECTS</a
            >
          </li>

          <li class="max-[767px]:py-1">
            <a
              href=""
              class="bg-white text-purple text-sm font-extrabold block px-5 rounded-[64px] py-3"
              >Download Cv</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
