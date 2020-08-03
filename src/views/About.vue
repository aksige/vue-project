<template>
  <div class="about-card">
    <div class="card-title">
      <img class="avatar" src="../assets/images/wer.jpg" alt="avatar" height="70px" />
      <div class="title-text-content">
        <p>About me</p>
        <h2>Lorem ipsum.</h2>
      </div>
    </div>
    <div class="card-content">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti distinctio blanditiis eligendi laudantium dolorum, corrupti suscipit necessitatibus, praesentium pariatur cupiditate commodi possimus quam quod, aut impedit. Dolore unde tempora voluptates, autem quod voluptatibus, soluta aspernatur ratione, quo ad inventore placeat tempore blanditiis atque magnam. Laudantium modi sed odio? Necessitatibus, veniam.</p>
      <div class="skills">
        <h3 class="col-1-row-1">Requirement</h3>
        <h3 class="col-2-row-1">Solution</h3>
        <h4 class="col-1-row-2">Design</h4>
        <p class="col-2-row-2">Photoshop, Figma, Adobe XD, Illustrator</p>
        <h4 class="col-3-row-1">Front-End</h4>
        <p class="col-3-row-2">Vue.js HTML CSS JavaScript</p>
        <h4 class="col-4-row-1">Back-End</h4>
        <p class="col-4-row-2">Node.js Mongo</p>
      </div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, omnis. Ea provident doloribus magni obcaecati? Corporis tenetur commodi ad. Illo quo repudiandae, non dolorem doloribus facere odit tempora, saepe repellendus, expedita officia omnis maiores inventore laboriosam amet ipsum! Velit vel ad iste dignissimos consectetur eius amet ratione voluptates qui, cum, laboriosam quia natus officia et.</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, omnis. Ea provident doloribus magni obcaecati? Corporis tenetur commodi ad. Illo quo repudiandae, non dolorem doloribus facere odit tempora, saepe repellendus, expedita officia omnis maiores inventore laboriosam amet ipsum! Velit vel ad iste dignissimos consectetur eius amet ratione voluptates qui, cum, laboriosam quia natus officia et.</p>
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