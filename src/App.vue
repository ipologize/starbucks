<template>
  <div id="app">
    <NavbarComponents />
    <router-view />
  </div>
</template>

<script>
import NavbarComponents from "@/components/NavbarComponents.vue"

export default {
  name: "HomeView",
  components: { NavbarComponents },
}
</script>

<style>
@import url(//db.onlinewebfonts.com/c/d7e8a95865396cddca89b00080d2cba6?family=SoDo+Sans+SemiBold);
* {
  margin: 0;
  padding: 0;
  font-family: Arial, Helvetica, sans-serif;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-family: "Open Sans", sans-serif;
  overflow-x: hidden;
}

/* f4c5a1 */
</style>
