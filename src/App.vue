<script setup>
import { RouterView } from 'vue-router'
import SidebarMenu from './components/SidebarMenu.vue';

import FooterSection from './components/FooterSection.vue';


import { ref, onMounted, onUnmounted } from 'vue';

const isMobile = ref(window.innerWidth < 768);

// Function to update the `isMobile` variable based on the window width
const updateSize = () => {
  isMobile.value = window.innerWidth < 768;
};

// Lifecycle hook to add a resize event listener when the component is mounted
onMounted(() => {
  window.addEventListener('resize', updateSize);
});

// Lifecycle hook to remove the resize event listener when the component is unmounted
onUnmounted(() => {
  window.removeEventListener('resize', updateSize);
});

</script>

<template>

  <div id="app" class="app-container">
    <SidebarMenu v-if="!isMobile"/>
    <RouterView />
  </div>
  <FooterSection />

</template>

<style>

.app-container {
  display: flex;
}

/* header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
} */
</style>
