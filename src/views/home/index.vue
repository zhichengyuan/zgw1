<template>
  <div class="home">
      <Menu></Menu>
   <!-- <div >
          <router-link to="/" >
               <span  >中文/EN</span>
          </router-link>
      </div> -->
      <Header></Header>
      <Main></Main>
      <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/header'

import Main from './components/main'
import Menu from './components/menu'
import Footer from './components/footer'

export default {
  name: 'Home',
  components:{Header,Main,Footer,Menu},
  

}
</script>
<style lang="scss">
.home {
  min-height: 544px;
  min-width: 200px;
  position: relative;
  overflow: hidden;
}


</style>

