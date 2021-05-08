<template>
  <div class="business">
    <div class="section-headline">
      <span>{{i18n.$t('Why Choose Us')}}</span>
    </div>
    <div class="business-group">
      <div class="group-block">
        <img src="../../../../assets/img/image1.jpg" alt="">
        <div class="business-title">
          <span>{{i18n.$t('Fast Delivery')}}</span>
        </div>
        <div class="business-desc">
          <span>{{i18n.$t('We guarantee same-day delivery for all local packages and next-day delivery for all parcels. We are committed to providing the best logistic experience and the highest quality of customer service.')}}</span>
        </div>
      </div>
      <div class="group-block">
        <img src="../../../../assets/img/image2.jpg" alt="">
        <div class="business-title">
          <span>{{i18n.$t('Service Integration')}}</span>
        </div>
        <div class="business-desc">
          <span>{{i18n.$t('We provide a one-stop last-mile delivery service plus storage system solution for various E-commerce and retail customers. We will take care of your parcels from the starting point and fulfill the client’s needs at any stage of the process. ')}}</span>
        </div>
      </div>
      <div class="group-block">
        <img src="../../../../assets/img/image3.jpg" alt="">
        <div class="business-title">
          <span>{{i18n.$t('Low Pricing')}}</span>
        </div>
        <div class="business-desc">
          <span>{{i18n.$t('We are here to offer the most competitive price in the market. Through extensive partnerships, we are proud to provide our customers with lower cost for last-mile delivery services and storage solutions.')}}</span>
        </div>
      </div>
      <div class="group-block">
        <img src="../../../../assets/img/image4.jpg" alt="">
        <div class="business-title">
          <span>{{i18n.$t('Partnerships')}}</span>
        </div>
        <div class="business-desc">
          <span>{{i18n.$t(' We focus on building strategic cooperation with various e-commerce brands, retail sites, and warehouse centers to ensure the smooth flow of cross-border logistics services all in one platform.')}}</span>
        </div>
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

<style lang="scss" >
@import '@/assets/css/business/pc.scss';
@import '@/assets/css/business/pro.scss';
@import '@/assets/css/business/ipad.scss';
@import '@/assets/css/business/phone.scss';
@import '@/assets/css/business/mini.scss';
</style>