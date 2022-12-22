<script>

</script>

<template>

    <div class="container">

        <div class="info">

            <h1>Devotion that <br> never <i><b>ends</b></i></h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex quaerat quae ullam dolore, recusandae omnis minus.</p>
            <a href="#">READ MORE</a>
        </div>

        <div class="images">

            <img src="/img/h-2-slider-img-15.png" alt="">
            <img src="/img/h-2-slider-img-16.png" alt="">

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
    width: 40%;
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 50px;

    a{
        width: 150px;
        border: 2px solid $border_btn_readmore;
        padding: 10px 20px;
        text-align: center;
        color: black;
    }
}
.images{
    width: 40%;
    padding: 20px;
    display: flex;
    justify-content: center;
    img{
        width: 300px;
    }
}
h1{
    font-size: 5rem;
    line-height: 100px;
    font-weight: 200;
}
p{
    color: $p_color;
}

</style>