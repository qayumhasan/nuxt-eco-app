<template>
  <div>
    <HeaderComponent />
    <SearchComponent />
    <navbarComponent />
    <nuxt />
    <footerComponent />
    <CartComponent />
  </div>
</template>
<script>
import footerComponent from "../components/inc/footer.vue";
import CartComponent from "../components/carts/cart.vue";
import HeaderComponent from "../components/inc/headerComponent.vue";
import SearchComponent from "../components/inc/searchComponent.vue";
import navbarComponent from "../components/inc/navbarComponent.vue";
export default {
  components: {
    footerComponent,
    CartComponent,
    HeaderComponent,
    SearchComponent,
    navbarComponent,
  },
};
</script>
