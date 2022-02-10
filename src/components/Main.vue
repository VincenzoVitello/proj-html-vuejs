<template>
  <div>
    <div class="ms_main_container">
      <div class="experience">
        <div class="exp_sushi_text">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque est molestias similique numquam voluptates totam officia sunt dicta nam, quasi accusamus mollitia, facere quibusdam illum eveniet dolorem maxime temporibus fugit!</p>
          <p class="black_title">Food is our common ground, a universal experience</p>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed illum porro alias quis necessitatibus distinctio et eaque esse quidem, aperiam commodi consequatur omnis itaque adipisci doloremque? Quas dolores vero quidem.</p>
          <p class="signature">
            <img src="../assets/layout-images/images/signature.jpg" alt="">
          </p>
        </div>
        <div class="exp_sushi_img">
          <p>California rolls - $22</p>
        </div>
      </div>
      <div class="infos">
        <div class="info_card">
          <img src="../assets/layout-images/sushi-1.png" alt="">
          <p class="info_card_title">Best table in town</p>
          <hr>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel error nemo necessitatibus blanditiis sit veritatis nisi adipisci saepe illum asperiores nostrum, tempore quasi quo natus cum, cumque dolore eveniet dolorum.</p>
          <p class="info_button">Explore the menu</p>
        </div>
        <div class="info_card">
          <img src="../assets/layout-images/sushi-2.png" alt="">
          <p class="info_card_title">Perfect for groups</p>
          <hr>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel error nemo necessitatibus blanditiis sit veritatis nisi adipisci saepe illum asperiores nostrum, tempore quasi quo natus cum, cumque dolore eveniet dolorum.</p>
          <p class="info_button">Make a reservation</p>
        </div>
        <div class="info_card">
          <img src="../assets/layout-images/sushi-3.png" alt="">
          <p class="info_card_title">Fresh produce everyday</p>
          <hr>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel error nemo necessitatibus blanditiis sit veritatis nisi adipisci saepe illum asperiores nostrum, tempore quasi quo natus cum, cumque dolore eveniet dolorum.</p>
          <p class="info_button">Learn more about us</p>
        </div>
      </div>
    </div>
    <div class="main_jumbo_one">
        <div class="jumbo_right_img">
          <img src="../assets/layout-images/images/slider32x.jpg" alt="">
        </div>
        <div class="jumbo_left">
          <div class="header_text_container">
                
                <div class="header_text">
                    <p>Fine dining experience</p>
                    <p class="white_title">The best table in town</p>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi commodi dolores odit sit eaque! Aperiam totam vero mollitia maxime unde ipsa, numquam dolores? Iste nulla velit ipsa in consectetur officiis.</p>
                    <div class="menu_button">Explore the menu</div>
                </div>
          </div>
        </div>
    </div>
    <section class="customer_review">
      <div>
        <h2 class="critics_title">What critics say about us</h2>
        <hr>
      </div>
    </section>
    <div class="ms_nyt">
        <div class="nyt_img">
          <img src="../assets/layout-images/images/blog72x.jpg" alt="">
        </div>
        <div class="nyt_review">
          <div class="nyt_review_container">
            <p>Maggie Stuart</p>
            <p class="white_title">New York Times</p>
            <p>&#9733;&#9733;&#9733;&#9733;&#9733;</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae accusamus asperiores voluptatem autem, eveniet ut hic, iusto eius architecto nihil sit minima, fuga vel magni.</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sit sapiente mollitia, ullam excepturi iusto magnam debitis. Omnis iusto est neque architecto.</p>
            <div class="menu_button">read full article</div>
          </div>
        </div>
      </div>
    <div class="journals_reviews ms_nyt">
    
      <div class="journal_right">
            <div class="overlay">
              <div class="nyt_review_container">
              <p>Mary Maxey</p>
              <p class="white_title journal">The Guardian</p>
              <p>&#9733;&#9733;&#9733;&#9733;&#9733;</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae accusamus asperiores voluptatem autem, eveniet ut hic, iusto eius architecto nihil sit minima, fuga vel magni.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sit sapiente mollitia, ullam excepturi iusto magnam debitis. Omnis iusto est neque architecto.</p>
              <div class="menu_button">read full article</div>
            </div>
            </div>
      </div>

      <div class="journal_left">
            <div class="overlay">
              <div class="nyt_review_container">
              <p>Patrick Monroe</p>
              <p class="white_title journal">Globe and mail</p>
              <p>&#9733;&#9733;&#9733;&#9733;&#9733;</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae accusamus asperiores voluptatem autem, eveniet ut hic, iusto eius architecto nihil sit minima, fuga vel magni.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sit sapiente mollitia, ullam excepturi iusto magnam debitis.</p>
              <div class="menu_button">read full article</div>
            </div>
            </div>
      </div>
    </div>
    <div class="jumbotron_bottom_main">
      <p>Kung Pao Chicken - $32</p>
    </div>
     <section class="customer_review">
      <div>
        <h2 class="critics_title">Latest news and promotions</h2>
        <hr>
      </div>
    </section>
    <div class="news_square">
      <div v-for="(element, index) in newsArr" :key="index" class="news_cards">
        <img :src="(element.pic)" alt="">
        <p class="news_card_title">{{element.title}}</p>
        <p class="news_card_credits">{{element.credits}}</p>
      </div>
    </div>
    <div class="main_jumbo_one">
        <div class="jumbo_right_img">
          <img src="../assets/layout-images/images/slider72x-scaled.jpg" alt="">
        </div>
        <div class="jumbo_left">
          <div class="header_text_container">
                
                <div class="header_text">
                    <p>Enjoy your meal at home</p>
                    <p class="white_title">Takeout now available</p>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi commodi dolores odit sit eaque! Aperiam totam vero mollitia maxime unde ipsa, numquam dolores? Iste nulla velit ipsa in consectetur officiis.</p>
                    <div class="menu_button"><i class="fa-solid fa-car"></i> &nbsp;view takeout menu</div>
                </div>
          </div>
        </div>
    </div>
    <div class="menu_advises">
      <div class="advise_card">
        <h3 class="advise_card_title">hors d'oeuvres</h3>
        <ul>
          <li>
            <div class="title_and_price"><span class="dish_name">Hai salmon nigiri</span><span>$48</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">Humi masu salad</span><span>$21</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">Tekami with crab</span><span>$32</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">California rolls</span><span>$22</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
        </ul>
      </div>
      <div class="advise_card advise_card_image">
        
        <div class="overlay">
          <h3 class="advise_card_title">Main Course</h3>
          <ul>
          <li>
            <div class="title_and_price"><span class="dish_name">Braised abalone</span><span>$52</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">twice cooked pork</span><span>$21</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">kung pao chicken</span><span>$32</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">char siu & sushis</span><span>$48</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
        </ul>
        </div>
      </div>
      <div class="advise_card">
        <h3 class="advise_card_title">desserts</h3>
        <ul>
          <li>
            <div class="title_and_price"><span class="dish_name">Chocolate ball cake</span><span>$13</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">lime pie with crust</span><span>$14</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">raspberry pear cake</span><span>$18</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
          <li>
            <div class="title_and_price"><span class="dish_name">cafè au lait</span><span>$6</span></div>
            <p>lorem ipsum consectetur lorem</p>
          </li>
        </ul>
      </div>
    </div>
    <div class="braised_abalone_bg">
      <div class="braised_abalone_menu">
        
                
                <div class="header_text abalone">
                    <div class="abalone_price_cont">
                      <p class="white_title">Braised Albalone</p>
                      <span>$52</span>
                    </div>
                    <hr>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi commodi dolores odit sit eaque! Aperiam totam vero mollitia maxime unde ipsa, numquam dolores? Iste nulla velit ipsa in consectetur officiis.</p>
                    <div class="menu_button">view in the menu</div>
                </div>
          
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Main',
    data(){
      return{
        newsArr: [
          {
            pic: require("../assets/layout-images/images/blog92x.jpg"),
            title: 'the best coffee in town' ,
            credits: 'by Admin | January 7th, 2020 | Categories: News',
          },
          {
            pic: require("../assets/layout-images/images/blog72x.jpg"),
            title: 'discover our new menu',
            credits: 'by Admin | January 7th, 2020 | Categories: News',
          },
          {
            pic: require("../assets/layout-images/images/blog82x.jpg"),
            title: 'we now accept square!',
            credits:'by Admin | January 7th, 2020 | Categories: News' ,
          }
        ]
      }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/global.scss";
@import "../assets/vars.scss";
@import '../assets/main.scss';
</style>