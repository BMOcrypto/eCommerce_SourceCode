<template>
  <footer>
    <section class="callout">
      <h2>"From start through finish.... thats the Flavorman promise."</h2>
      <p>- The Flavorman</p>
    </section>
    <app-footer-links />
    <div class="lowerfooter">
      <p>Flavorman 2021</p>
    </div>
  </footer>
</template>

<script>
import AppFooterLinks from "~/components/AppFooterLinks.vue";

export default {
  components: {
    AppFooterLinks,
  },
};
</script>

<style lang="scss" scoped>
.callout {
  width: 100%;
  height: 280px;
  background: url("/callout.jpg") center center no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: black;
  h2 {
    padding: 0 30px;
    text-align: center;
  }
}
.lowerfooter {
  background: #52acf4;
  width: 100%;
  color: white;
  text-align: center;
  height: 25px;
}
a,
a:visited,
a:active {
  color: #c4c3ec;
  font-weight: bold;
}
</style>