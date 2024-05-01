<template >

    
    <nav>
        <div class="container">
            <div class="nav__link">
                <a href="" class="nav__link-logo">
                    <img src="@/assets/images/logo.png" alt=""> CINEMA
                </a>
                
                <ul class="nav__list">
                    
                    <li><a href="" class="nav__list-link">Films</a></li>
                    <li><a href="" class="nav__list-link">Serials</a></li>
                    <li><a href="" class="nav__list-link">Cartoons</a></li>
                    <li><a href="" class="nav__list-link">Collections</a></li>
                    
                </ul>
                
            </div>
        </div>
        
    </nav>

                    

    

</template>

<script>

export default {
  
}
</script>
<style>
  .container {
    max-width: 1140px;
    margin: 0 auto;
    padding: 0 15px;
}

nav {
    background: #000;
}

.nav__link {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav__link-logo {
    color: white;
    font-size: 18px;
    font-family: 'Comfortaa-Bold';
    line-height: 20px;
}

.nav__list {
    display: flex;
    column-gap: 30px;
}

.nav__list-link {
    color: white;
    padding: 42px 0;
    display: flex;
    justify-content: center;
    position: relative;
    transition: 0.5s;
}

.nav__list-link:hover {
    color: #ED8E00;

}

.nav__list-link::before {
    content: '';
    position: absolute;
    height: 2px;
    background: #ED8E00;
    width: 0;
    bottom: 0;
    transition: 0.5s;
}

.nav__list-link:hover::before {
    width: 100%;
}

</style>