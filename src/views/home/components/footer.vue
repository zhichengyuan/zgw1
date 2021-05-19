<template>
  <div class="footer">
    <div class="feedback-container">
      <div class="part">
        <div class="column">
          <div class="Logo"></div>
        </div>

        <div class="contact">
          <div class="item-group">
            <div>
              <router-link to="/">{{i18n.$t('About Direct Xpress')}} </router-link>
              <router-link to="/">{{i18n.$t('Contact Us')}}</router-link>
              <router-link to="/">{{i18n.$t('Customer Service')}}</router-link>
              <router-link to="/">{{i18n.$t('Get a Quote')}}</router-link>
              <router-link to="/"> {{i18n.$t('Careers')}}</router-link>
              <router-link to="/">{{i18n.$t('User Login')}} </router-link>
              <router-link to="/">{{i18n.$t('Privacy Policy')}} </router-link>
              <router-link to="/">{{i18n.$t('Learn More')}}</router-link>
            </div>
          </div>
        </div>
        <div class="companyInfo">
          <div class="info-wrap">
            <div class="item-info">
              <h3 class="content">{{i18n.$t('(626) 567-3999')}}</h3>
              <span class="title">{{i18n.$t('Customer service hotline')}}</span>
            </div>
            <div class="item-info">
              <span class="title">info@directxps.com</span>
            </div>
            <div class="item-info">
              <h3 class="content">
                <!-- {{i18n.$t('19550 Vallco Pkwy, Suite 215, Cupertino, CA, 95014')}} -->
                {{i18n.$t('19585 E Walnut Dr N, City of Industry, CA 91789')}}
              </h3>
              <span class="title">{{i18n.$t('company address')}}</span>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="notic">
        <div>
          <router-link to="https://support.google.com/business/answer/7388122">Report abuse</router-link>
          </div>
        <div><router-link to="https://www.google.com/business/how-it-works/website">Google</router-link> </div>
      </div> -->
    </div>
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
@import "@/assets/css/footer/pc.scss";
@import "@/assets/css/footer/pro.scss";
@import "@/assets/css/footer/ipad.scss";
@import "@/assets/css/footer/phone.scss";
@import "@/assets/css/footer/mini.scss";
</style>