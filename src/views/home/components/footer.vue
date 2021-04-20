<template>
  <div class="footer">
    <div class="feedback-container">
      <div class="part">
        <div class="column">
            <div class="Logo">
              logo图片
        </div>
          </div>
        
        <div class="contact">
          <div class="item-group">
            <div>
              <router-link to="/">Get a quote</router-link >
              <router-link to="/">Get directions</router-link >
              <router-link to="/">contact us</router-link >
              <router-link to="/">User login</router-link >
            </div>
          </div>
        </div>
        <div class="companyInfo">
          <div class="info-wrap">
            <div class="item-info">
              <h3 class="content">**********</h3>
              <span class="title">Customer service hotline</span>
            </div>
            <div class="item-info">
              <h3 class="content">*********</h3>
              <span class="title">Email feedback</span>
            </div>
            <div class="item-info">
              <h3 class="content">**************</h3>
              <span class="title">company address</span>
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
export default {

}
</script>

<style lang='scss' scoped>
@import '@/assets/css/footer/pc.scss';
@import '@/assets/css/footer/pro.scss';
@import '@/assets/css/footer/ipad.scss';
@import '@/assets/css/footer/phone.scss';
@import '@/assets/css/footer/mini.scss';
</style>