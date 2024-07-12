<script>
import AppHeader from './components/AppHeader.vue';

// import store
import { store } from './store';

export default {
  name: 'App',
  components: {
    AppHeader,
  },
  data() {
    return {
      store,
    }
  },
}
</script>

<template>
    <AppHeader />
</template>

<style lang="scss">
  @use './styles/partials/mixins' as *;
  @use './styles/partials/variables' as *;
  @use './styles/general.scss' as *;
</style>
