<script>
import AppContent from './components/AppContent.vue';
import AppHeader from './components/AppHeader.vue';
import axios from 'axios';

// import store
import { store } from './store';

export default {
    name: 'App',
    components: {
        AppHeader,
        AppContent,
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
    <AppContent />
    <main>

    </main>
</template>

<style lang="scss">
    @use './styles/partials/mixins' as *;
    @use './styles/partials/variables' as *;
    @use './styles/general.scss' as *;
</style>
