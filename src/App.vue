<template>
  <div>
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: "App",
  data: () => {
    return {
      message: "Hello Vue",
    };
  },
};
</script>

<style lang="scss">
$text: #1d1d1d;

* {
  font-family: Arial, Helvetica, sans-serif;
  color: $text;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

h1 {
  text-align: center;
}
</style>
