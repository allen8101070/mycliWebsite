<template>
<section class="pt-5 pb-5" id="contact">
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <h2>聯絡我</h2>
        <hr>
      </div>

      <div class="col-sm-12 text-center">
        <img src="../assets/isMe2.png" class="my-photo mb-2 rounded-circle img-thumbnail" alt="個人照片">
        <h3 class="h5">Simon士堯</h3>
        <div class="contact-info">
          <i class="far fa-envelope"></i><a class="ml-2" href="10117108@gm.nttu.edu.tw">10117108@gm.nttu.edu.tw</a>
          <br>
          <div class="icon-link mt-2">
            
            <a href="https://github.com/allen8101070" target="_blank"><i class="fab fa-github ml-2 mr-2"></i></a>
            <a href="https://codepen.io/SimonAllen/" target="_blank"><i class="fab fa-codepen ml-2 mr-2"></i></a>
            <a href="https://www.linkedin.com/in/%E5%A3%AB%E5%A0%AF-%E6%9E%97-9b2a66141/" target="_blank"><i class="fab fa-linkedin ml-2 mr-2"></i></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'contact'
}
</script>

<style scoped lang="sass">
@import "../assets/variables"

#contact
  background-color: $simon-bgc
  color: #fff

.contact-info
  font-size: 20px

.my-photo
  width: 230px
  height: 230px

.icon-link
  font-size: 30px

.contact-info
  a
    color: #fff
    text-decoration: none
    &:hover
      color: #000
</style>