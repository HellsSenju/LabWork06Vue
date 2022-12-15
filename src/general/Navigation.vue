<script setup>
</script>

<template>
    <nav> 
        <ul class="nav nav-pills nav-fill">
            <li class="nav-item"><a class="nav-link navText" href="aboutCompany.html">О компании</a></li>
            <li class="nav-item"><a class="nav-link navText" href="SovietDir.html">Корпоративное управление</a></li>
            <li class="nav-item"><a class="nav-link navText" href="toShareholders.html">Акционерам</a></li>
            <li class="nav-item"><a class="nav-link navText" href="bussines.html">Бизнес-направления</a></li>
            <li class="nav-item"><a class="nav-link navText" href="news.html">Пресс-центр</a></li>
            <li class="nav-item"><a class="nav-link navText" href="js1.html">Пользователи</a></li>
            <li class="nav-item"><a class="nav-link navText" href="js2.html">Мерч</a></li>
        </ul>
        <div class="dropdown">
            <button class="btn btn-lg btn-secondary dropdown-toggle" id="dropdownMenuButton1" type="button" data-bs-toggle="dropdown" aria-expanded="false">=</button>
            <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                <li><a class="dropdown-item" href="aboutCompany.html">О компании</a></li>
                <li><a class="dropdown-item" href="SovietDir.html">Корпоративное управление</a></li>
                <li><a class="dropdown-item" href="toShareholders.html">Акционерам</a></li>
                <li><a class="dropdown-item" href="bussines.html">Бизнес-направления</a></li>
                <li><a class="dropdown-item" href="news.html">Пресс-центр</a></li>
                <li><a class="dropdown-item" href="js1.html">Пользователи</a></li>
                <li><a class="dropdown-item" href="js2.html">Мерч</a></li>
            </ul>
        </div>
    </nav>
</template>

<style scoped>
nav {
	background-color: #faf3b7;
}

.dropdown{
    display: none;
}

.navTextMain{
    background-color: #55567b;
    color: #ffff;
    font-family: sans-serif;
    font-size: 16pt;
}

.navText{
    color: #ee8373;
    font-family: sans-serif;
    font-size: 16pt;
}

.nav-link:hover{
    color: #ee8373;
    background-color: #55567b;
}

@media screen and (max-width: 1100px) { 

    .dropdown{
        background-color: #55567b;
        display:block;       
    }

    .dropdown-menu{
        background-color: #faf3b7;
        width: 100vw;
    }

    .dropdown .btn{
        font-size: 30pt;
    }
    
    .dropdown-item{
        font-size: 30pt;
    }
    
    .dropdown-item:hover{
        color: #ee8373;
        background-color: #55567b;
    }

    .nav-pills {
        display: none; 
    }
}

</style>