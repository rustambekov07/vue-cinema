<template>
        
<footer class="footer">
    <div class="container">

        <div class="footer__box">
            <div class="footer__box-left">

                <img  src="@/assets/images/Play.png" alt="" class="footer__box-img">

                <img src="@/assets/images/App Store.png" alt="">
            </div>

          <p class="footer__box-title">© PROWEB. В целях обучения 2021</p>

        </div>
    </div>

</footer> 
    

</template>
<script>
export default {
    
}
</script>
<style>
    .footer{
    background: linear-gradient(90deg, #FF8C30 0%, #9F4700 100%);
    padding: 24px 0;
}


.footer__box{
    display: flex;
    justify-content: space-between;
    align-items: center;
}


.footer__box-img{
    margin-right: 50px;
}


.footer__box-title{
    color: white;
    font-family: 'Comfortaa-Bold';
    font-size: 18px;
    line-height: 20px;
}


@media(max-width: 1100px) {
    .title{
        margin: 50px auto;
        font-size: 30px;
    }
    
    .item2{
        grid-column: span 4;
    }
    
    .item3{
        grid-column: span 2;
    }
}

@media(max-width: 992px) {}

@media(max-width: 768px) {
    .nav__link{
        flex-direction: column;
        padding-top: 50px;
    }
    
    .nav__list{
        column-gap: 15px;
    }
    
    .header__title{
        font-size: 55px;
        text-align: center;
    }
    
    .header__subtitle{
        margin: 0 auto;
    }
    
    .header__btns{
        justify-content: center;
    }
    
    .item1__subtitle{
        text-align: justify;
    }
    
    .footer__box{
        flex-direction: column;
        row-gap: 30px;
    }
}

@media(max-width: 576px) {
    .header__title{
        font-size: 40px;
        padding: 100px 0 30px;
    }
    
    .premier__content-img{
        display: flex;
        margin: 0 auto;
        width: 300px;
    }
    
    .btn{
        display: flex;
        flex-direction: column;
        max-width: max-content;
        margin: 0 auto;
    }
    
    .item3{
        grid-column: span 4;
    }
}

@media(max-width: 460px) {
    .item1__title{
        font-size: 30px;
    }
}

@media(max-width: 420px) {
    .header__title{
        font-size: 30px;
        
    }
    
    .header__btns{
        flex-wrap: wrap;
        row-gap: 30px;    
    }
    
    .btn{
        padding: 15px 35px;
    }
    
    .footer__box-title{
        font-size: 15px;
    }
}

@media(max-width: 350px) {
    .item1__title{
        font-size: 25px;
    }
}

</style>