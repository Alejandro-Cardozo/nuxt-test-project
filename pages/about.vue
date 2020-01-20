<template>
  <div>
    <h1>about us</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione sit asperiores quidem facere hic ea quis dolore totam voluptates animi at aliquam doloribus, porro qui tenetur eligendi atque nesciunt. Sequi.</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "First Nuxt App | About",
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