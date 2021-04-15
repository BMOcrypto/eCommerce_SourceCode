<template>
  <section>
    <ul>
      <li><a href="">About</a></li>
      <li><a href="">Company</a></li>
      <li><a href="">Locations</a></li>
      <li><a href="">Contact Us</a></li>
       <li><a href="">Hours</a></li>
    </ul>
    <ul>
      <li>Twitter</li>
      <li>Facebook</li>
      <li>Instagram</li>
      <li>LinkedIn</li>
    </ul>
    <ul>
      <h4>Sign up for our sweet newsletter:</h4>
      <input type="text" />
    </ul>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
section {
  width: 100%;
  padding: 40px 0;
  display: grid;
  grid-template-columns: repeat(4, 2fr);
  border-top: 5px solid #f2ad1c;
  margin-top: 25px;
}

ul {
  list-style: none;
  padding-left: 0;
}

input {
  width: 100%;
}

@media screen and (min-width: 850px) {
  section {
    padding: 40px !important;
  }
}
</style>