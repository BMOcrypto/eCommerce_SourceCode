<template>
  <div>
    <app-store-grid :data="flavor" />
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
    ...mapGetters(["flavor"]),
  },
};
</script>

<style lang="scss" scoped>
</style>