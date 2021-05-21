<template>
  <router-view />
</template>
<script>
import { provideI18n } from "./i18nPlugin";
export default {
  setup() {
    provideI18n({
      locale: "en", //表示默认的语言 修改全局locale值可以导入message中不同的包
      messages: {
        zh: require("./lang/zh").messages, // 中文语言包
        en: require("./lang/en").messages, // 英文语言包
      },
    });
  },
};
</script>

<style lang="scss">
@import "assets/initial/base.css";
#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  // -webkit-font-smoothing: antialiased;
  // -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;

  font-family: regular;
  // font-family: roboto;
  // font-family: flqd-i7, adobe-notdef;
  font-weight: 400;
  // font-style: italic;
}
</style>
