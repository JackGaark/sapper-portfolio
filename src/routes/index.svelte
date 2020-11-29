<style global>
  .parallax {
    /* The image used */
    background-image: url("/images/Projects/project1/main.jpg");

    /* Set a specific height */
    height: 100vh;

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  .parallax.image_1 {
    background-image: url("/images/Projects/project1/2.jpg");
  }

  .parallax.image_2 {
    background-image: url("/images/Projects/project3/3.jpg");
  }
  .container {
    display: flex;
    flex-direction: column;
    width: 100vw;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }

  /* img {
    height: 100vh;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    flex: 1;
    width: 100vw;
  } */
  .row {
    display: flex;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100vw;
    height: 100vh;
    flex-direction: row;
    gap: 6px;
  }

  /* .item {
    flex: 1;
    max-width: 100vw;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  } */
</style>

<svelte:head>
  <title>Projects</title>
</svelte:head>

<div class="parallax" />
<div class="parallax image_1" />
<div class="parallax image_2" />
