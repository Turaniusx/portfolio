<template>
  <main class="home">
    <Hero />
    <section class="section">
      <div class="section__stacks">
        <h3>HTML</h3>
        <h3>CSS</h3>
        <h3>JavaScript</h3>
        <h3>PHP</h3>
        <h3>Vue</h3>
        <h3>Laravel</h3>
      </div>
    </section>
  </main>
</template>

<script>
import Hero from "@/components/Hero.vue";

export default {
  components: {
    Hero,
  },
};
</script>
