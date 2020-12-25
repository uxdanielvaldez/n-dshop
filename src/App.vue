<template>
<div>
  <navbar class="nb" />
    <router-view/>
  <footerpage />
</div>
</template>

<script>
import navbar from './components/navBar'
import footerpage from './components/footer'
export default {
  components: {
    navbar,
    footerpage
  }
  
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');

    * {
        margin: 0;
        padding: 0;
        font-family: 'Roboto', sans-serif;
    }

    .nb {
        position: fixed;
        width:100%;
        height: 140px;
        background-color: white;
        z-index: 2;
    } 
</style>
