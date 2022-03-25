<template>
  <!-- set the header, nav and footer in this template for the entire website -->
  <div class="grid-container">
    <header class="header">
      <img
        class="header-img"
        :src="require('static/images/back-yard-trees.jpg')"
        alt="A view looking out to a tree filled and grassy backyard."
      />
      <div class="flex-heading">
        <img class="logo-box" />
        <h1>Dragonfly Landscaping</h1>
      </div>

      <nav class="nav">
        <ul class="nav-list">
          <!-- <nuxt-link> acts like an <a> with the correct href -->
          <li><nuxt-link to="/">The Beginning</nuxt-link></li>
          <li><nuxt-link to="/projects">Projects</nuxt-link></li>
          <li><nuxt-link to="/about">About</nuxt-link></li>
          <!-- <li>
            <span data-toggle="tooltip" title="Not working yet">
              <a class="nav-link disabled" href="#">More and more</a>
            </span>
          </li> -->
        </ul>
      </nav>
    </header>
    <nuxt />

    <footer class="footer">
      <ul class="footer-nav">
        <li><nuxt-link to="/">The Beginning</nuxt-link></li>
        <li><nuxt-link to="/projects">Projects</nuxt-link></li>
        <li><nuxt-link to="/about">About</nuxt-link></li>
      </ul>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout',

  data() {
    return {};
  },
};
</script>

<style></style>
