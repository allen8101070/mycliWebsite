<template>
<section  class="pt-5 pb-5" id="works">
    <div class="container">
        <div class="row">
            <div class="col-sm-12">
                <h2>作品</h2>
                <hr>
            </div>
            <div class="col-xl-4 col-md-6 col-sm-12">
                <div class="works-block ml-auto mr-auto mb-4">
                    <img src="../assets/works/001.jpg">
                    <div class="text-center works-info">
                        <h4>體育直播</h4>
                    </div>
                </div>
            </div>
            <div class="col-xl-4 col-md-6 col-sm-12">
                <div class="works-block ml-auto mr-auto mb-4">
                    <img src="../assets/works/002.jpg">
                    <div class="text-center works-info">
                        <h4>直播測試頁</h4>
                    </div>
                </div>
            </div>
            <div class="col-xl-4 col-md-6 col-sm-12">
                <div class="works-block ml-auto mr-auto mb-4">
                    <img src="../assets/works/003.jpg">
                    <div class="text-center works-info">
                        <h4>直播監控頁</h4>
                    </div>
                </div>
            </div>
            <div class="col-xl-4 col-md-6 col-sm-12">
                <div class="works-block ml-auto mr-auto mb-4">
                    <img src="../assets/works/004.jpg">
                    <div class="text-center works-info">
                        <h4>咖啡巨匠</h4>
                    </div>
                </div>
            </div>
            <div class="col-xl-4 col-md-6 col-sm-12">
                <div class="works-block ml-auto mr-auto mb-4">
                    <img src="../assets/works/005.jpg">
                    <div class="text-center works-info">
                        <h4>Hello電影網</h4>
                    </div>
                </div>
            </div>
            <div class="col-xl-4 col-md-6 col-sm-12">
                <div class="works-block ml-auto mr-auto mb-4">
                    <img src="../assets/works/006.jpg">
                    <div class="text-center works-info">
                        <h4>打地鼠</h4>
                    </div>
                </div>
            </div>
            <div class="col-sm-12 text-center">
            <a class="btn btn-warning mt-4" role="button" href="https://github.com/allen8101070/resume" target="_blank">作品清單</a>
            </div>
        </div>
    </div>
</section>
</template>

<script>
export default {
  name: 'works',
  
}
</script>

<style scoped lang="sass">
@import "../assets/variables"

#works
  background-color: #fff
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 80 80' width='80' height='80'%3E%3Cpath fill='%23ffd5bf' fill-opacity='0.33' d='M14 16H9v-2h5V9.87a4 4 0 1 1 2 0V14h5v2h-5v15.95A10 10 0 0 0 23.66 27l-3.46-2 8.2-2.2-2.9 5a12 12 0 0 1-21 0l-2.89-5 8.2 2.2-3.47 2A10 10 0 0 0 14 31.95V16zm40 40h-5v-2h5v-4.13a4 4 0 1 1 2 0V54h5v2h-5v15.95A10 10 0 0 0 63.66 67l-3.47-2 8.2-2.2-2.88 5a12 12 0 0 1-21.02 0l-2.88-5 8.2 2.2-3.47 2A10 10 0 0 0 54 71.95V56zm-39 6a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm40-40a2 2 0 1 1 0-4 2 2 0 0 1 0 4zM15 8a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm40 40a2 2 0 1 0 0-4 2 2 0 0 0 0 4z'%3E%3C/path%3E%3C/svg%3E")

.works-block
  position: relative
  width: 300px
  height: 200px
  img
    width: 300px
    height: 200px
    box-shadow: 0px 0px 10px #777

.works-info
  top: 0px
  bottom: 0px
  left: 0px
  right: 0px
  position: absolute
  display: none
  width: 300px
  height: 200px
  background: rgba(0, 0, 0, 0.4)
  color: #fff
  cursor: pointer
  h4
    line-height: 200px

.works-block:hover .works-info
  display: block
  
@media (max-width: 1200px)
  .works-info
    display: block
    background: rgba(0, 0, 0, 0.3)
    text-shadow: 0px 0px 10px $simon-sdc

</style>