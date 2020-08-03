<template>
  <section class="nav">
    <div class="nav-logo">
      <img class="logo" src="../assets/images/s1200.jpg" alt="logo" height="120px" />
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
  position: fixed
  left: 0
  top: 0
  bottom: 0
  background: #333
  display: flex
  flex-direction: column
  align-items: center
  width: 20vw
  &-logo
    margin: 100px
    .logo
      border-radius: 50%
      &:hover
        box-shadow: 0 0 30px 15px red
  &-menu
    color: white
    &-list
      list-style: none
      .nav-list-item
        background: #222
        padding: 10px 20px
        text-align: center
        margin: 10px auto
        cursor: pointer
        &:hover
          width: 100%
</style>