# OASIS-INFOBYTE-INTERNSHIP

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=DM+Sans:ital,opsz,wght@0,9..40,100..1000;1,9..40,100..1000&family=Edu+VIC+WA+NT+Beginner:wght@400..700&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
        integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

</head>
<style>
    * {
        margin: 0;
        padding: 0;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

    }
    html{
        height: 100%;
    }
    body {
        position: relative;
        margin: 0 auto;
        min-height: 100%;
        /* padding-bottom: 6.74rem; */
    }

    nav {
        display: flex;
        align-items: center;
        justify-content: space-around;
        height: 80px;
        background-color: rgb(18, 18, 62);
    }

    nav ul {
        display: flex;
        justify-content: center;
    }

    nav ul li {
        list-style: none;
        margin: 0 23px;
        text-decoration: none;
    }

    nav ul li a:hover {
        text-decoration: none;
        color: rgb(112, 112, 256);

    }
    }

    .left {
        font-size: 2rem;
    }

    .firstsection {

        display: flex;
        justify-content: space-around;
        margin: 23px 0;


    }

    .firstsection>div {

        align-items: center;
        justify-content: space-around;
        width: 30%;
        margin: 15vh 0;
    }

    .leftsection {
        font-size: 75px;
        width: 50%;
        margin-top: 6ovh;
        /* margin: 30px 0; */
        /* margin: 70px 0; */
    }

    .thirdsection .btn {
        padding: 12px;
        background: purple;
        color: white;
        border: 2px solid violet;
        cursor: pointer;
        border-radius: 50px;
        font-size: 22px;
        margin-top: 25px;
        margin-bottom: 25px;
        /* margin-bottom: 23vh; */

    }

    .leftsection buttons {
        margin-top: 600vh;
    }

    .rightsection img {
        width: 100%;
        margin: 50px 0;
    }

    .right ul li a {
        color: white;
        text-decoration: none;
        font-size: 1.04rem;
    }

    .right ul li a:hover {
        color: rgb(112, 112, 256);
    }

    .left {
        color: white;
        font-size: 30px;
    }

    .secondSection h1 {
        margin: 50px 0;
        color: blueviolet;
        font-size: 1.9rem;

    }

    .red {
        color: blueviolet;
    }

    #element {
        color: rgb(170, 107, 228);
    }

    .secondSection {
        max-width: 80vw;
        margin: auto;
        padding-bottom: 100vh;

    }

    main hr {
        border: 0;
        background: #9c97f1;
        height: 1.2px;
        margin: 40px 84px;
    }

    .secondSection .box {
        background-color: blue;
        width: 80vw;
        height: 2px;
        margin: 56px 0;
        display: flex;

    }

    .secondSection .vertical {
        height: 93px;
        width: 1px;
        background-color: blue;
        margin: 0 100px;
    }

    .image-top {
        width: 23px;
        position: relative;
        top: -32px;
        left: -9px;
    }

    .vertical-title {
        position: relative;
        top: 75px;
        width: 150px;
        font-size: 20px;
        align-content: center;

    }

    .vertical-desc {
        position: relative;
        color: rgb(10, 10, 50);
        top: 100px;
        font-size: 20px;
        text-align: center;
        box-sizing: border-box;
    }

    footer {
        position: fixed;
        bottom: 0px;
    }

    #first ul {
        margin: 0px;
    }

    .second ul {
        justify-content: space-between;
    }

    .buttons .btn {
        margin-top: 20vh;
        border-radius: 5px;
        border: 1px solid purple;
    }

    .thirdsection {
        display: flex;
        justify-content: space-around;
        margin: 23px 0;


    }

    .thirdsection>div {
        width: 30%;
        display: flex;
        justify-content: space-around;
        margin: 23px 0;


    }

    .right_2 {
        font-size: 23px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        /* background-color: white; */
        color: blue;
        /* border: 1px solid black; */
        /* overflow: hidden; */

    }

    .thirdsection h3 {
        display: block;
        color: blueviolet;
        font-size: 30px;
        margin-top: 10px;
        margin-bottom: 10px;

    }

    .thirdsection .desc {
        text-align: center;
        color: blue;
        font-size: 30px;
        background-color: #dde8ea;
        border: 2px solid #dde8ea;
        border-radius: 50px;
        /* align-content: flex-start; */

    }

    .skill {
        font-size: 30px;
        font-weight: bold;
        color: blueviolet;
        text-align: center;
        margin-top: 10px;
        margin-bottom: 10px;


    }

    #skill_dec {
        color: black;
        font-weight: normal;
        color: blue;
        background: #dde8ea;
        border: 2px solid transparent;
        border-radius: 50px;

    }

    #skill_dec h2 {
        color: blueviolet;
        align-items: center;
        display: flex;
        align-items: end;
        margin-top: 10px;
        margin-bottom: 10px;
    }

    .contact_heading {
        font-size: 30px;
        font-weight: bold;
        color: blueviolet;
        text-align: center;
        margin-top: 10px;
        margin-bottom: 10px;


    }

    .contact_heading {
        text-align: center;
        color: blueviolet;
        font-size: 30px;
        background-color: #dde8ea;
        border: 2px solid #dde8ea;
        border-radius: 50px;
        margin-top: 10px;
        margin-bottom: 10 px;
    }

    #co_detail {
        color: red;
        margin-left: 10px;
        word-spacing: 5px;

    }

    .right_2 .description {
        color: navy;
    }

    section .description {
        color: navy;
    }

    section h3 {
        justify-content: center;
        color: green;
        display: inline;

    }

    section .right_2 {}

    #image_3 {
        width: 5vh;
        height: 5vh;
        border: 1px solid white;
        display: inline-flex;
        border-radius: 50%;
    }

    .contact_heading li {
        color: red;
        list-style: none;
    }

    .contact_heading .whatsapp {
        color: green;
    }

    .contact_heading .no {
        color: black;
    }

    .contact_heading .mail {
        color: rgb(100, 100, 100);
    }

    .contact_heading .gm {
        color: purple;
    }

    .contact_heading .linkedin {
        color: blue;
    }

    .contact_heading .lk {
        color: rgb(45, 114, 204);
    }

    .contact_heading .insta {
        color: green;
    }

    .contact_heading .id {
        padding-bottom: 10px;
        color: rgb(210, 29, 168);
    }

    footer{
        background-color: #2d2a30;
        right: 0;
        left: 0;
        position: relative;
        height: auto;
        width: 100vw;
        color: #fff;
        margin-bottom: 0;
    }
    .footer-content{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        text-align: center;
    }
    .footer-content h3{
        font-size: 1.8rem;
        font-weight: 400;
        text-transform: capitalize;
        padding-top: 10px;

    }
    .footer-content p{
        max-width: 500px;
        margin: 10px auto;
        line-height: 28px;
        font-size: 14px;

    }
    .social{
        list-style: none;
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 1rem 0 3rem 0;

    }
    .social li{
        margin: 0 10px;
    }
    .social a{
        text-decoration: none;
        color: #fff;

    }
    .social a i{
        font-size: 1.1rem;
        transition: color .4s ease;
    }
    .social a:hover i{
        color: aqua;

    }
    .footer-bottom{
        background:#000;
        width: 100vw;
        padding: 20px 0;
        text-align: center;
    }
    .footer-bottom p{
        font-size: 14px;
        word-spacing: 2px;
        text-transform: capitalize;

    }
    .footer-bottom span{
        text-transform: uppercase;
        opacity: .4;
        font-weight: 200;
    }
    .space {
        padding-left: 5px;
    }
</style>

<body>
    <header>

        <nav>
            <div class="left">My Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">home</a></li>
                    <li><a href="/">about</a></li>
                    <li><a href="/">contact me</a></li>
                    <li><a href="/">follow me</a></li>

                </ul>



            </div>

        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">Hi , My Name is <span class="red">Aadarsh</span> And I'm a <span
                    id="element"></span>
            </div>
            <div class="rightsection">
                <img src="pg.png" alt="">

                <br>
            </div>
            </div>
        </section>
        <section class="thirdsection">
            <div class="right_section">
                <div class="desc">
                    <h3>BIO</h3>
                    Hi, Friends My Name is Aadarsh and I'm a student.
                    I'm 19 year old. currently i am pursuing the engineering in electronics and telecommunication.
                    currently I'm studying the another skills like Web Developement,Data structure & Algorithm etc.
                    <div class="button">
                        <button class="btn">Download Resume</button>
                    </div>
                </div>
            </div>
            <div id="skill_dec">
                <div class="skill">SKILLS
                    <br>
                    <div id="skill_dec">
                        As a Electronics and Telecommunication student I've basic skills related to the semiconductors ,
                        sensors , any other equipment etc., and I'm eager to learn new technologies like devopps , AI&ML
                        also I've knowledge about the various programming languages like C , PYTHON , HTML , CSS &
                        JAVASCRIPT.
                        <div class="button">
                            <button class="btn">Visit Github</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="contact">
                <div class="contact_heading">
                    <h3>CONTACT</h3>
                    <li class="whatsapp"><i class="fa-brands fa-whatsapp"></i><br><i
                            class="fa-solid fa-arrow-down"></i><br><span class="no">+91 9322994030</span></li>
                    <li class="mail"><i class="fa-regular fa-envelope"></i><br><i
                            class="fa-solid fa-arrow-down"></i><br><span class="gm">Maskea291@gmail.com</span></li>
                    <li class="linkedin"><i class="fa-brands fa-linkedin"></i><br><i
                            class="fa-solid fa-arrow-down"></i><br><span class="lk">Maske Aadarsh</span></li>
                    <li class="insta"><i class="fa-brands fa-instagram"></i><br><i
                            class="fa-solid fa-arrow-down"></i><br><span class="id">AADARSH_M_07</span></li>
                    </p>
                </div>

            </div>
        </section>
        </div>
        <section class="secondSection">
            <h1>KNOWN LANGUAGES</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="c programming logo.png" alt="">
                    <div class="vertical-title">
                        C (2023)
                    </div>
                    <div class="vertical-desc">
                        The C language is studied year 2023 before joining the college & completed in the 5-6 months.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="python.png" alt="">
                    <div class="vertical-title">
                        PYTHON (2023)
                    </div>
                    <div class="vertical-desc">
                        i have completes studied the python language from august 2023 to march 2024.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="html_logo.png" alt="">
                    <div class="vertical-title">
                        HTML (2024)
                    </div>
                    <div class="vertical-desc">
                        i have completes studied the html language from june 2024 to august 2024.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="css.png" alt="">
                    <div class="vertical-title">
                        CSS (2024)
                    </div>
                    <div class="vertical-desc">
                        Along with the html language i have completes studied the css language from june 2024 to august 2024.
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="javascript.png" alt="">
                    <div class="vertical-title">
                        JAVASCRIPT(2024)
                    </div>
                    <div class="vertical-desc">
                        i've currently studying the javascript language.
                    </div>
                </div>
            </div>
            </div>
            </div>
            </div>

        </section>
    </main>
    <footer>
        <div class="footer-content">

              <h3>
                MY PORTFOLIO
              </h3> 
        

            <p>This is my Portfolio website</p>
            <ul class="social">
                <li><a href="#"><i class="fa-brands fa-instagram"></i></a></li>
                <li><a href="#"><i class="fa-brands fa-whatsapp"></i></a></li>
                <li><a href="#"><i class="fa-brands fa-linkedin"></i></a></li>
            </ul>
        </div>
        <div class="footer-bottom">
            <p>copyright &copy;<script>document.write(new Date().getFullYear())</script> MY PORTFOLIO</p>
        </div>
    </footer>
</body>

</html>



<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
<span id="element"></span>

<!-- Load library from the CDN -->
<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

<!-- Setup and start animation! -->
<script>
    var typed = new Typed('#element', {
        strings: ['Web Developer', 'Student'],
        typeSpeed: 50,
    });
</script>
</body>

</body>
<!-- Hi, Friends my name is Aadarsh and i am a student.
i am 19 year old. currently i am pursuing the engineering in electronics and telecommunication.
currently i am studying the another skills like web developement,data structure & algorithm etc.     -->

</html>
<!-- <a class="icon"><i class="fa-brands fa-whatsapp"></i><span class="space"></span>+91 9322994030</a><br>
<a class="icon"><i class="fa-brands fa-Email"></i>MASKEA291@GMAIL.COM</a>
<a class="icon"><i class="fa-brands fa-linkedin"></i>MASKE AADARSH</a> -->
