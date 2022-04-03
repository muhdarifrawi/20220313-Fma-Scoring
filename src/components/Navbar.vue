<template>
  <nav class="navbar fixed-top navbar-dark bg-dark" id="main-navbar">
    <div class="container-fluid">
      <a v-on:click="goMain" class="navbar-brand" href="#">FMA Scoring</a>
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
          <span v-on:click="goAdminScoring" class="nav-link navbar-toggler my-2" aria-current="page" href="#"
              data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation"
            >
              Administration and Scoring
            </span>
            <span v-on:click="goKeyform" class="nav-link navbar-toggler my-2" aria-current="page" href="#"
              data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation"
            >
              Keyform
            </span>
            <span v-on:click="goIntervention" class="nav-link navbar-toggler my-2" aria-current="page" href="#"
              data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation"
            >
              Intervention
            </span>
            <span v-on:click="goBrochures" class="nav-link navbar-toggler my-2" aria-current="page" href="#"
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
  methods:{
    goMain(){
      this.$emit("clicked","main");
    },
    goAdminScoring(){
      this.$emit("clicked","admin-score");
    },
    goKeyform(){
      this.$emit("clicked","keyform");
    },
    goIntervention(){
      this.$emit("clicked","intervention");
    },
    goBrochures(){
      this.$emit("clicked","brochures");
    }
  }
};
</script>
<style>
  .nav-link{
    border:0;
    font-size:1em;
    cursor:pointer;
  }
  
</style>