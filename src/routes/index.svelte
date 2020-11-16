<svelte:head>
  <title>Projects</title>
</svelte:head>



<div class="container">
  <div class="row">
    <div class="item">
      <a href="/projects?id=1">
        <img  src="/images/Projects/project1/main.jpg" />
      </a>
    </div>
  </div>
  <div class="row">
    <div class="item">
      <a href="/projects?id=2">
        <img  src="/images/Projects/project1/main.jpg" />
      </a>
    </div>
    <div class="item">
      <img  src="/images/Projects/project2/main.jpg" />
    </div>
  </div>
  <div class="row">
    <div class="item">
      <img  src="/images/Projects/project3/main.jpg" />
    </div>
    <div class="item">
      <img  src="/images/Projects/project3/main.jpg" />
    </div>
    <div class="item">
      <img  src="/images/Projects/project3/main.jpg" />
    </div>
  </div>
    
</div>
<style>
  .container {
    display: flex;
    flex-direction: column;
  }

  img {
    width: 100%;
    object-fit: cover;
    flex: 1;
  }
  .row {
    display: flex;
    flex-direction: row;
    gap: 6px;
  }

  .item {
    flex: 1;
  }


</style>
