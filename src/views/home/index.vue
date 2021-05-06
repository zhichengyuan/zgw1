<template>
  <div class="home">
   
      <Header></Header>
      <Main></Main>
      <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/header'

import Main from './components/main'
import Footer from './components/footer'
export default {
  name: 'Home',
  components:{Header,Main,Footer}
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

