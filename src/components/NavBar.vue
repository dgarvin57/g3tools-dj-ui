<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
      <a class="navbar-brand" href="#">g3tools</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarNav" class="collapse navbar-collapse">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <router-link to="/" class="nav-link">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/restricted-list" class="nav-link"
              >Restricted</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/brand-list" class="nav-link">Brands</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/brand-item" class="nav-link"
              >Brand Item</router-link
            >
          </li>
          <li class="nav-item">
            <router-link to="/item-master-list" class="nav-link"
              >Item Master</router-link
            >
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  props: {
    msg: String,
  },
};
</script>

<style scoped></style>
