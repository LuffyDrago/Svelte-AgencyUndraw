<footer class="footer-Container">
    <div class="first-footer">
        <div class="footer-column">
            <h4>HELPFUL LINK</h4>
            <p>About</p>
            <p>Life at Unigget</p>
            <p>Giving Back</p>
            <p>Meet the Team</p>
            <p>Themes</p>
        </div>

        <div class="footer-column">
            <h4>SUPPORTS</h4>
            <p>Documentation</p>
            <p>Support Forum</p>
            <p>Support Policy</p>
            <p>Faqs</p>
            <p>Contact Form</p>
        </div>

        <div class="footer-column">
            <h4>TERMS</h4>
            <p>Terms of Use</p>
            <p>Copyright Notice</p>
            <p>Refund Policy</p>
            <p>Privacy Policy</p>
        </div>


    </div>
    <div class="footer-image">
        <img src="/assets/img/randomt.svg" alt="footers">
    </div>

</footer>


<style>
    footer{
        max-width: 1980px;
        margin: auto;
    }
    .footer-Container{
        display: flex;
        justify-content: space-evenly;
        max-height: 600px;
       
    }

    .first-footer{
        display: flex;
        justify-content: center;
        gap:3rem;
        line-height:2;
        font-size: 0.95rem;
        margin-top: 6rem;
    }

    .footer-image{
        width: 50%;
    }
    img{
        width: 100%;
        height: 100%;
        max-width: 800px;
    }

    p{
        color:#656275;
    }

    @media screen and (max-width: 1000px) {
        .footer-Container{
            display: flex;
            flex-direction: column-reverse;
            
        }
        .first-footer{
            display: flex;
            flex-direction: column;
        }

        .footer-image{
            padding-top: 2rem;
            align-self:center;
            width: 70%;

        }
    }

</style>