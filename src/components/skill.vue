<template>
<section id="skill">
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-4 bg-cover" style="background-image:url(https://www.pakutaso.com/shared/img/thumb/PAK86_codeing20140517_TP_V.jpg)">
            </div>
            <div class="col-lg-7">
                <div class="container pt-5 pb-5">
                    <div class="row">
                        <div class="col-12 text-center">
                        <h2>技能</h2>
                        <hr>
                    </div>
                    
                </div>

                <div class="row">
                    <div class="col-6 mb-5 text-center">
                        <i class="fab fa-html5 fa-4x"></i>
                        <h3>HTML</h3>
                        <ul class="list-unstyled">
                            <li><i class="fas fa-code"></i> 能撰寫語意化標籤</li>
                            <li><i class="fas fa-code"></i> 使用過pug</li>
                            <li><i class="fas fa-code"></i> HTML5</li>
                        </ul>
                    </div>
                    <div class="col-6  mb-5 text-center">
                    <i class="fab fa-css3 fa-4x"></i>
                    <h3>CSS</h3>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-code"></i> 手刻RWD</li>
                        <li><i class="fas fa-code"></i> BS3、BS4</li>
                        <li><i class="fas fa-code"></i> 使用過SASS</li>
                    </ul>
                    </div>
                    <div class="col-6 text-center">
                    <i class="fab fa-js fa-4x"></i>
                    <h3>JavaScript</h3>
                        <ul class="list-unstyled">
                        <li><i class="fas fa-code"></i> jQuery</li>
                        <li><i class="fas fa-code"></i> ES6</li>
                        <li><i class="fas fa-code"></i> Vue.js</li>
                        <li><i class="fas fa-code"></i> Node.js</li>
                        </ul>
                    </div>
                    <div class="col-6 text-center">
                    <i class="fas fa-code-branch fa-4x"></i>
                    <h3>Other</h3>
                        <ul class="list-unstyled">
                        <li><i class="fas fa-code"></i> 使用GIT版控</li>
                        <li><i class="fas fa-code"></i> 使用過webpack、gulp</li>
                        <li><i class="fas fa-code"></i> vscode、webstorm</li>
                        <li><i class="fas fa-code"></i> illustrator</li>
                        </ul>
                    </div>
                </div>

                </div>
            </div>
            <div class="col-lg-1"></div>
        </div>
    </div>
</section>

</template>

<script>
export default {
  name: 'skill'
}
</script>

<style scoped lang="sass">
@import "../assets/variables"

#skill
  background-color: #f9f9f9
  color: $simon-txtc
  text-align: center
  box-shadow: 0px 0px 4px -2px #ccc
  font-weight: 900
  li
    color: $simon-txtc2
    

.bg-cover
  background-size: cover

@media (max-width: 991px)
  .bg-cover
    display: none
</style>