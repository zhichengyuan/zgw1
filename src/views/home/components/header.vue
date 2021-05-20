<template>
  <div class="home-header">
      <div class="home-part-img">
          <div class="text">
              <!-- <div class="title">DirectXpress</div>
          <div class="desc">{{i18n.$t('Delivery and Logistic Services')}} </div> -->
         
          <div class="home-btn">
              <router-link to="/">{{i18n.$t('Get Quote')}}</router-link>
          </div>
          </div>
          
      </div>
      <!-- <div class="btn-group">
      
      <div class="btn-group clearfix">
          <router-link to="/">
              <span>{{i18n.$t('login')}}</span>
          </router-link>
          <span>|</span>
          <router-link to="/">
              <span>{{i18n.$t('register')}}</span>
          </router-link>
      </div> 
           
      </div>-->
      
      
  </div>
</template>

<script>
import { useI18n } from "../../../i18nPlugin";
export default {
 setup() {
      const i18n = useI18n();
      return {
        i18n,
      };
    }

}
</script>

<style lang='scss' scoped>
@import '@/assets/css/header/pc.scss';
@import '@/assets/css/header/pro.scss';
@import '@/assets/css/header/ipad.scss';
@import '@/assets/css/header/phone.scss';
@import '@/assets/css/header/mini.scss';
</style>