<template>
    <div>

        <navbar class="nb"/>
        <slideshow />
        <br>
        <h1 class="title_categories">Shop by Categories</h1>
        <h6 class="subtitle_categories">Top Categories in this Week</h6>
        <categoriesBox class="category_box" />
        <br>
        <h1 class="title_t_products">Trending Products</h1>
        <h6 class="subtitle_t_products">Top view in this Week</h6>
        <trending />
        <br>
        <h1 class="title_b_products">Best Seller Products</h1>
        <h6 class="subtitle_b_products">Top sale in this week</h6>
        <bestseller />
        <br>
        <newsletter />

    </div>
</template>

<script>
import navbar from '../components/navBar'
import slideshow from  '../components/containerShow'
import categoriesBox from  '../components/categoriesHome'
import trending from '../components/trending'
import bestseller from '../components/bestsellerproducts'
import newsletter from '../components/newsletter'

export default {
   components: {
       navbar,
       slideshow,
       categoriesBox,
       trending,
       bestseller,
       newsletter

   } 
}
</script>

<style>

    .nb {
        position: fixed;
        width:100%;
        height: 140px;
        background-color: white;
        z-index: 2;
    }  

    .title_categories{
        padding-top: 20px;
        text-align: center;
        margin-top: 30px;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        font-size: 35px;
        color: rgba(49, 49, 49, 0.932);
    }

    .subtitle_categories{
        text-align: center;
        margin-top: 10px;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        font-size: 15px;
        color: rgba(49, 49, 49, 0.932);
    }

    .title_t_products{
        padding-top: 40px;
        text-align: center;
        margin-top: 30px;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        font-size: 35px;
        color: rgba(49, 49, 49, 0.932);
    }

    .subtitle_t_products{
        text-align: center;
        margin-top: 10px;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        font-size: 15px;
        color: rgba(49, 49, 49, 0.932);
    }

    .title_b_products{
        padding-top: 40px;
        text-align: center;
        margin-top: 30px;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        font-size: 35px;
        color: rgba(49, 49, 49, 0.932);
    }

    .subtitle_b_products{
        text-align: center;
        margin-top: 10px;
        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        font-size: 15px;
        color: rgba(49, 49, 49, 0.932);
    }

    /* .category_box {
        z-index: -2;
    } */

</style>