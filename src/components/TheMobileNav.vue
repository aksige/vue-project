<template>
  <section class="nav">
    <div class="nav-logo">
      <img class="logo" src="../assets/images/s1200.jpg" alt="logo" height="80px" />
    </div>
    <div class="nav-menu">
      <ul class="nav-menu-list">
        <li class="nav-list-item">About me</li>
        <li class="nav-list-item">GitHub</li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang='sass' scoped>
.nav
  background: #333
  display: flex
  flex-direction: column
  justify-content: space-around
  align-items: center
  &-logo
    margin: 20px auto
    .logo
      border-radius: 50%
      &:hover
        box-shadow: 0 0 15px 6px red
  &-menu
    width: 100%
    &-list
      list-style: none
      padding: 0
      display: flex
      margin: 0
      color: white
      li
        width: 50%
        text-align: center
        background: #555
        padding: 10px 0
        cursor: pointer
        transition: background 300ms ease-in-out
        &:hover
          background: #333
</style>