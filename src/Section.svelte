<main class="whole">
    <div class="description">
        <div class="word-sectior">
        <h4 class="firstheader">Design Better</h4>
        <h1 class="secondheader">The Digital <br>
        Design Agency</h1>
        <button class="section-button">Our Work</button>
        </div>


        <div class="image-sector">
        <img src="/assets/img/sharelink.svg" alt="share link">
        </div>
        
    </div>

    <div class="destination">
        <div class="destination-sector">
            <img class="rotate" src="/assets/img/location.svg" alt="destination">
        </div>
        <div class="wacthvideo">
            <div class="rlative">
                <svg viewBox="0 0 320 320" width="120" >
                    <path stroke-width="5"
                    stroke="#E6E6E6" stroke-dasharray="15" fill="none"
                    d="M160 10
                        a 150 150 0 0 1 0 300
                        a 150 150 0 0 1 0 -300"
                    />
                </svg>
                <div class="absolt">
                            <button class="watch-video">
                        <svg
                        viewBox="0 0 24 24"
                        width="24"
                        height="24"
                        stroke="white"
                        stroke-width="0"
                        fill="#565786"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="css-i6dzq1"
                        >
                        <circle cx="12" cy="12" r="10"></circle>
                        <polygon
                            class="fill-white"
                            points="10 8 16 12 10 16 10 8"
                        ></polygon>
                        </svg>
                        Watch Video
                    </button>
                    </div>
            </div>
            <!-- <button class="watch-video">
                <svg
                viewBox="0 0 24 24"
                width="24"
                height="24"
                stroke="white"
                stroke-width="0"
                fill="#565786"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="css-i6dzq1"
                >
                <circle cx="12" cy="12" r="10"></circle>
                <polygon
                    class="fill-white"
                    points="10 8 16 12 10 16 10 8"
                ></polygon>
                </svg>
                Watch Video
            </button> -->
        </div>
    </div>


    <div class="branding-sect">
        <div class="brand-title">
            <h1 class="titlebrand2">
                BRANDING DO <br>
                YOU KNOW WHO <br>
                YOU ARE
            </h1>
            <div class="paragragh-brand">
                <p class="first-lorems">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin et suscipit dolor.<br>
                    Ut eget elit sit amet urna sodales rhoncus a vel dolor. <br>
                    Donec efficitur purus est, vehicula dapibus mi molestie vel. <br>
                    
                </p>

                <p class="second-lorems">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br>
                    Proin et suscipit dolor. Ut eget elit sit amet urna sodales rhoncus a vel <br>
                    Donec efficitur purus est, vehicula dapibus mi molestie vel. <br>
                    Pellentesque sagittis nisl ac risus faucibus, sit amet rhoncus urna dictum.<br> 
                    Duis ac arcu tristique, viverra tortor sit.
                </p>
                <button class="section-buttonpar">Our Work</button>
            </div>
        </div>
        <div class="brand-images">
            <img src="/assets/img/reflect.svg" alt="careers">
        </div>
    </div>


    <div class="user-experience">
    <div class="usersection-images">
        <img src="/assets/img/unlock.svg" alt="careers">
    </div>
    <div class="user-paragraph">
        <h1 class="titlebrand1">
            Powering The <br>
            World's Best User <br>
            Experiences
        </h1>
        <div class="paragragh-brand">
            <p class="second-lorems2">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin et suscipit dolor.<br>
                Ut eget elit sit amet urna sodales rhoncus a vel dolor. <br>
                Donec efficitur purus est, vehicula dapibus mi molestie vel. <br>
                
            </p>
        </div>
        <button class="section-buttonpar">Our Work</button>
    </div>
    </div>
</main>

<style>
    .whole{
        max-width: 1980px;
        margin: auto;
    }
    .description{
        display:flex;
        flex-direction: row;
        margin-left:5rem;
        margin-bottom: 8rem;
        /* background-color: #000; */
    }
    .firstheader{
        text-transform: uppercase;
        letter-spacing: 1.5px;
        font-size: 0.75em;
    }
    .secondheader{
        padding-top: 2rem;
        font-size: 3em;
        padding-bottom: 2rem;
    }
    .section-button{
        padding: 20px 40px;
        border-radius: 3px;
        cursor: pointer;
        border: none;
        text-transform: uppercase;
        background-color: #565786;
        color:#fff;
        font-weight: 400;
        letter-spacing: 2.3px;
    }

    .section-buttonpar{
        padding: 20px 40px;
        border-radius: 3px;
        cursor: pointer;
        border: none;
        text-transform: uppercase;
        background-color: #eeedf2;
        color:#000;
        font-weight: 600;
        letter-spacing: 2.3px;
    }
    
    img{
        width: 100%;
        height: 100%;
        max-width: 800px;
    }
    .destination-sector{
        width: 50%;
    }
    .rotate{
        -webkit-transform: scaleX(-1);
        transform: scaleX(-1);
    }
    .destination{
        display: flex;
        justify-content: space-evenly;
        max-height: 600px;
        margin-bottom: 8rem;
    }

    .fill-white {
        fill: #fff;
    }

    .wacthvideo {
        display: flex;
        /* height: 60px; */
        margin-top:5rem;
        padding-bottom: 20px;   
    }

    .rlative{
        position: relative;
       
    }
    .absolt{
        position: absolute;
        top:40px;
        left:40px;
    }

    .watch-video {
        display: flex;
        flex-direction: column;
        align-items: center;
        background: none;
        outline: none;
        border: none;
        font-size: 1rem;
        letter-spacing: 2px;
        text-transform: uppercase;
        font-weight: 600;     
       
    }

    .watch-video svg {
        height:80px;
        width:80px;
        box-shadow: 0 0 0 3px #f2f2f2;
        border-radius:50%;
        background-color: #f6f5f8;
    }

    .branding-sect{
        display: flex;
        justify-content: space-evenly;
        max-height: 600px;
        margin-bottom: 8rem;
    }
    .paragragh-brand{
        font-size: 0.75rem;
        word-break: keep-all;
        line-height: 2;
        padding-top: 2rem;
    }
    .second-lorems{
        padding-top: 2rem;
        padding-bottom: 2rem;
    }
    .brand-images{
        width:50%;
    }
    /* .titlebrand{
        font-size:3rem;
    } */
    .user-experience{
        display: flex;
        justify-content: space-evenly;
        max-height: 600px;
        margin-bottom: 8rem;  
    }
    .usersection-images{
        width:50%;
    }
    .second-lorems2{
        padding-bottom: 2rem;
    }
    /* .user-paragraph{
        width:50%;
    } */
    /* .titlebrand2{
        font-size: 1rem;
    } */

    @media screen and (max-width: 1000px) {
        .whole{
            overflow-x: hidden;
        }
        .description{
            display: flex;
            flex-direction: column;
            margin:0;
        }
        .image-sector{
            padding-top: 1rem;
            align-self:center;
        }

        .branding-sect{
            display: flex;
            flex-direction: column;
        }
        .brand-title{
            font-size: 0.75rem;
        }
        .brand-images{
            padding-top: 1rem;
            align-self:center;
            width:100%;
        }

        .user-experience{
            padding-top: 2rem;
            display:flex;
            flex-direction: column-reverse;
        }

        .usersection-images{
            width:100%;
            padding-top: 2rem;
            align-self:center;
        }
        
    }




</style>