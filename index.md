<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cotton Design and Development</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</head>

<body>
    <div id="particles">
        <div class="container">
            <header class="main-header">
                <nav class="main-nav">
                    <a class="header-image" href="index.html"><img src="images/logo.png"
                            alt="Cotton Design and Development logo"></a>
                    <ul class="navbar-items">
                        <li><a href="index.html" class="navbar-items-item">Home</a></li>
                        <li><a href="#pricing" class="navbar-items-item">Pricing</a></li>
                        <li><a href="#contact" class="navbar-items-item">Contact</a></li>
                    </ul>
                </nav>
                <a href="https://discordapp.com/invite/85ZFBNj" class="click-button">
                    <img class="header-image" src="images/discord-white.png" alt="discord logo">CLICK HERE
                </a>
            </header>
            <section class="home-main-section">
                <div class="left-part">
                    <h1 class="title">Cotton Design & <br />Development Studio</h1>
                    <div class="learn-more">
                        <div class="graphic-design">
                            <img src="images/eye-icon.png" alt="">
                            <span>Graphic Design</span>
                            <!-- <span class="material-icons">
                                expand_more
                            </span> -->
                        </div>
                        <div class="front-end-development">
                            <div class="small-size"> <img src="images/laptop.png" alt="">
                                <span>Front-End Development</span></div>
                            <a href="#pricing" class="learn-more-btn">Learn More</a>
                        </div>

                    </div>
                    <p class="subtitle">A SERVICE BY <span>COTTON DEVELOPMENT TEAM</span></p>
                </div>

                <img src="images/office-background.jpg" class="office-image" alt="photo">

            </section>
        </div>
    </div>
    <section class="product-listing">
        <div class="container">
            <h2 id = "pricing">Find a product</h2>
            <div class="product-listing-items">
                <div class="products">
                    <div class="product-tag"><img src="images/paint-brush.png" alt="tag photo"> design</div>
                    Website Design, Logo Design, UI/UX Design, etc.
                    <hr>
                    <div class="listing-bottom">
                        <p>STARTING AT <span> $25</span></p>
                        <div>
                            <img src="images/shopcat.png" alt="shopcat-photo" data-shoppy-product="VBAczpQ">
                        </div>
                    </div>
                </div>
                <div class="products">
                    <div class="product-tag"><img src="images/laptop2.png" alt="tag photo">development</div>
                    Front-end website development
                    <hr>
                    <div class="listing-bottom">
                        <p>STARTING AT <span> $25</span></p>
                        <div>
                            <img src="images/shopcat.png" alt="shopcat-photo" data-shoppy-product="VBAczpQ">
                        </div>
                    </div>
                </div>
                <div class="products">
                    <div class="product-tag"><img src="images/logo.png" alt="tag photo">design + development</div>
                    Website Design and front-end development
                    <hr>
                    <div class="listing-bottom">
                        <p>STARTING AT <span> $50</span></p>
                        <div>
                            <img src="images/shopcat.png" alt="shopcat-photo" data-shoppy-product="VBAczpQ">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <section class="end-page">
            <div class="call-to-action container">
                <div>
                    <h3 id="contact">Our goal is simple.</h3>
                    <p>To persuade potential customers in buying <br> from you through your website </p>

                    <div class="buttons">
                        <a href="https://discord.gg/85ZFBNj"><img src="images/discord-new-logo.png" alt="discord logo"
                                class="end-page-image">https://discord.gg/85ZFBNj</a>
                        <a href="https://discord.gg/85ZFBNj">Click here to join the server</a>
                    </div>
                </div>

            </div>
        </section>
    </section>

    <script src="https://shoppy.gg/api/embed.js"></script>
    <script src="three.r95.min.js"></script>
    <script src="vanta.dots.min.js"></script>
    <script>
        VANTA.DOTS({
            el: "#particles",
            mouseControls: true,
            touchControls: true,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0xffa200,
            color2: 0xcf7221,
            backgroundColor: 0x282c34,
            size: 4.70,
            spacing: 66.00,
            showLines: false
        })
    </script>
</body>


</html>
