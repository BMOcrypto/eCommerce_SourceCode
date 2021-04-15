<template>
  <div>
    <app-store-grid :data="dryblend" />
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
    ...mapGetters(["dryblend"]),
  },
};
</script>

<style lang="scss" scoped>
</style>