<template>
    <app-header></app-header>
    <fylo-app />
    <app-footer />

</template>

<script>
import appHeader from './components/app-header.vue'
import fyloApp from './components/fylo-app.vue';
import appFooter from './components/app-footer.vue';

export default {
    components: {
        appHeader,
        fyloApp,
        appFooter
    }
}
</script>