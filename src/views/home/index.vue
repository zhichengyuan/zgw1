<template>
  <div class="home">
   <div >
          <router-link to="/" >
               <span  @click="switchLanguage">中文/EN</span>
          </router-link>
      </div>
      <Header></Header>
      <Main></Main>
      <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/header'

import Main from './components/main'
import Footer from './components/footer'
 import { useI18n } from "../../i18nPlugin";
export default {
  name: 'Home',
  components:{Header,Main,Footer},
  setup() {
      const i18n = useI18n();

      const switchLanguage = () => {
          console.log('点击事件',i18n.locale.value)
        const locale = i18n.locale.value === "en" ? "zh" : "en";
        i18n.locale.value = locale;
      };

      return {
        i18n,
        switchLanguage
      };
    }

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

