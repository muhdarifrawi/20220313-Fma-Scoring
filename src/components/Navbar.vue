<template>
  <nav class="navbar fixed-top navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">FMA Scoring</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarText"
        aria-controls="navbarText"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <span class="nav-link navbar-toggler my-2" aria-current="page" href="#"
              data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation"
            >
              Administration and Scoring
            </span>
            <span class="nav-link navbar-toggler my-2" aria-current="page" href="#"
              data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation"
            >
              Intervention
            </span>
            <span class="nav-link navbar-toggler my-2" aria-current="page" href="#"
              data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation"
            >
              Brochures
            </span>
          </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  name: "Navbar",
};
</script>
<style>
  .nav-link{
    border:0;
    font-size:1em;
    cursor:pointer;
  }
</style>