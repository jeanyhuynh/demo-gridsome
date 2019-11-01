<template>
  <Layout>
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/favicon.png" width="135" />

    <h1 class="test">Hello, world!</h1>

    <p class="test">
      Lorem ipsum dolor sit amet,
      <span class="test1">hello</span> consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
    </p>
    <ul>
      <li>
        <g-link to="/blog-html/blog-post-one">Blog post one</g-link>
      </li>
      <li>
        <g-link to="/blog-html/blog-post-two">Blog post two</g-link>
      </li>
    </ul>
    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!"
  }
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
