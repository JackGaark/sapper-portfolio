<script>
  // export let segment
</script>

<style>
  /* main {
    height: 100vh;
    position: relative;
    padding: 0;
    margin: 0 auto;
    box-sizing: border-box;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    max-width: 100vw;
  } */
  header {
    position: fixed;
    width: 100vw;
    height: 50px;
    padding: 1em 2em;
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

  <nav><a href="/instagram">Instagram</a></nav>
</header>
<main>
  <slot />
</main>
