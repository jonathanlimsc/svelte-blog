<style>
  figure {
    float: right;
    margin: -3em -7em 2em 2em;
    max-width: 400px;
  }

  figure img {
    border-radius: 8px;
  }

  @media (max-width: 1020px) {
    figure {
      float: none;
      margin: 0 auto 2em;
    }
  }
</style>

<svelte:head>
  <title>About</title>
</svelte:head>

<div class="container">
  <h1>About</h1>
  <figure>
    <img src='rsz_florian-klauer-489-unsplash.jpg' alt='A vintage typewriter.'>
    <figcaption>Photo by <a href="https://unsplash.com/@florianklauer" target="_blank">Florian Klauer</a> on Unsplash</figcaption>
  </figure>
  <p>Data scientist and machine learning engineer</p>
  <p>Passionate about building data-driven products.</p>
  <p>In my free time I like to think about space and consciousness.</p>
</div>
