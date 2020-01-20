<template>
  <div>
    <p>{{ identificator }}. {{ name }}</p>
  </div>
</template>

<script>
export default {
  name: "Post",
  props: ["identificator", "name"]
};
</script>
