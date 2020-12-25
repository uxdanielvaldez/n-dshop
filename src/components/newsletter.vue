<template>
    <div>
        <div class="newsletter">
            <div class="form">
                <h1 class="title_form">Subcribe To Our Newsletter</h1>
                <h6 class="subtitle_form">Sign up for the weekly newsletter and build better ecommerce stores.</h6>
   
                <div class="row">
                    <div class="col-md-6">
                        <input type="text" class="form-control">
                        <br>
                        <button class="btn-send">Send</button>
                        <br>
                        <h6 class="subtitle_form">We respect your privacy, so we never share your info.</h6>
                        
                    </div>
                    
                </div>

            </div>
        </div>
    </div>
</template>

<style>
    
    .newsletter {
        width: 100%;
        height: 60vh;
        background-image: url('../assets/bg_home.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position: top;
        background-attachment: fixed;
        padding-top: 50px;

    }

    .form {
        width: 70%;
        height: 50vh;
        background-color: #ffffff;
        display: block;
        margin-left: auto;
        margin-right: auto;
        padding-top: 6%;
        -webkit-box-shadow: 0px 8px 26px 0px #000000; 
        box-shadow: 0px 8px 26px 0px #000000;
        
    }

    .title_form {
        font-family: 'Roboto', sans-serif;
        font-size: 40px;
        text-align: center;
        font-weight: 300;
    }

    .subtitle_form {
        font-family: 'Roboto', sans-serif;
        font-size: 16px;
        text-align: center;
        font-weight: 300;
        margin-bottom: 50px;
    }

    .col-md-6 {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }

    .col-md-6 > button{
        display: block;
        margin-left: auto;
        margin-right: auto;
    }

    .btn-send {
        width: 190px;
        height: 50px;
        border: solid 2px #000;
        background-color: transparent;

    }

</style>