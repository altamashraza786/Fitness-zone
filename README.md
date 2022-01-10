<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">


    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>The Gym/Fitness</title>
    <style>
        body {
            background-color: rgb(206, 179, 179);
        }

        .photo {
            overflow: hidden;
            border: 2px solid red;
            height: 700px;

        }

        .photo figure {
            position: relative;
            margin: 0%;
            width: 500%;
            height: 700px;
            left: 0%;
            animation: 10s photo infinite;
        }

        .photo figure img {
            width: 20%;
            float: left;
        }

        @keyframes photo {
            0% {
                left: 0%;
            }

            20% {
                left: 0%;
            }

            25% {
                left: -100%;
            }

            45% {
                left: -100%;
            }

            50% {
                left: -200%;
            }

            70% {
                left: -200%;
            }

            75% {
                left: -300%;
            }

            95% {
                left: -300%;
            }
        }

        .frist {
            max-width: 2000px;
            max-height: auto;
            background-color: black;
            padding-top: 2px;
            padding-left: 300px;
        }

        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;

        }

        li {
            font-size: 25px;
            float: left;
            color: white;
        }

        li a {
            display: block;
            padding: 8px;
            color: white;
        }

        li :hover {
            background-color: rgb(15, 0, 83);
        }

        }

        .conter {
            max-width: 1800px;
            background-color: rgb(211, 179, 0);
            margin: auto;
            overflow: auto;
        }

        .gallary {
            margin: 5px;
            border: 1px solid black;
            float: left;
            width: 350px;
        }

        .gallary img {
            width: 100%;
            height: 300px;
        }

        .discp {
            padding: 15px;
            text-align: center;
        }

        .txt {
            text-align: center;
        }

        ps {
            text-align: center;
            font-size: 20px;
        }

        .conter {
            margin: 0%;
            overflow: auto;
            float: left;
        }

        .discp {
            font-size: 200%;
            text-align: center;
        }

        .page {
            max-width: 1900px;
            background-color: rgb(10, 10, 10);



        }

        .texts {
            max-width: 900px;
            text-justify: auto;


        }

        .discption {
            color: white;
            font-size: 40px;
            text-justify: auto;
        }

        .ps {
            text-align: center;
            font-size: 25px;
        }

        .bank {
            text-align: center;
        }

        .video {
            padding-left: 0;
        }
    </style>
</head>
<link rel="stylesheet" href="gym.css">

<body>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>

    <nav class="navbar navbar-expand-lg navbar-danger bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">GYM</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="membership.html">Membership</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link" href="contact.html">contact</a>
                        </a>

                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-success" type="submit">Search</button>
                </form>
                <div class="mx-2">
                    <a href="login.html"><button class="btn btn-danger">Login</button></a>
                    <button class="btn btn-danger" data-bs-toggle="modal" data-bs-target="#signupModal">Sign up</button>
                </div>

                </form>
            </div>
        </div>
    </nav>
    <div class="photo">
        <figure>
             <img src="https://themewagon.com/wp-content/uploads/2020/10/gym-1.jpg" alt="">
             <img src="https://miro.medium.com/max/1400/1*kymQR1cbK7cGIdFNb_aMdQ.jpeg" alt="">
             <img src="https://s3-alpha.figma.com/hub/file/941840809/232bf1c0-4f7c-491d-886b-a9a3dc27a3e1-cover.png" alt="">
             <img src="https://themewagon.com/wp-content/uploads/2020/09/Zacson-1.png" alt="">
        </figure>

    </div>

    <div id="colour"></div>
    <h1 style="color: chocolate;" class="txt"> WELCOME TO THE GYM!</h1>
    <P class="ps">Take care of your body. Its the only place you have a to live</P>
    <div class="conter" style="background-color: wheat;">
        <div class="gallary">
            <div class="discp">KICK BOXING</div>
            <img src="https://i.ytimg.com/vi/4fao_RUnPXk/maxresdefault.jpg" alt="">
        </div>
        <div class="gallary">
            <div class="discp">workout</div>
            <img src="https://www.planetfitness.com/sites/default/files/feature-image/xbreak-workout_602724.jpg.pagespeed.ic.v8byD7su-e.jpg" alt="">
        </div>
        <div class="gallary">

            <div class="discp">fitness</div>
            <img src="https://www.healthkart.com/connect/wp-content/uploads/2016/10/Banner-24.jpg" alt="">
        </div>
        <div class="gallary">
            <div class="discp">workout</div>
            <img src="https://i0.wp.com/images-prod.healthline.com/hlcmsresource/images/topic_centers/man-deadlift-1296x728-header.jpg?w=1155&h=1528" alt="">
        </div>
        <div class="gallary">
            <div class="discp">yoga</div>
            <img src="https://assets.vogue.in/photos/601291e222284e1c9b494ad7/1:1/w_3574,h_3574,c_limit/5%20female%20fitness%20myths,%20debunked%20by%20the%20pros.jpg" alt="">
        </div>
        <div class="gallary">
            <div class="discp">fitness</div>
            <img src="https://img.freepik.com/free-photo/young-fitness-man-studio_7502-5008.jpg?size=626&ext=jpg" alt="">
        </div>
        <div class="gallary">
            <div class="discp">
                gym
            </div>
            <img src="https://www.lifefitness.com/resource/image/162952/portrait_ratio1x1/600/600/d7dfae1242ae38425be3d8cbc420dd89/Yt/axiom-series.jpg" alt="">
        </div>
        <div class="gallary">

            <div class="discp">work</div>
            <img src="https://www.panattasport.com/resources/home/homefitness-home.jpg" alt="">
        </div>
    </div><br><br><br><br><br><br>
    <br><br>
    <h1 style="text-align: center; padding-top: 650px;">No Judgments are the Best Kind</h1>
    <p style="text-align: center; font-size: 25px;">Differences are encouraged. Quirks are welcomed.</p>

    <div class="container marketing" my="20px">

        <div class="row" my="20px">
            <div class="col-lg-4">
                <img src="https://dj7w0h47bhjwk.cloudfront.net/assets/illustration--positivity-light-400-93e6eaa31ffe5bf8c0f80e0a7f15f90c64f6a82737a11e6b2a510500e137c016.png"
                    alt="">
                <h2>Positivity</h2>
                <p> We are nurturers: we seek only to encourage, entertain, and empower.</p>
                <p><a class="btn btn-secondary" href="#">View details »</a></p>
            </div>
            <div class="col-lg-4">
                <img src="https://dj7w0h47bhjwk.cloudfront.net/assets/illustration--inclusivity-light-400-09aff2bed351817c782bd57695ad13ffd31e2b5f6a311c4169e92c087bd1aa95.png"
                    alt="">
                <h2> INCLUSIVITY</h2>
                <p> Here we keep open minds. There is no one type or way in our diverse community. Come as you are!</p>
                <p><a class="btn btn-secondary" href="#">View details »</a></p>
            </div>
            <div class="col-lg-4">
                <img src="https://dj7w0h47bhjwk.cloudfront.net/assets/illustration--fun-light-400-1ab8ad2a8f2e1c05f1b5191853e02fb11e9e7f9eab61cc560b2a9eec0cf8a9ef.png"
                    alt="">
                <h2>Fun</h2>
                <p> We know serious fitness is hard, but that doesn’t mean it can’t be an edge-of-your-seat,
                    can’t-get-enough, look-forward-to-your-workouts party.</p>
                <p><a class="btn btn-secondary" href="#">View details »</a></p>
            </div>
        </div> <br><br>
        <h1 class="bank" style="font-size: 50px;">Goals are Made to be Crushed</h1>
        <p class="bank" style="font-size: 20px;">Train with our experts to drive your results.</p>
        <p class="bank" style="font-size: 15px; color: brown;">LEARN MORE ABOUT OUR INDIVIDUAL AND SMALL GROUP TRAINING
            PROGRAMS</p>
        <iframe width="100%" height="500px" style="padding-left: 80px;" src="https://www.youtube.com/embed/KFSsMS2mZkM"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>

        <br><br>
        <footer class="pt-4 my-md-5 pt-md-5 border-top">
            <div class="row">

                <div class="col-6 col-md">
                    <h5>Features</h5>
                    <ul class="list-unstyled text-small">
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Cool stuff</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Random feature</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Team feature</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Stuff for
                                developers</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Another one</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Last time</a></li>
                    </ul>
                </div>
                <div class="col-6 col-md">
                    <h5>Resources</h5>
                    <ul class="list-unstyled text-small">
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Resource</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Resource name</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Another resource</a>
                        </li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Final resource</a></li>
                    </ul>
                </div>
                <div class="col-6 col-md">
                    <h5>About</h5>
                    <ul class="list-unstyled text-small">
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Team</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Locations</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Privacy</a></li>
                        <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Terms</a></li>
                    </ul>
                </div>
            </div>
        </footer>






</body>

</html>
