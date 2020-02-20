<template>
  <div class="instagram">
    <h1>
      {{ pageTitle }}
    </h1>
  </div>
</template>

<script>
export default {
  name: 'Instagram',
  data() {
    return {
      pageTitle: 'Vue-insta test',
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
  .instagram {

  }
</style>
