<template>
  <the-header title="Remember Me"></the-header>
  <the-resources></the-resources>
</template>

<script>
import TheHeader from "./components/layouts/TheHeader";
import TheResources from "./components/learing-resources/TheResources";

export default {
  components: {
    TheHeader,
    TheResources,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
}
</style>
