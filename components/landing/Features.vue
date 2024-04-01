<script setup>
const features = [
  {
    title: "Tech-Focused Solutions",
    description:
      "Explore innovative tech solutions to address environmental challenges.",
    icon: "bx:bxs-desktop",
  },
  {
    title: "Sustainable Practices",
    description:
      "Learn about sustainable practices and how they contribute to a healthier planet.",
    icon: "bx:bxs-window-alt",
  },
  {
    title: "Waste Reduction Strategies",
    description:
      "Discover effective strategies to reduce waste and minimize environmental impact.",
    icon: "bx:bxs-data",
  },
  {
    title: "Minimalism",
    description:
      "Embrace a lifestyle focused on simplicity and intentional living, reducing clutter and consumption.",
    icon: "bx:bxs-bot",
  },
  {
    title: "Zero Waste Lifestyle",
    description:
      "Adopt practices to minimize waste generation and promote recycling, composting, and reusability.",
    icon: "bx:bxs-bot",
  },
];
</script>

<template>
  <div class="mt-16 md:mt-0">
    <h2 class="text-4xl lg:text-5xl font-bold lg:tracking-tight">
      Empowering Change for a Sustainable Future
    </h2>
    <p class="text-lg mt-4 text-slate-600">
      Explore how technology and mindful living can create a positive impact on
      the environment and society.
    </p>
  </div>

  <div class="grid sm:grid-cols-2 md:grid-cols-3 mt-16 gap-16">
    <div v-for="item of features" class="flex gap-4 items-start">
      <div class="mt-1 bg-black rounded-full p-2 w-8 h-8 shrink-0">
        <Icon class="text-white" :name="item.icon" />
      </div>
      <div>
        <h3 class="font-semibold text-lg">{{ item.title }}</h3>
        <p class="text-slate-500 mt-2 leading-relaxed">
          {{ item.description }}
        </p>
      </div>
    </div>
  </div>
</template>
