<template>
  <div class="max-w-[1150px] mx-auto py-5 max-[1209px]:px-12">
    <Navbar></Navbar>

    <!-- HERO SECTION -->
    <main class="max-width">
      <div
        class="min-[821px]:mt-16 flex max-[821px]:flex-col gap-36"
        data-aos="fade-right"
        data-aos-duration="1300"
      >
        <div class="">
          <h1
            class="text-white text-[70px] center max-[821px]:text-[50px] max-[500px]:text-[35px] line font-extrabold"
          >
            SAMUEL ODILI
            <span
              class="text-purple min-[821px]:block max-[821px]:hidden font-extrabold"
            >
              FRONT-END <br />
              DEVELOPER</span
            >
            <span
              class="text-purple min-[821px]:hidden max-[821px]:block font-extrabold"
            >
              FRONT-END DEVELOPER</span
            >
          </h1>
          <img
            src="../public/images/line.png"
            class="w-[371px] max-[500px]:w-[200px] block max-[821px]:mx-auto"
          />

          <div class="flex hire gap-12 items-center">
            <a
              href=""
              class="bg-white text-purple text-sm font-extrabold block px-5 rounded-[64px] py-3"
              >HIRE ME NOW</a
            >

            <p class="text-white text-[15px] px-8 max-[821px]:text-center">
              Hey there! I'm Samuel Odili, a Frontend Developer who loves <br />
              to build products that are user-friendly, engaging, and help
              <br />
              businesses and people grow.
            </p>
          </div>
        </div>

        <div data-aos="fade-left" data-aos-duration="1300" class="img-hide">
          <img
            src="../public/images/samuel-photo.png"
            class="w-[260px] ax-[821px]:hidden"
          />
        </div>
      </div>

      <div class="line2"></div>
    </main>

    <!-- ABOUT ME -->
    <div class="max-width mt-4">
      <div>
        <h3 class="text-[#62606F] font-extrabold text-5xl sub-head">
          ABOUT ME
        </h3>

        <div class="flex flex-col gap-1">
          <div
            data-aos="fade-right"
            data-aos-duration="1000"
            data-aos-once="true"
            class="flex flex-col"
          >
            <p class="text-white pt-8 text-xl">
              My journey into software development began with a curiosity about
              the intricate workings behind captivating interfaces. As a web
              designer and copywriter constructing websites for software
              companies, I found myself drawn to the magic happening beneath the
              surface. I wanted to understand the alchemy that transforms
              designs into engaging user experiences, leading me to delve into
              the realm of software development.
            </p>
          </div>

          <div
            data-aos="fade-right"
            data-aos-duration="1300"
            data-aos-once="true"
            class="flex flex-col"
          >
            <p class="text-white pt-8 text-xl">
              From those initial sparks of curiosity, my path has taken me on an
              exhilarating journey. I've had the privilege of collaborating with
              diverse entities, ranging from NGOs to nimble startups and
              medium-sized corporations. Each encounter has enriched my
              understanding and honed my skills, guiding me towards my current
              focus.
            </p>
          </div>

          <div
            data-aos="fade-right"
            data-aos-duration="1600"
            data-aos-once="true"
            class="flex flex-col"
          >
            <p class="text-white pt-8 text-xl">
              Today, my passion lies in crafting innovative, cost-effective
              products that empower individuals, businesses, and communities. I
              believe in harnessing the potential of technology and innovation
              to unlock new possibilities, enabling people to achieve more in
              every facet of their lives.
            </p>
          </div>
        </div>
      </div>

      <div class="line3"></div>
    </div>

    <!-- PROJECTS -->
    <h3 class="text-[#62606F] font-extrabold text-5xl sub-head mt-8">
      Projects
    </h3>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-16 mt-8 md:mt-16">
      <!-- PROJECT1 -->
      <div>
        <a href="https://cloud.bizbudd.ai/" target="_blank">
          <div class="flex items-center justify-center">
            <swiper :navigation="true" :modules="modules" class="mySwiper">
              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-cloud.bizbudd.ai-1.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>
              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-cloud.bizbudd.ai-2.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>
              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-cloud.bizbudd.ai-3.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>
              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-cloud.bizbudd.ai-4.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>
            </swiper>
          </div>
        </a>
        <span class="px-10 max-[401px]:px-1 block">
          <h4 class="text-[21px] text-white font-bold text-center">
            Bizbudd AI
          </h4>
          <p class="text-center">
            Bizbudd is a cutting-edge SaaS web app that leverages AI for
            business insights harnessing the power of multiple AI engines.
          </p>
        </span>
        <div class="flex flex-wrap justify-center gap-3 mt-3">
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Tailwind
          </p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">PHP</p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">Vue</p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Typescript
          </p>
        </div>
      </div>

      <!-- PROJECT2 -->
      <div>
        <a href="https://app.iceleraite.io/" target="_blank">
          <div class="flex items-center justify-center">
            <swiper :navigation="true" :modules="modules" class="mySwiper">
              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-app.iceleraite.io-1.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-app.iceleraite.io-2.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-app.iceleraite.io-3.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-app.iceleraite.io-4.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>
            </swiper>
          </div>
        </a>
        <span class="px-10 max-[401px]:px-1 block">
          <h4 class="text-[21px] text-white font-bold text-center">
            Iceleraite
          </h4>
          <p class="text-center">
            The project aimed to develop an AI-powered app to accelerate the
            growth of 13 ready-to-profit agencies
          </p>
        </span>
        <div class="flex flex-wrap justify-center gap-3 mt-3">
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Tailwind
          </p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">PHP</p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">Vue</p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Typescript
          </p>
        </div>
      </div>

      <!-- PROJECT3 -->
      <div>
        <a href="https://www.smartbloks.ai/" target="_blank">
          <div class="flex items-center justify-center">
            <swiper :navigation="true" :modules="modules" class="mySwiper">
              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-smartbloks.ai-1.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-smartbloks.ai-2.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-smartbloks.ai-3.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-smartbloks.ai-4.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>
            </swiper>
          </div>
        </a>
        <span class="px-10 max-[401px]:px-1 block">
          <h4 class="text-[21px] text-white font-bold text-center">
            Smartbloks
          </h4>
          <p class="text-center">
            Website for Smartbloks a platform that empowers users to build,
            learn, and grow with innovative AI-powered tools and resources."
          </p>
        </span>
        <div class="flex flex-wrap justify-center gap-3 mt-3">
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Tailwind
          </p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Typescript
          </p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">Vue</p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">Astro</p>
        </div>
      </div>

      <!-- PROJECT4 -->
      <div id="projects">
        <a href="https://www.smartbloks.ai/" target="_blank">
          <div class="flex items-center justify-center">
            <swiper :navigation="true" :modules="modules" class="mySwiper">
              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-bizbudd.ai-1.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-bizbudd.ai-2.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-bizbudd.ai-3.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>

              <swiper-slide>
                <img
                  src="../public/images/Macbook-Air-bizbudd.ai-4.png"
                  alt=""
                  class="p-4 test"
                />
              </swiper-slide>
            </swiper>
          </div>
        </a>
        <span class="px-10 max-[401px]:px-1 block">
          <h4 class="text-[21px] text-white font-bold text-center">
            Bizbudd-Landingpage
          </h4>
          <p class="text-center">
            A landing page for bizbudd a web app that leverages AI for business
            insights harnessing the power of multiple AI engines
          </p>
        </span>
        <div class="flex flex-wrap justify-center gap-3 mt-3">
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Wordpress
          </p>
          <p class="bg-[#62606F] text-white rounded-full text-sm px-4">
            Elementor
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<!-- <script setup>
import Navbar from './components/Navbar.vue';
</script> -->

<script>
import Navbar from './components/Navbar.vue';
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from 'swiper/vue';

// Import Swiper styles
import 'swiper/css';

import 'swiper/css/navigation';

import './assets/main.css';

// import required modules
import { Navigation } from 'swiper/modules';

export default {
  components: {
    Swiper,
    SwiperSlide,
    Navbar,
  },
  setup() {
    return {
      modules: [Navigation],
    };
  },
};
</script>

<style scoped>
/* .swiper {
  width: 600px;
  height: 300px;
} */
</style>
