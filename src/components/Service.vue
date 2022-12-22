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
    <div class="card book">
        <img src="/img/h-2-port-img-4.jpg" alt="">
        <div class="over">
            <h4>Illustration of novels</h4>
            <span>Illustration</span>
        </div>
        
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
.book{
    position: relative;
    cursor: pointer;
}

.book:hover .over{
    display: block;
}

.over{
    background-color: white;
    width: 220px;
    padding: 10px 20px;
    position: absolute;
    top: 50%;
    display: none;
}

</style>