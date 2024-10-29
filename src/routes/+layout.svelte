<script>
  export let title = "App name";
</script>
<svelte:head>
  <title>{title}</title>
</svelte:head>

<main>
  <header>
  </header>
  <section class="container">
    <slot></slot>
  </section>
  <footer>
    <p>© 2021 Your Name</p>
  </footer>
</main>

<style scoped>
</style>