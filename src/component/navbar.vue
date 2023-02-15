<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary bg-black fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Adityamms.</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#toolsku">Features</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#call">Price</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            contact
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="https://www.instagram.com/adityamms_/?hl=id">Instagram</a></li>
            <li><a class="dropdown-item" href="https://github.com/adityamms">Github</a></li>
            <li><a class="dropdown-item" href="https://www.linkedin.com/in/aditya-marzuk-8603771a1/">LinkedIn</a></li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    nav{
        a:hover{
            transform: scale(1.1);
            text-shadow: 2px 2px 2px white;
            border-bottom: .5px solid black;
        }
    }

</style>