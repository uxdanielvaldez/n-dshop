<template>
    <div>
        <div class="container" style="margin-top:60px;">
            <div class="row">
                <div class="col-md-3 img1"><h1>Women</h1></div>
                <div class="col-md-3 img2"><h1>Man</h1></div>
                <div class="col-md-3 img3"><h1>Shoes</h1></div>
            </div>
        </div>

    </div>
</template>

<style>
    .img1 {
        background-image: url('../assets/bg.jpg');
        height: 40vh;
        margin-left: 70px;
        background-repeat: no-repeat;
        background-position: center;
        cursor: pointer;
        

    }
    .img2 {
        background-image: url('../assets/bg.jpg');
        height: 40vh;
        margin-left: 70px;
        background-repeat: no-repeat;
        background-position: center;
        cursor: pointer;
     
    }
    .img3 {
        background-image: url('../assets/bg.jpg');
        height: 40vh;
        margin-left: 70px;
        background-repeat: no-repeat;
        background-position: center;
        cursor: pointer;
        
    }

    .img1 h1 {
        font-family: 'Roboto', sans-serif;
        font-size: 40px;
        font-weight: 300;
        text-transform: uppercase;
        text-align: center;
        margin-top: 60%;
        color: #ffffff;
        text-shadow: 0px 3px 8px rgb(0, 0, 0);
        transition: all .5s ease-in-out;
        -webkit-filter: grayscale(0%);
        filter: grayscale(0%);
        
    }

    .img1 h1:hover {
        font-size: 50px;
        
    }

    .img1:hover {
        -webkit-filter: grayscale(100%);
        filter: grayscale(100%);
        transition: all .5s ease-in-out;
    }

    .img2 h1 {
        font-family: 'Roboto', sans-serif;
        font-size: 40px;
        font-weight: 300;
        text-transform: uppercase;
        text-align: center;
        margin-top: 60%;
        color: #ffffff;
        text-shadow: 0px 3px 8px rgb(0, 0, 0);
        transition: all .5s ease-in-out;
        -webkit-filter: grayscale(0%);
        filter: grayscale(0%);
    }

    .img2 h1:hover {
        font-size: 50px;
    }

    .img2:hover {
        -webkit-filter: grayscale(100%);
        filter: grayscale(100%);
        transition: all .5s ease-in-out;
    }

    .img3 h1 {
        font-family: 'Roboto', sans-serif;
        font-size: 40px;
        font-weight: 300;
        text-transform: uppercase;
        text-align: center;
        margin-top: 60%;
        color: #ffffff;
        text-shadow: 0px 3px 8px rgb(0, 0, 0);
        transition: all .5s ease-in-out;
        -webkit-filter: grayscale(0%);
        filter: grayscale(0%);
    }

    .img3 h1:hover {
        font-size: 50px;
    }

    .img3:hover {
        -webkit-filter: grayscale(100%);
        filter: grayscale(100%);
        transition: all .5s ease-in-out;
    }

    @media only screen and (max-width: 1000px) {
    .img1 {
        background-image: url('../assets/bg.jpg');
        height: 40vh;
        width: 310px;
        margin-left: 10%;
        margin-top: 10px;
        background-repeat: no-repeat;
        background-position: center;
    }
    .img2 {
        background-image: url('../assets/bg.jpg');
        height: 40vh;
        width: 310px;
        margin-left: 10%;
        margin-top: 10px;
        background-repeat: no-repeat;
        background-position: center;
    }
    .img3 {
        background-image: url('../assets/bg.jpg');
        height: 40vh;
        width: 310px;
        margin-top: 10px;
        margin-left: 10%;
        background-repeat: no-repeat;
        background-position: center;
    }
    }
</style>