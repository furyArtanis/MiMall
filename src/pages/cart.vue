<template>
  <order-header></order-header>
  cart
  <nav-footer></nav-footer>
</template>

<script>
import OrderHeader from "@/components/OrderHeader";
import NavFooter from "@/components/NavFooter";
export default {
  name: "index",
  components: {NavFooter, OrderHeader}
}
</script>

<style scoped>

</style>