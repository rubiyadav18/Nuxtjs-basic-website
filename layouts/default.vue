<template>
  <div>
    <AppHeader />
    <Nuxt />
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "~/components/inc/AppHeader.vue";
import AppFooter from "~/components/inc/AppFooter.vue";
import AppHeader2 from "~/components/inc/AppHeader2.vue";
export default {
  name: "default",
  components: {
    AppHeader,
    AppFooter,
    AppHeader2,
  },
  // mounted() {
  //   this.$store.state.counter = 10;
  // },
};
</script>
