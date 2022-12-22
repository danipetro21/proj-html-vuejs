<script>

</script>

<template>

    <div class="container">

        <div class="info">

            <h1>Devotion that <br> never <span class="final">ends</span></h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex quaerat quae ullam dolore, recusandae omnis minus.</p>
            <a href="#">READ MORE</a>
        </div>

        <div class="images">

            <img src="/img/h-2-slider-img-15.png" alt="">
            <img src="/img/h-2-slider-img-16.png" alt="">

            <img class="foglia t1" src="/img/h-2-slider-img-17.png" alt="">
            <img class="foglia t2" src="/img/short-slider-rev-1-img-2.png" alt="">
            <img class="foglia t3" src="/img/short-slider-rev-1-img-10.png" alt="">
            <img class="foglia t4" src="/img/short-slider-rev-1-img-7.png" alt="">
            <img class="foglia t5" src="/img/short-slider-rev-1-img-8.png" alt="">
            <img class="foglia t6" src="/img/short-slider-rev-1-img-6.png" alt="">

            




        </div>

    </div>

</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;

a{
    text-decoration: none;
}

.container{
    
    max-width: 1500px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin: 120px auto;
    


}
.info{
    width: 50%;
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 50px;

    a{
        width: 200px;
        border: 3px solid $border_btn_readmore;
        padding: 15px 27px;
        text-align: center;
        color: black;
    }
    a:hover{
        background-color: $btn_readmore_hover;
        color: white;
    }
}
.images{
    width: 50%;
    padding: 20px;
    display: flex;
    justify-content: center;

    position: relative;
}
h1{
    font-size: 5rem;
    line-height: 100px;
    font-weight: 200;
}
p{
    color: $p_color;
}

.foglia{
    position: absolute;
    object-fit: cover;
}
.t1{
    bottom: 0;
    right: 0;
}
.t2{
    right: 0;
}
.t3{
    left: 0;
}
.t4{
    bottom: 0;
    left: 50px;
}
.t5{
    top: 50%;
    left: 0;
}

.t6{
    top: 50%;
    right: -50px;
}



</style>