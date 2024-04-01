<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8">
    <div class="p-24 md:order-1 hidden md:block">
      <img
        class="rounded-full transition-transform transform hover:scale-125"
        src="~/assets/img/pp1.webp"
        alt="Starship starts the engine"
        loading="eager"
        format="avif"
        width="512"
        height="512"
      />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight">
        Exploring Tech, Creativity, and Sustainability
      </h1>
      <h2
        class="text-3xl lg:text-4xl xl:text-5xl font-semibold lg:tracking-tight text-gray-700 mt-4"
      >
        Hi! I'm Ork
      </h2>
      <p class="text-lg mt-4 text-slate-600 max-w-xl">
        I'm a software engineer with a love for the environment, technology,
        languages, and the arts. Through this blog, I share my passions and
        work, from coding to capturing moments behind the camera. Join me as I
        explore the intersections of tech, photography, and sustainability, and
        let's embark on this journey together.
      </p>

      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink
          href="https://github.com/Gr33nW33n/nuxtship-template"
          target="_blank"
          rel="noopener"
          >Contact Me</LandingLink
        >
        <LandingLink
          size="lg"
          styleName="outline"
          rel="noopener"
          href="https://github.com/Gr33nW33n/nuxtship-template"
          target="_blank"
          >About me</LandingLink
        >
      </div>
    </div>
  </main>
</template>
