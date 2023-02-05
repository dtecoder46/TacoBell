<script>
  import logo from './assets/Taco.png'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <img src={logo} alt="Svelte Logo" />
  <h1>Taco Bell has not found its new janitor.</h1>

  <Counter />

  <p>
    Click if you agree.
  </p>
</main>

<style>
  :root {
    font-family: 'Courier New', monospace;
    font-weight: 900;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
    font-weight: bold;
  }

  img {
    height: 16rem;
    width: 16rem;
  }

  h1 {
    color: black;
    text-transform: uppercase;
    font-size: 48px;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
    font-weight: bold;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }

    p {
      max-width: none;
    }
  }
</style>
