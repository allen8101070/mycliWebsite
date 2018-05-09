<template>
    <section class="pt-5 pb-5" id="timeline">
        <div class="container">
            <div class="row">
                <div class="col-sm-12">
                    <h2>學經歷</h2>
                    <hr>
                </div>
            </div>
            <div class="timeline-section">
                <div class="row mt-3 timeline-pointer">
                    <div class="col-md-6">
                        <div class="time-block">
                            <h3>國立臺東大學 數位媒體與文教產業學系</h3>
                            <h4>2012-2016</h4><hr>
                            <p>大學時期多方接觸不同領域：3D、Unity、arduino、平面設計、影片剪輯...等，確立了我對做數位科技的熱忱，也建立了我對「做畫面」這件事的樂趣。<br><br>
                            這段期間擔任過：班代、宿委、系學會、畢籌會、學生議員..等職位，也有在麥當勞打工、台東縣政府實習的經歷，大學多采多姿的活動與磨練，對往後的我影響很深。
                            </p>
                        </div>
                    </div>
                    <div class="col-md-6">
                    </div>
                </div>
                <div class="row mt-3 timeline-pointer flex-sm-row-reverse">
                    <div class="col-md-6">
                        <div class="time-block">
                            <h3>台中資策會 前端班</h3>
                            <h4>2017</h4><hr>
                            <p>畢業後決定投入網頁的世界求職，先在網路的線上平台學習一陣子後，覺得自己能寫程式，於是投入資策會前端養成班上課。
                            <br><br>
                            由於有先在網路上學過HTML、CSS，在資策會的時期反而比預想的輕鬆，這段時期學習了不少網頁知識、前後端名詞等等。還沒結訓時就有遊戲廠商主動邀約工作，但想寫網頁而不是HTML5遊戲，最後予以婉拒而自行找工作。</p>
                        </div>
                    </div>
                    <div class="col-md-6">
                    </div>
                </div>
                <div class="row mt-3 timeline-pointer">
                    <div class="col-md-6">
                        <div class="time-block">
                            <h3>雋上科技 前端工程師</h3>
                            <h4>2017-2018</h4><hr>
                            <p>在雋上科技期間，與其他同事合作維護公司舊有專案的前端、並獨自負責直播專案的前端部分，能與網頁設計、後端、QA合作，且能獨自切版並用JavaScript開發團隊用網頁工具。
                            <br><br>
                            這段期間有幾點收穫：<br>1.脫離「做畫面」的思考，多思考「做功能」的部分<br>2.開始瞭解公司運作、職場與專案的部分<br>3.思考公司個人職涯與技術的成長
                            </p>
                        </div>
                    </div>
                    <div class="col-md-6">
                    </div>
                </div>

            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'timeline',
  
}
</script>

<style scoped lang="sass">
@import "../assets/variables"

#timeline
  background-color: #fff
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 80 80' width='80' height='80'%3E%3Cpath fill='%23ffd5bf' fill-opacity='0.33' d='M14 16H9v-2h5V9.87a4 4 0 1 1 2 0V14h5v2h-5v15.95A10 10 0 0 0 23.66 27l-3.46-2 8.2-2.2-2.9 5a12 12 0 0 1-21 0l-2.89-5 8.2 2.2-3.47 2A10 10 0 0 0 14 31.95V16zm40 40h-5v-2h5v-4.13a4 4 0 1 1 2 0V54h5v2h-5v15.95A10 10 0 0 0 63.66 67l-3.47-2 8.2-2.2-2.88 5a12 12 0 0 1-21.02 0l-2.88-5 8.2 2.2-3.47 2A10 10 0 0 0 54 71.95V56zm-39 6a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm40-40a2 2 0 1 1 0-4 2 2 0 0 1 0 4zM15 8a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm40 40a2 2 0 1 0 0-4 2 2 0 0 0 0 4z'%3E%3C/path%3E%3C/svg%3E")

.timeline-section
  position: relative
  
  &:after
    content: ""
    position: absolute
    left: 50%
    transform: translateX(-50%)
    top: 0
    bottom: 0
    width: 4px
    background-color: $simon-bgc

.time-block
  border-bottom: 10px solid $simon-bgc
  padding: 1.2em
  box-shadow: 0px 0px 10px #ccc
  border-radius: 6px
  background-color: #fff
  &:hover
    box-shadow: 0px 1px 16px #888
    transition: all 0.3s

.timeline-pointer
  position: relative
  &:after
    content: ""
    position: absolute
    left: 50%
    transform: translateX(-50%)
    top: 0
    bottom: 0
    top: 0
    width: 10px
    height: 10px
    border-radius: 50%
    border: 3px solid darkred
    background-color: #fff
    z-index: 100

@media (max-width: 1024px)
  .time-block:hover
    box-shadow: 0px 0px 10px #ccc
    transition: none

@media (max-width: 767px)
  .timeline-section:after
    left: -10px
    transform: none
  .timeline-pointer:after
    left: 2px
    transform: none
</style>