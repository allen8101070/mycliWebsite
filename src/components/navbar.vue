<template>
<nav class="navbar navbar-expand-lg navbar-dark fixed-top simon-navbar">
  <a class="navbar-brand" href="#">Simon的個人網站</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav ml-auto">
      <a class="nav-item nav-link simon-nav" @click="toAboutMe">關於我</a>
      <a class="nav-item nav-link simon-nav" @click="toTimeline">學經歷</a>
      <a class="nav-item nav-link simon-nav" @click="toSkill">技能</a>
      <a class="nav-item nav-link simon-nav" @click="toWorks">作品</a>
      <a class="nav-item nav-link simon-nav" @click="toContact">聯絡我</a>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'navbar',
  methods:{
    toAboutMe(){
        $('html,body').animate({
          scrollTop:$('#aboutMe').offset().top
        }, 800); 
    },
    toTimeline(){
        $('html,body').animate({
          scrollTop:$('#timeline').offset().top
        }, 800); 
    },
    toSkill(){
        $('html,body').animate({
          scrollTop:$('#skill').offset().top
        }, 800); 
    },
    toWorks(){
        $('html,body').animate({
          scrollTop:$('#works').offset().top
        }, 800); 
    },
    toContact(){
        $('html,body').animate({
          scrollTop:$('#contact').offset().top
        }, 800); 
    }
  },
  mounted() {
    // 漢堡選單連結被點選後 自動收合
    if($(window).width()<991){ 
    $('.navbar a').on('click', function(){
      console.log('被點到囉')
        $('.navbar-toggler').click();
    });
    }
  }
}
</script>

<style scoped lang="sass">
@import "../assets/variables"

.simon-navbar
  background-color: $simon-bgc
  box-shadow: 0px 0px 10px #333

  .navbar-nav
    .simon-nav
      color: #fff
      cursor: pointer

@media (min-width: 992px)
  .simon-navbar
    .navbar-nav
      .simon-nav:hover
        color: #fff1ea

</style>