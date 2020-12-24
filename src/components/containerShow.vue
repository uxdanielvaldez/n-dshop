<template>
    <div>
        <div class="slide w-100 p-3">
            <h1>LOREM IPSUM</h1>
            <h6>LOREM IPSUM</h6>
            <button>LOREM IPSUM</button>
        </div>
    </div>
</template>

<style>

    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');

    .slide {
        height: 100vh;
        background-image: url('../assets/bg_home.jpg');
        background-size: cover;
        background-attachment: fixed;
        background-repeat: no-repeat;

        text-align: center;
    }

    .slide h1 {
        font-size: 80px;
        text-shadow: 0px 3px 8px rgba(0,0,0,0.8);

        color: #ffffff;

        padding-top: 20%;
        
    }

    .slide > h6 {
        color: #ffffff;

        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        text-shadow: 0px 3px 8px rgba(0,0,0,0.8);

        padding-bottom: 10px;
    }

    .slide > button {
        width: 220px;
        height: 70px;

        border: 2px solid #ffffff;

        background-color: transparent;
        text-shadow: 0px 3px 8px rgba(0,0,0,0.8);
        box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.473);
        color: #ffffff;
    }

    @media only screen and (max-width: 1000px) {
    .slide {
        height: 90vh;
        background-image: url('../assets/bg_home.jpg');
        background-size: cover;
        background-attachment: fixed;
        background-repeat: no-repeat;
        background-position: center;

        text-align: center;
    }

    .slide h1 {
        font-size: 40px;
        text-shadow: 0px 3px 8px rgba(0,0,0,0.8);

        color: #ffffff;

        padding-top: 50%;
        
    }

    .slide > h6 {
        color: #ffffff;

        font-family: 'Roboto', sans-serif;
        font-weight: 300;
        text-shadow: 0px 3px 8px rgba(0,0,0,0.8);

        padding-bottom: 10px;
    }

    .slide > button {
        width: 160px;
        height: 40px;

        border: 2px solid #ffffff;

        background-color: transparent;
        text-shadow: 0px 3px 8px rgba(0,0,0,0.8);
        box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.473);
        color: #ffffff;
    }
    }

</style>