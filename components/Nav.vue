<template>
  <div class="nav__wrapper">
    <nuxt-link to="/">
      Real world events
    </nuxt-link>
    <nav class="nav__internalWrapper">
      <nuxt-link to="/createEvent" class="nav__link">
        Create event
      </nuxt-link>
      <nuxt-link to="/" class="nav__link">
        List
      </nuxt-link>
    </nav>
  </div>
</template>
<style>
.nav__wrapper {
  display: flex;
  justify-content: space-evenly;
  padding: 20px 0;
}
.nav__link {
  padding: 0 20px;
}
</style>
