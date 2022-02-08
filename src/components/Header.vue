<template>
  <div class="ms_header_container">
      <div class="left_header">
          <div class="logo_header">
              <img src="../assets/layout-images/images/logo-restaurant.png">
          </div>
          <div class="header_text_container">
                
                <div class="header_text">
                    <p>The best table in town</p>
                    <p class="white_title">Fine dining experience</p>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi commodi dolores odit sit eaque! Aperiam totam vero mollitia maxime unde ipsa, numquam dolores? Iste nulla velit ipsa in consectetur officiis.</p>
                    <div class="menu_button">Explore the menu</div>
                </div>
          </div>
          
      </div>
      <div class="rigth_header">
          <ul>
              <li>Home</li>
              <li>Culinary History</li>
              <li>Our Team</li>
              <li>Our Menu</li>
              <li>Take out <span>new</span></li>
              <li>Bulletin</li>
              <li>Reservations</li>
              <li><i class="fa-solid fa-cart-arrow-down"></i></li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style lang="scss" scoped>
@import "../assets/global.scss";
@import "../assets/vars.scss";
@import "../assets/header.scss";
</style>