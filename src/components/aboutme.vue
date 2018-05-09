<template>
<section class="pt-5 pb-5" id="aboutMe">
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <h2>關於我</h2>
        <hr/>
      </div>
      <div class="col-lg-3"></div>
      <div class="col-lg-6 col-md-12 text-center">
        <p>我是林士堯(SimonAllen)，今年24歲，高雄人，現居臺中。
        <br>
        大學就讀數位媒體科系，畢業後投入前端領域學習，目前是位junior前端工程師。 我是能靜能動的中向性格，對於做畫面很感興趣，渴望學習與做畫面的成就感。
        </p>
        <a class="btn btn-warning" role="button" href="https://github.com/allen8101070/resume" target="_blank">GITHUB RESUME</a>
      </div>
      <div class="col-lg-3"></div>
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'aboutme'
}
</script>

<style scoped lang="sass">
@import "../assets/variables"
#aboutMe
  background-color: $simon-bgc
  color: #fff
</style>