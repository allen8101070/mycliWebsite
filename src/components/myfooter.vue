<template>

    <footer class="text-center myfooter">
      <div class="container">
        <p>2017 By SimonAllen</p>
      </div>
    </footer>

</template>

<script>
export default {
  name: 'myfooter'
}
</script>

<style scoped lang="sass">
@import "../assets/variables"

.myfooter
  height: 100px
  background: url(https://www.pakutaso.com/shared/img/thumb/yuu1226IMGL0009_TP_V.jpg) no-repeat
  background-size: cover
  background-attachment: fixed
  margin: 0px
  font-weight: 900
  font-size: 20px
  text-shadow: 0px 0px 6px $simon-sdc
  color: #fff
  p
    margin-bottom: 0px
    line-height: 100px

</style>