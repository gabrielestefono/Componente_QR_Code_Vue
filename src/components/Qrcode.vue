<template>
    <div class="content">
        <img src="../assets/img/image-qr-code.png" class="content__img">
        <h3 class="content__title">Improve your front-end skills by building projects</h3>
        <p class="content__text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
</template>
<script>
    export default {
        name: 'Qrcode'
    }
</script>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100;200;300;400;500;600;700;800;900&display=swap');
    .content{
        width: 320px;
        height: 497px;
        background-color: white;
        border-radius: 20px;
        display: flex;
        flex-direction: column;
    }

    .content__img{
        width: 288px;
        height: 288px;
        margin: 0 auto;
        display: block;
        margin-top: 16px;
        border-radius: 10px;
    }

    .content__title{
        font-family: 'Outfit', sans-serif;
        font-weight: 700;
        font-size: 22px;
        color: #1F314F;
        width: 288px;
        margin: 0 auto;
        text-align: center;
        margin-top: 16px;
    }

    .content__text{
        color: #7D889E;
        font-size: 15px;
        font-family: 'Outfit', sans-serif;
        width: 256px;
        text-align: center;
        margin: 0 auto;
        margin-top: 16px;
    }


</style>