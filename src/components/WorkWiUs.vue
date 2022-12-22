<script>

</script>

<template>


    <section id="working-process">

        <div class="title">
            <h1>Working <i><span class="final">process</span></i></h1>
        </div>

        <div class="round-box">

            <div class="container">
                <div class="round">
                    <a id="bulb"><i class="fa-solid fa-lightbulb"></i></a>
                </div>

                <div class="info">
                    <h4>First theres an idea</h4>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="container">
                <div class="round">
                    <a id="comment"><i class="fa-regular fa-comment"></i></a>
                </div>
                <div class="info">
                    <h4>Then we talk about</h4>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                </div>
            </div>

            <div class="container">
                <div class="round">
                    <a id="cloud"><i class="fa-solid fa-cloud"></i></a>
                </div>
                <div class="info">
                    <h4>And we think about</h4>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                </div>
            </div>

            <div class="container">
                <div class="round">
                    <a id="pencil"><i class="fa-solid fa-pencil"></i></a>
                </div>
                <div class="info">
                    <h4>So we draw along</h4>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>

    </section>


    <section id="work-with-us">

        <h1>Want to work with us? Send us <i><span class="final">a message!</span></i></h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur molestiae quasi autem alias facere saepe dolores officia sit. Qui explicabo enim magnam molestiae aspernatur, voluptatem officiis nostrum hic! Similique, rem!</p>
        <a href="#">CONTACT</a>
    </section>

</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;

h1 {
    font-size: 4rem;
    font-weight: 200;
}
a{
    text-decoration: none;
}
p {
        color: $p_color;
    }

#working-process {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.title {
    margin-top: 100px;


}

.round-box {
    width: 100%;
    display: flex;
    justify-content: space-between;
    background-image: url("/svg/svg-3.svg");
    background-size: 83%;
    background-repeat: no-repeat;
    background-position: 100px 50px;
    margin: 100px;

}

//colori icone

#bulb {
    color: $round_bulb;
}

#comment {
    color: $round_commment;
}

#cloud {
    color: $round_cloud;
}

#pencil {
    color: $round_pencil;
}

.round {

    display: flex;
    justify-content: center;

    a {
        background-color: $background_rond;
        padding: 50px;
        border-radius: 50%;
        font-size: 3rem;
        margin: 30px 0;
    }

}

.info {
    text-align: center;
    width: 250px;


}

#work-with-us{
    text-align: center;
    display: flex;
    justify-content: center;
    flex-direction: column;
    gap: 50px;
    align-items: center;
    height: 500px;
    background-image: url("img/h-2-background-1.jpg");

    p{
        width: 80%;
    }

    a{
        
        border: transparent;
        cursor: pointer;
        background-color: $btn_contact;
        padding: 15px 50px;
        text-align: center;
        color: black;
    
    }
}
.final{
    font-family: 'Playfair Display', serif;
    font-style: italic; 
    font-weight: 700;
}

</style>