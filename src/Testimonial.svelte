<div class="Testimonial">
    <div class="Testimonial-details">
    <h2 class="header-testimonial">Testimonial</h2>
    <p class="Paragraph-testimonial">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin et suscipit dolor.<br>
        Ut eget elit sit amet urna sodales rhoncus a vel dolor. <br>
        
    </p>
    </div>

    <div class="carousel-testimonial">
        <div class="card-testimony">
            <div class="cards-paragraphs">
                <p class="Paragraph-testimonial">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
                    Ut eget elit sit amet urna sodales rhoncus a vel dolor. <br>
                    Donec efficitur purus est, vehicula dapibus mi molestie vel. <br>  
                </p>

                <div class="round-testimony">
                    <div class="avatars">
                        <img src="/assets/img/male.svg" alt="male avatars" width="100%">
                    </div>
                    <div class="avatars-details">
                        <h5>Alexa Tenorio </h5>
                        <h7>Head of marketing, Sketch App</h7>
                    </div>
                </div>

            </div>
        </div>

            <!-- <2>SECOND CARD</2> -->
        <div class="card-testimony">
            <div class="cards-paragraphs">
                <p class="Paragraph-testimonial">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
                    Ut eget elit sit amet urna sodales rhoncus a vel dolor. <br>
                    Donec efficitur purus est, vehicula dapibus mi molestie vel. <br>  
                </p>

                <div class="round-testimony">
                    <div class="avatars">
                        <img src="/assets/img/male.svg" alt="male avatars" width="100%">
                    </div>
                    <div class="avatars-details">
                        <h5>Alexa Tenorio </h5>
                        <h7>Head of marketing, Sketch App</h7>
                    </div>
                </div>

            </div>
        </div>

          <!-- <2>SECOND CARD</2> -->
          <div class="card-testimony">
            <div class="cards-paragraphs">
                <p class="Paragraph-testimonial">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
                    Ut eget elit sit amet urna sodales rhoncus a vel dolor. <br>
                    Donec efficitur purus est, vehicula dapibus mi molestie vel. <br>  
                </p>

                <div class="round-testimony">
                    <div class="avatars">
                        <img src="/assets/img/male.svg" alt="male avatars" width="100%">
                    </div>
                    <div class="avatars-details">
                        <h5>Alexa Tenorio </h5>
                        <h7>Head of marketing, Sketch App</h7>
                    </div>
                </div>

            </div>
        </div>




    </div>

    




</div>


<style>
    .Testimonial{
        margin-bottom: 4rem;
    }

    .Testimonial-details{
        text-align: center;
    }
    .Paragraph-testimonial{
        line-height: 2;
        font-size: 0.8rem;
    }

    .round-testimony{
        display: flex;
        gap:1rem;
        padding-top: 2rem;
    }
    .avatars {
       max-width: 40px;
    }
    
    .card-testimony{
    min-width: 330px;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0.75rem;
    padding: 3rem;
    /* padding: 40px 20px; */
    justify-content: space-around;
    box-shadow: 0 3px 10px rgb(0 0 0 / 0.2);
    }

    .carousel-testimonial {
    overflow: scroll;
    display: flex;
    flex-direction: row;
    scroll-snap-align: center;
    -webkit-animation: scroll 20s linear infinite;
    animation: scroll 20s linear infinite;
    width: calc(300px * 8);
    scrollbar-color: transparent transparent;
    scrollbar-width: none;
    scroll-behavior: smooth;
    scroll-snap-type: x mandatory;
}

*::-webkit-scrollbar {
    width: 0;
    display: none;
}

*::-webkit-scrollbar-track {
    background: transparent;
}

*::-webkit-scrollbar-thumb {
    background: transparent;
    border: none;
}

* {
    -ms-overflow-style: none;
}

.carousel-testimonial::before,
.carousel-testimonial::after {
    content: "";
    position: absolute;
    width: 300px;
    z-index: 2;
}

.carousel-testimonial::after {
    right: 0;
    top: 0;
    transform: rotateZ(180deg);
}

@keyframes scroll {
    0% {
        transform: translateX(0);
    }

    100% {
        transform: translateX(calc(-300px * 3));
    }
}


@media screen and (max-width: 1000px) {
        .Testimonial{
            overflow-x: hidden;
            padding-bottom: 3rem;
        }
    }

</style>