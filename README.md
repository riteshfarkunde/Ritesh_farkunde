<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>LEARN FAST</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        .allcard {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 5px 10px;
            margin: 15px;
        }

        hr {
            border: 2px solid rgb(11, 2, 2);
        }

        #p1 {
            font-size: 20px;
            color: black;
            text-align: center;
        }

        .marque {
            color: black;
            font-weight: bold;
        }

        #tcs {
            max-width: 700px;
            max-height: 500px;
        }

        @media (max-width: 768px) {
            #form1 {
                margin-left: 0;
                margin-top: 10px;
            }

            .navbar {
                flex-direction: column;
                align-items: center;
            }

            .navbar h1 {
                margin-bottom: 10px;
            }

            .allcard {
                justify-content: center;
            }

            .allcard .card {
                margin-bottom: 20px;
                width: 90%;
            }

            .para1 {
                margin-left: 0;
                margin-top: 10px;
                font-style: bold;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-size: 20px;
            }

            .carousel-inner img {
                width: 100%;
                height: auto;
            }

            #carouselExample {
                border: none;
            }
        }

        /* Footer styling */
        footer {
            background-color: #f8f9fa;
            padding: 20px 0;
        }

        footer .nav-link {
            padding: 0;
        }

        footer .form-control {
            width: 100%;
        }

        footer .btn-primary {
            width: 100%;
        }

        .para1 {
            margin-left: 876px;
            margin-top: -498px;
            font-style: bold;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 25px;
        }

        #carouselExample {
            margin: 10px 5px 0px 5px;
            /* Remove bottom margin */
        }

        #form1 {
            display: block;
            max-width: 748px;
            margin: 10px auto 0px;
            /* Reduce top margin */
            padding: 15px;
            border: 1px solid #ccc;
            border-radius: 15px;
        }
    </style>
</head>

<body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <h1><b>LEARN FAST</b></h1><a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="webcopy.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://topperworld.in/">Link</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Dropdown
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" aria-disabled="true">Disabled</a>
                    </li>
                </ul>
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>
    <hr>
    <marquee behavior="right">
        <h5><a href="#"> Welcome to Learn fast .................please kindly login to the web page ... and get notified
                about all updates</a></h5>
    </marquee>
    <hr>

    <div class="allcard">
        <div class="card" style="width: 18rem;">
            <img src="python.jfif" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Python</h5>
                <p class="card-text">Python is an interpreted, object-oriented, high-level programming language with
                    dynamic semantics developed by Guido van Rossum.</p>
                <a href="https://www.learnpython.org/" class="btn btn-primary">Get course</a>
            </div>
        </div>
        <div class="card" style="width: 18rem;">
            <img src="c++.jfif" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">C++</h5>
                <p class="card-text">C++ is a generic programming language for building software. It's an
                    object-oriented language.</p>
                <a href="https://topperworld.in/cpp-tutorial/" class="btn btn-primary">Get course</a>
            </div>
        </div>
        <div class="card" style="width: 18rem;">
            <img src="download.jfif" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">C</h5>
                <p class="card-text">C programming courses cover a variety of topics essential for mastering this
                    foundational programming language.</p>
                <a href="https://topperworld.in/c-tutorial/" class="btn btn-primary">Get course</a>
            </div>
        </div>
        <div class="card" style="width: 18rem;">
            <img src="js.jfif" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">JavaScript</h5>
                <p class="card-text">This JavaScript tutorial covers all important advanced JavaScript concepts such as
                    functional programming and object-oriented programming.</p>
                <a href="https://topperworld.in/javascript-handwritten-notes/" class="btn btn-primary">Get course</a>
            </div>
        </div>
    </div>

    <p id="p1">
        <span style="font-weight: bold; color: black; font-size: 22px ;">Get Started Today!</span><br>
    <h4>Take the first step towards transforming your future. Sign up for an online programming course and start
        learning from the comfort of your own home.</h4>
    </p>

    <div id="carouselExample" class="carousel slide">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="microsoft.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="tcs.jfif" class="d-block w-100" alt="..." id="tcs">
            </div>
            <div class="carousel-item">
                <img src="infosys.png" class="d-block w-100" alt="...">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <form id="form1">
        <div class="form-group">
            <h1>LOGIN</h1>
            <label for="exampleInputEmail1">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
        </div>
        <div class="form-group">
            <label for="exampleInputPassword1">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
        </div>
        <div class="form-group form-check">
            <input type="checkbox" class="form-check-input" id="exampleCheck1">
            <label class="form-check-label" for="exampleCheck1">Check me out</label>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
    </form>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous">

        </script>
</body>

<br><br><br>
<hr style="border: 3px solid rgb(14, 1, 1);">

<div class="container">
    <footer class="py-5">
        <div class="row">
            <div class="col-6 col-md-2 mb-3">
                <h5>Section</h5>
                <ul class="nav flex-column">
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
                </ul>
            </div>
            <div class="col-6 col-md-2 mb-3">
                <h5>Section</h5>
                <ul class="nav flex-column">
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
                    <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
                </ul>
            </div>
            <div class="col-md-5 offset-md-1 mb-3">
                <form>
                    <h5>Subscribe to our newsletter</h5>
                    <p>Monthly digest of what's new and exciting from us.</p>
                    <div class="d-flex flex-column flex-sm-row w-100 gap-2">
                        <label for="newsletter1" class="visually-hidden">Email address</label>
                        <input id="newsletter1" type="text" class="form-control" placeholder="Email address">
                        <button class="btn btn-primary" type="button">Subscribe</button>
                    </div>
                </form>
            </div>
        </div>
        <div class="d-flex flex-column flex-sm-row justify-content-between py-4 my-4 border-top">
            <p>&copy; 2024 Company, Inc. All rights reserved.</p>
            <ul class="list-unstyled d-flex">
                <li class="ms-3"><a class="link-body-emphasis" href="www.twitter.com">Twitter</a></li>
                <li class="ms-3"><a class="link-body-emphasis" href="WWW.instagram.com">Instagram</a></li>
                <li class="ms-3"><a class="link-body-emphasis" href="www.facebook.com">Facebook</a></li>

            </ul>
        </div>
    </footer>
</div>

</html>
