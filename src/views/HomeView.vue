<script setup>
import HeaderSection from '../components/HeaderSection.vue';
import SigaaIntroduction from '../components/SigaaIntroduction.vue';
import MapSection from '../components/MapSection.vue';
import ContactsSection from '../components/ContactsSection.vue';
import SocialNetworks from '../components/SocialNetworks.vue';
import TipsSection from '../components/TipsSection.vue';
</script>

<template>
  <main>
    <HeaderSection />
    <SigaaIntroduction />
    <MapSection />
    <ContactsSection />
    <SocialNetworks />
    <TipsSection />
  </main>
</template>

<style>

main {
  margin-left: 50px;
  width: 100%;
}

</style>