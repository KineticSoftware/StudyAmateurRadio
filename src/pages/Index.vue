<template>
  <Layout>
    <section id="container-centre" class="column centre flex-1">
      <h1 class="page-title">Welcome to Study Amateur Radio!</h1>
      <div class="content">
        <!-- Learn how to use images here: https://gridsome.org/docs/images -->
        <g-image alt="Example image" src="~/favicon.png" width="135" />

        <h1>Hello and QSL!</h1>

        <p>
          Would you like to get started with getting your Amateur Radio (HAM) license but just don't know where to begin?
        </p>

        <p class="home-links">
          <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
          <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
          <a href="./testing">Finding A Test Location</a>
          <a href="./resources">Online Resources</a>
          <a href="./plan">A Sample Study Plan</a>
        </p>
      </div>
    </section>
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
