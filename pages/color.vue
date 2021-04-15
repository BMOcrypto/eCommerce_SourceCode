<template>
  <div>
    <app-store-grid :data="color" />
  </div>
</template>

<script>
import { mapGetters } from "vuex";
import AppStoreGrid from "~/components/AppStoreGrid.vue";

export default {
  components: {
    AppStoreGrid,
  },
  computed: {
    ...mapGetters(["color"]),
  },
};
</script>

<style lang="scss" scoped>
</style>