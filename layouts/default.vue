<template>
  <div>
    <Navigation />
    <div class="content">
      <nuxt />
    </div>
  </div>
</template>

<script>
import Navigation from "../components/Navigation";

export default {
  components: {
    Navigation
  }
};
</script>

<style>
* {
  box-sizing: border-box;
  color: whitesmoke;
}

body {
  background: #2d3436;
  color: whitesmoke;
  padding-top: 0;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}

.content {
  padding: 2rem;
}
</style>
