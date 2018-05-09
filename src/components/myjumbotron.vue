<template>
<div class="jumbotron simon-jumbotron">
  <div class="container">
    <h2 class="display-1">Hello !</h2>
    <p class="h3">我是Simon士堯</p>
    <img src="../assets/isMe.png">
  </div>
</div>
</template>

<script>
export default {
  name: 'myjumbotron'
}
</script>

<style scoped lang="sass">
@import "../assets/variables"

.simon-jumbotron
  height: 100vh
  background: url(https://www.pakutaso.com/shared/img/thumb/yuu1226IMGL0009_TP_V.jpg) no-repeat
  background-size: cover
  background-attachment: fixed
  margin: 0px
  text-shadow: 0px 0px 10px $simon-sdc
  color: #fff
  position: relative

  .container
    padding: 100px 0px

  img
    filter: drop-shadow(0px 0px 10px #888)

  h2, p
    margin-left: 100px
    font-weight: 900

@media (max-width: 2200px)
  .simon-jumbotron
    img
      position: absolute
      height: 70vh
      bottom: 0px
      right: 30vh

@media (max-width: 1200px)
  .simon-jumbotron
    img
      height: 70vh
      bottom: 0px
      right: 20vh

@media (max-width: 992px)
  .simon-jumbotron
    h2, p
      margin-left: 0px
    img
      height: 70vh
      bottom: 0px
      right: 10vh

@media (max-width: 768px)
  .simon-jumbotron
    img
      height: 60vh
      bottom: 0px
      right: 10vh

@media (max-width: 414px)
  .simon-jumbotron
    .container
      padding-top: 60px
      padding-bottom: 100px
    img
      height: 59vh

@media (max-width: 374px)
  .simon-jumbotron
    h2, p
      font-size: 40px

    img
      height: 59vh
      left: 30px
      right: 0px
</style>