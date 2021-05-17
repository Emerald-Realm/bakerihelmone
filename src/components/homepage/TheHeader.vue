<template>
  <div class='header'>
    <div class='logo-row'>Logo</div>
    <ul class='navbar'>
      <li class='nav-item'>Home</li>
      <li class='nav-item'>Home</li>
      <li class='nav-item'>Home</li>
      <li class='nav-item'>Home</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'TheHeader'
}
</script>

<style scoped>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.nav-item {
  padding: 1vw 0.5vw;
}
</style>
