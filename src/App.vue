<template>
  <div id="app">
    <ProductList />
  </div>
</template>

<script>
import ProductList from "./components/ProductList";
export default {
  name: "app",
  components: {
    ProductList
  }
};
</script>

<style scoped>
body {
  padding: 1rem;
}
</style>
