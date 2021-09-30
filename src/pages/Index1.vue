<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="me" src="~/assets/MeThumbs.jpg" width="170" />

    <h1>Welcome to my digital garden</h1>

    <p>
      Simply put the intention of this site is to bring my Obsidian notes alive!
    </p>

    <p class="home-links">
      <a href="https://joshafairhead.com" target="_blank" rel="noopener">Website</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
