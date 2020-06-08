<template>
  <div>
    <h1>About DadJokes</h1>
    <p>This is an app that displays corny Dad Jokes.</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "About The App",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny Dad Jokes."
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
</style>