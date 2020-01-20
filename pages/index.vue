<template>
  <div>
    <h1>Welcome to my first Nuxt App</h1>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "First Nuxt App | Home",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "this is a simple website about posts"
        }
      ],
      htmlAttrs: {
        lang: "en"
      }
    };
  }
};
</script>