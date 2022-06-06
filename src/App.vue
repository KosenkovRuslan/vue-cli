<template>
  <div class="wrapper">
    <!-- Header -->
    <header>
      <div class="navbar">
        <div class="container">
          <div class="navbar-content">
            <div class="logo">VUECLI</div>
            <ul class="navbar-list">
              <li class="navbar-item">
                <a class="navbar-link">Home</a>
              </li>
              <li class="navbar-item">
                <a class="navbar-link">Example</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>

    <router-view></router-view>

    <!-- Footer -->
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {},
}
</script>

<style></style>
