<template>
  <div class="header">
    <span class="logo">Logo</span>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-center" id="navbarNavAltMarkup">
        <ul class="navbar-nav">
          <li class="nav-item">
            <nuxt-link to="/films" class="nav-link">
							Films
						</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/people" class="nav-link">
							People
						</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/locations" class="nav-link">
							Locations
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/species" class="nav-link">
							Species
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/vehicles" class="nav-link">
							Vehicles
            </nuxt-link>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
  .color-active {
    color: #109CEB !important;
  }

  .header {
    background-color: #109CEB;
    box-shadow: 0 .1rem 1rem .5rem rgba(0, 0, 0, 0.2);
  }

  .header .logo {
    display: block;
    width: 10rem;
    height: 10rem;
		font-size: 0;
    background: url('../static/logo.png') no-repeat center;
    background-size: cover;
    margin: 0 auto;
  }

  .header .navbar {
    justify-content: flex-end;
    background-color: white;
  }

  .router-link-exact-active {
    color: #109CEB !important;
  }
</style>