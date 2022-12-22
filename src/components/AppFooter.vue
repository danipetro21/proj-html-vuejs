<script>

</script>

<template>
    <section id="footer">

        <div class="footer-top">

            <div class="card">
                <img src="/img/h-2-blog-img-1.jpg" alt="">
                <div class="calendar">
                    <span class="number final">07</span>
                    <span class="month">MAY '19</span>
                </div>
                <h1>This way, loves: a detailed guide <br> through new desing</h1>
                <span class="signature"><i>by Emily Fields</i></span>

            </div>
            <div class="card">
                <img src="/img/h-2-blog-img-2.jpg" alt="">
                <div class="calendar">
                    <span class="number final">07</span>
                    <span class="month">MAY '19</span>
                </div>
                <h1>I try to give people a different way <br> of looking art</h1>
                <span class="signature"><i>by Emily Fields</i></span>

            </div>
            <div class="card">
                <img src="/img/h-2-blog-img-3.jpg" alt="">
                <div class="calendar">
                    <span class="number final">07</span>
                    <span class="month">MAY '19</span>
                </div>
                <h1>Introduce Richard Laperrière of <br> those amazing features</h1>
                <span class="signature"><i>by Emily Fields</i></span>
            </div>

        </div>


        <div class="footer-bottom">


            <div class="footer-box">

                <div class="logo">
                    <img src="/img/logo-sidearea-1.png" alt="">
                    <span>Let's Get Creative</span>
                </div>

                <div class="contact">
                    <span>maree.qode@gmail.com</span>
                    <span>+44645 321 789</span>

                </div>

                <div class="location">
                    <span>Avenue d'Aiferghem 10</span>
                    <span>1040 Brussels, Belgium</span>


                </div>

                <div class="social">
                    <span>Stay in touch with us</span>
                    <ul>
                        <li><a href=""><i class="fa-brands fa-twitter"></i></a></li>
                        <li><a href=""><i class="fa-brands fa-pinterest-p"></i></a></li>
                        <li><a href=""><i class="fa-brands fa-facebook-f"></i></a></li>
                        <li><a href=""><i class="fa-brands fa-linkedin-in"></i></a></li>
                    </ul>

                </div>
            </div>
        </div>

    </section>
</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;

#footer {
    width: 100%;
}

.footer-top {
    width: 60%;
    display: flex;
    gap: 20px;
    margin: 100px auto;
}

.signature {
    font-size: 0.8rem;

}

.card {
    width: calc(100%/3);
    position: relative;

    h1 {
        margin: 20px 0;
        font-size: 1.3rem;
    }

    img {
        width: 100%;
    }
}

.calendar {
    text-align: center;
    width: 70px;
    display: flex;
    flex-direction: column;
    position: absolute;
    top: -15px;
    left: 15px;
}

.number {
    background-color: $calendar_number;
    padding: 10px 3px;
    font-size: 30px;
    font-weight: 900;
}

.month {
    background-color: $calendar_month;
    padding: 5px 3px;
    font-size: 12px;
}

.footer-bottom {
    width: 100%;
    background-color: $footer;
    padding: 60px 0;
}

.footer-box {
    width: 60%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    

    span {
        display: block;
        margin: 15px 0;
    }

    ul {
        display: flex;
        gap: 20px;
        justify-content: space-between;
    }


    
}


</style>