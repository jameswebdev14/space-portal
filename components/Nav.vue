<template>
  <nav class="navbar navbar-expand-lg">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <nuxt-link to='home' class="nav-link" href="#">Home <span class="sr-only">(current)</span></nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to='earth' class="nav-link" href="#">Earth</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to='milkyway' class="nav-link" href="#">Milky Way</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to='ourgalaxy' class="nav-link" href="#">Our Galaxy</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to='solarsystem' class="nav-link" href="#">Solar System</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to='sun' class="nav-link" href="#">Sun</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to='universe' class="nav-link" href="#">Universe</nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Nav"
};
</script>

<style>
.navbar .nav-link {
  color: cadetblue;
  background-color: transparent;
  font-size: 1.5rem;
}

.nav-link {
  justify-content: space-evenly;
  margin: auto;
}

.navbar-toggler {
  color: white;
}
</style>
