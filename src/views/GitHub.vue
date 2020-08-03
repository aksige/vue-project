<template>
  <div class="about-card">
    <div class="card-title">
      <img class="avatar" src="../assets/images/wer.jpg" alt="avatar" height="70px" />
      <div class="title-text-content">
        <p>About me</p>
        <h2>Lorem ipsum.</h2>
      </div>
    </div>
  </div>
</template>

<style lang="sass" scoped>
.about-card
  background: #333 url(../assets/images/b-min.jpg) no-repeat center center / cover
  padding: 3rem
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar
      border: 3px solid rgba(255,255,255,0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content
    p
      margin-bottom: 0
      color: rgb(210,210,210)
    h2
      margin-top: 0
      text-transform: capitalize
.card-content
  line-height: 1.5
  margin: 30px auto
  .skills
    display: grid
    grid-template-columns: repeat(2,1fr)
    grid-template-rows: repeat(4,90px)
    justify-content: center
    align-items: center
    text-align: center
    border: 10px solid white
    background: rgba(11, 14, 14, 0.7)
    border-radius: 50px
    font-size: 18px
    h3
      font-size: 36px
      color: #fff
      border-bottom: 5px solid white
    h4
      font-size: 24px
      text-transform: uppercase
      color: #990031
p
  color: #05ffae
</style>