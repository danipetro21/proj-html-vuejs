<script>

</script>

<template>

<div class="grid">

    <div class="card">
        <img src="/img/h-2-port-img-1.jpg" alt="">
    </div>
    <div class="card">
        <img src="/img/h-2-port-img-2.jpg" alt="">
        
    </div>
    <div class="card">
        <img src="/img/h-2-port-img-3.jpg" alt="">
        
    </div>
    <div class="card">
        <img src="/img/h-2-port-img-4.jpg" alt="">
        
    </div>
    <div class="card">
        <img src="/img/h-2-port-img-5.jpg" alt="">
        
    </div>
    <div class="card">
        <img src="/img/h-2-port-img-6.jpg" alt="">
        
    </div>

</div>

</template>

<style lang="scss" scoped>

.grid{
    display: flex;
    flex-wrap: wrap;
}

.card{
    width: calc(100%/3);

    img{
        width: 100%;
        height: 100%;
        object-fit: cover;

    }
}

</style>