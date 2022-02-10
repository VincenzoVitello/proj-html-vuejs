<template>
  <div class="footer_container">
      <div class="social">
        <img src="../assets/layout-images/images/logo-restaurant.png" alt="">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur sed eaque mollitia inventore a nisi qui asperiores.</p>
        <ul>
          <li v-for="(element, index) in socialArr" :key="index"><i :class="element" class="social_elem"></i></li>
        </ul>
      </div>
      <div class="copy_container">
        <div class="copy">
          Copyright 2021 - 2019 Avada | All rights reserved | Powered by WordPress | ThemeFusion
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Footer',
    data(){
      return{
        socialArr: [
          "fa-brands fa-facebook-f", 
          "fa-brands fa-twitter", 
          "fa-brands fa-youtube", 
          "fa-brands fa-instagram",
          "fa-brands fa-linkedin-in"
        ]
      }
    }
}

</script>

<style lang="scss" scoped>
@import "../assets/footer.scss";
</style>