<template>
<div>
<myjumbotron/>
<aboutme/>
<timeline/>
<skill/>
<works/>
<contact/>
<myfooter/>
</div>


</template>

<script>
import aboutme from './aboutme'
import myjumbotron from './myjumbotron'
import timeline from './timeline'
import skill from './skill'
import works from './works'
import contact from './contact'
import myfooter from './myfooter'

export default {
  name: 'mainpage',
  components:{
    myjumbotron,
    aboutme,
    timeline,
    skill,
    works,
    contact,
    myfooter

  }
}

</script>
