<template>
  <div>
    <AppTitle />
    <AppHero />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero,
  },
};
</script>
