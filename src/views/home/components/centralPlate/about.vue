<template>
  <div class="about">
     <div class="feature">
          <div class="feature-info">
           {{i18n.$t('The Fastest & Lowest Cost Last-Mile Delivery Service ')}} 
      </div>
     </div>
  </div>
</template>

<script>
import { useI18n } from "../../../../i18nPlugin";
export default {
 setup() {
      const i18n = useI18n();
      return {
        i18n,
      };
    }

}
</script>

<style lang="scss" scoped>
@import '@/assets/css/about/pc.scss';
@import '@/assets/css/about/pro.scss';
@import '@/assets/css/about/ipad.scss';
@import '@/assets/css/about/phone.scss';
@import '@/assets/css/about/mini.scss';
</style>