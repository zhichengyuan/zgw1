<template>
  <div class="footer">
    <div class="feedback-container">
      <div class="part">
        <div class="column">
          <div class="Logo">logo图片</div>
        </div>

        <div class="contact">
          <div class="item-group">
            <div>
              <router-link to="/"> About Direct Xpress</router-link>
              <router-link to="/">Contact Us</router-link>
              <router-link to="/">Customer Service</router-link>
              <router-link to="/">Get a Quote</router-link>
              <router-link to="/"> Careers</router-link>
              <router-link to="/">User Login </router-link>
              <router-link to="/"> Privacy Policy</router-link>
              <router-link to="/">Learn More</router-link>
            </div>
          </div>
        </div>
        <div class="companyInfo">
          <div class="info-wrap">
            <div class="item-info">
              <h3 class="content">(626) 567-3999</h3>
              <span class="title">Customer service hotline</span>
            </div>
            <div class="item-info">
              <h3 class="content">info@directxps.com</h3>
              <span class="title">Email feedback</span>
            </div>
            <div class="item-info">
              <h3 class="content">
                19550 Vallco Pkwy, Suite 215, Cupertino, CA, 95014
              </h3>
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
export default {};
</script>

<style lang='scss' scoped>
@import "@/assets/css/footer/pc.scss";
@import "@/assets/css/footer/pro.scss";
@import "@/assets/css/footer/ipad.scss";
@import "@/assets/css/footer/phone.scss";
@import "@/assets/css/footer/mini.scss";
</style>