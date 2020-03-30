<template>
  <div class="navbar">
    <nav class="nav-extended indigo darken-2">
      <div class="nav-content">
        <router-link to exact>
          <span class="nav-title">Smoothies</span>
        </router-link>
        <a class="btn-floating btn-large halfway-fab pink">
          <router-link to exact>
            <i class="material-icons">add</i>
          </router-link>
        </a>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar nav {
  padding: 0 20px;
}
</style>
