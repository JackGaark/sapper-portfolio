<script>
  // export let segment
</script>

<style>
  main {
    position: relative;
    max-width: 56em;
    padding: 0em 2em 2em;
    margin: 0 auto;
    box-sizing: border-box;
  }
  header {
    position: relative;
    max-width: 56em;
    padding: 1em 2em;
    margin: 0 auto;
    box-sizing: border-box;
    display: flex;
    justify-content: space-between;
    font-family: OppositMedium;
  }
</style>

<header>
  <nav>
    <a href="/">Projects</a>
    <a href="/about">About</a>
    <a href="/contact">Contact</a>
  </nav>

  <div class="logo">Superbonjour</div>

  <nav>
    <a href="/instagram">Instagram</a>
  </nav>

</header>
<main>
  <slot></slot>
</main>
