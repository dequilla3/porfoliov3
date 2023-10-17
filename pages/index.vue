<template>
  <div class="static">
    <div ref="hero">
      <!-- navigation -->
      <div class="absolute flex text-white">
        <!-- navbrand -->
        <a href="/" class="lg:py-10 lg:px-20">
          <div
            class="shadow-lg shadow-pink-500/50 font-bold lg:text-6xl text-4xl px-8 py-4"
          >
            KA.D
          </div>
        </a>

        <ul class="hidden lg:flex lg:float-right font-mono py-16">
          <li class="text-center text-2xl cursor-pointer mx-10 nav-item pb-1">
            home
          </li>
          <li class="text-center text-2xl cursor-pointer mx-10">about</li>
          <li class="text-center text-2xl cursor-pointer mx-10">projects</li>
        </ul>
      </div>

      <div class="lg:h-screen bg-neutral-900">
        <!-- hero page title -->
        <div
          class="pt-32 pl-5 lg:p-0 lg:absolute font-mono text-white lg:top-1/3 lg:left-40"
        >
          <label class="lg:text-xl text-sm">Hi, my name is </label>
          <br />
          <label class="lg:text-3xl text-xl">Kim Ariel N. Deqilla </label>
          <br />
          <!-- position -->
          <div class="font-mono lg:text-8xl text-4xl lg:pt-8 text-shadow">
            Full Stack <br />
            Web Developer
          </div>
        </div>
        <div
          class="absolute right-10 top-11 lg:w-64 lg:h-64 w-52 h-52 bg-pink-950 eclipse"
        ></div>

        <div
          class="absolute right-60 top-60 lg:w-44 lg:h-44 w-36 h-36 bg-green-950 eclipse"
        ></div>

        <div
          class="absolute right-96 top-96 w-28 h-28 bg-amber-200 eclipse"
        ></div>
        <img
          class="lg:absolute lg:min-h-screen drop-shadow-xl right-24 bottom-0"
          src="../assets/img/me2.png"
          alt=""
        />
      </div>
    </div>
  </div>
</template>
<script></script>
<style scoped>
.nav-item {
  border-bottom: 5px solid #74113a;
}

.eclipse {
  flex-shrink: 0;
  border-radius: 311px;
  opacity: 0.3;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}

.text-shadow {
  text-shadow: 3px 2px 19px rgba(41, 111, 17, 0.96);
}
</style>
