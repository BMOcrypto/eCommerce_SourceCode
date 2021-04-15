<template>
  <div>
    <app-textlockup />
    <app-sales-boxes />
    <app-textlockup>
      <template v-slot:new></template>
      <template v-slot:sale></template>
      <template v-slot:collection></template>
      <template v-slot:details></template>
    </app-textlockup>
    <app-featured-products />
  </div>
</template>

<script>
import AppTextlockup from "~/components/AppTextlockup.vue";
import AppSalesBoxes from "~/components/AppSalesBoxes.vue";
import AppFeaturedProducts from "~/components/AppFeaturedProducts.vue";

export default {
  components: {
    AppTextlockup,
    AppSalesBoxes,
    AppFeaturedProducts,
  },
};
</script>

<style>
.test {
  margin: 3vh;
}

main {
  width: 75vw;
}
</style>
