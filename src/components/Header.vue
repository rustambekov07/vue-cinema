<template >

     <header class="header">
        <img src="@/assets/images/header__bg.png" alt="" class="header__banner">
        
        <div class="header__content">
            <div class="container">
                <h1 class="header__title">Kong: Skull Island</h1>
                <p class="header__subtitle">The film takes the viewer to the 70s of the last century. The protagonist organizes an expedition to the Skull island, always covered in fog, on which King Kong was once caught to find the missing brother and some mysterious substance. During...</p>
                
                <div class="header__btns">
                <a href="" class="btn">Watch now</a>    
                <a href="" class="btn">Download</a>    
                </div>
                
            </div>    
        </div>
        
    </header> 

</template>
<script>
export default {
    
}
</script>
<style >
    .header {
    min-height: 80vh;
    position: relative;
    display: flex;
}

.header__banner {
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
    object-fit: cover;

}

.header__content {
    background: rgba(7, 15, 25, 0.75);
    width: 100%;

}

.header__title {
    color: white;
    padding: 183px 0 30px;
    line-height: 78px;
    font-size: 64px;
    font-family: 'Montserrat-Bold';
}

.header__subtitle {
    max-width: 570px;
    color: #C8C8C8;
    text-align: justify;
    line-height: 24px;
    padding-bottom: 50px;
}

.header__btns {
    display: flex;
    column-gap: 30px;
}

.btn {
    background: #F18128;
    color: black;
    padding: 17px 48px;
    border-radius: 4px;
    transition: 0.5s;
}

.btn:hover {
    background: #040D1F;
    color: white;
}

</style>