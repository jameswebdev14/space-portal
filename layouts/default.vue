<template>
  <div id="default">
    <div><h1 class="text-center" id="title">SPACE PORTAL</h1></div>
    <div id="main_body">
      <Nav class="col-lg-12"></Nav>
    </div>
    <nuxt/>
  </div>
</template>

<script>
import Nav from "@/components/Nav";

export default {
  name: "default",
  components: {
    Nav
  }
};
</script>

<style>
html {
  box-sizing: border-box;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

#title {
  font-size: 4rem;
  font-style: italic;
  color: cadetblue;
  padding-bottom: 10px;
}

#default {
  background-image: url("../assets/img/space-background.jpg");
}

#main_body {
  display: grid;
  grid-template-columns: 100% 1fr;
  grid-template-rows: auto;
}
</style>
