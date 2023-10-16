<template>
  <div class="static">
    <div ref="hero">
      <!-- navigation -->
      <div class="absolute flex text-white">
        <!-- navbrand -->
        <a href="/" class="py-10 px-20">
          <div
            class="brand shadow-lg shadow-pink-500/50 font-bold text-6xl px-4 pt-2 pb-5"
          >
            KA.D
          </div>
        </a>

        <ul class="flex font-mono py-16 pl-96">
          <li class="text-center text-2xl cursor-pointer mx-10 nav-item pb-1">
            home
          </li>
          <li class="text-center text-2xl cursor-pointer mx-10">about</li>
          <li class="text-center text-2xl cursor-pointer mx-10">projects</li>
        </ul>
      </div>
      <!-- end navigation block -->

      <!-- hero page title -->
      <div class="absolute font-mono text-white top-64 left-40">
        <label class="text-xl">Hi, my name is </label>
        <label class="text-3xl">Kim Ariel N. Deqilla </label>
        <br />
        <!-- position -->
        <div class="font-mono text-8xl pt-8 text-shadow">
          Full Stack <br />
          Web Developer
        </div>
      </div>

      <div class="absolute right-10 top-11 w-64 h-64 bg-pink-950 eclipse"></div>

      <div
        class="absolute right-60 top-60 w-44 h-44 bg-green-950 eclipse"
      ></div>

      <div
        class="absolute right-96 top-96 w-28 h-28 bg-amber-200 eclipse"
      ></div>

      <div ref="hero" class="h-screen bg-neutral-900">
        <img
          class="absolute drop-shadow-xl right-24 bottom-0"
          src="../assets/img/me2.png"
          alt=""
        />
      </div>
    </div>
    <div ref="about" class="h-screen bg-neutral-600"></div>
  </div>
</template>
<script></script>
<style scoped>
.nav-item {
  border-bottom: 5px solid #74113a;
}

.brand {
  border-top: 1px solid #006017;
  border-right: 1px solid #006017;
  border-bottom: 1px solid #006017;
  border-left: 1px solid #006017;
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
