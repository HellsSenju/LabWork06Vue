<script setup>
</script>

<template>
    <section class = "directors text-center">
        <h1>Совет Директоров:</h1>
        <img src = "../img/Directors1.png" class="mx-auto d-block imageBody">
        <br>
        <img src = "../img/Directors2.png"  class="mx-auto d-block imageBody">
        <h1>Уставы:</h1>
    </section>

    <section class = "ystav text-center mx-auto">
        <br>
        <a href="Устав акционерного общества 2022.pdf" download>Устав акционерного общества 2022</a>
        <br>
        <a href="Положение об собрании.pdf" download>Положение об собрании</a>
        <br>
        <br>
        
    </section>
    <br>
    <br> 
</template>

<style scoped>
.imageBody{
    width: 60%;
}

.directors h1{
	margin-top: 10px;
    font-size: 35pt;
    color: #55567b;
}

.directors h2{
    font-size: 35pt;
    color: #55567b; 
	width: 13%;	
}

.ystav{
    background-color: #ee8373;
	width: 60%;
}

.ystav a{
    text-decoration: none; 
    font-size: 20pt;
    color: #55567b; 
    margin-left: 30px;
    margin-right: 30px; 
}
</style>