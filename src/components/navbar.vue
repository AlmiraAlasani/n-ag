<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light" style="padding-left:5em">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Logo</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
              <a class="nav-link" href="#">Home</a>
              <a class="nav-link" href="#">Projects</a>
              <a class="nav-link" href="#">Testimonials</a>
              <a class="nav-link" href="#">Contact</a>              
            </div>
          </div>
        </div>
      </nav>
</template>

<script>
export default {
  name: 'navbar',

}
</script>

<style>
.navbar-nav{
    margin-left: 60em;
   
}

</style>