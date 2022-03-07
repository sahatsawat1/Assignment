<!-- Please remove this file from your project -->
<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-wrapper">
        <img class="logo" src="../img/logo.png" alt="">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggler">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarToggler">
          <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
            <li class="nav-item profile">
              <img src="../img/team-1.jpg" alt="">
              <a href="#" class="nav-link">Delowar</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>

.container-wrapper {
  display: flex;
  justify-content: space-around;
  width: 100%;
}

.profile {
  display: flex;
}

.profile img {
  border-radius: 5rem;
  width: 2.5rem;
}

img {
  width: 10rem;
}

</style>