<template>
  <div class="settings">
    <div class="nav">
      <ul>
        <li><nuxt-link to="/settings">Genneral</nuxt-link></li>
        <li><nuxt-link to="/settings/desk">Desks</nuxt-link></li>
        <li><nuxt-link to="/settings/time">Times</nuxt-link></li>
      </ul>
    </div>

    <nuxt-child></nuxt-child>
  </div>
</template>

<script>
export default {};
</script>

<style>
.settings {
  display: flex;
}
.profiles {
  margin-left: 3cm;
}
</style>