<template>
  <div>
    <nav class="indigo darken-1">
      <div class="nav-wrapper">
        <router-link to="/" class="brand-logo">Tasks</router-link>
        <ul class="right hide-on-med-and-down">
          <router-link
            tag="li"
            to="/"
            exact
            active-class="active"
          >
           <a href="#">Create</a>
         </router-link>

         <router-link
            tag="li"
            to="/list"
            active-class="active"
          >
           <a href="#">List</a>
         </router-link>
        </ul>
        </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar"
}
</script>

<style  lang="scss">
  nav {
    padding: 0 2rem;
  }
</style>