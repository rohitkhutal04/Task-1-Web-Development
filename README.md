# Task-1-Web-Development
Oasis Infobyte
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="fontawesome/css/all.min.css">
    <style>
        * {
            margin: 0px;
            padding: 0px;
        }
        
        .container {
            width: 86%;
            margin-left: 100px;
        }
        
        .header {
            background-color: grey;
            height: 100px;
        }
        
        .header .nav-heading {
            margin-left: 10px;
            float: left;
            font-size: 60px;
            text-decoration: none;
            color: rgb(36, 2, 2);
        }
        
        .header .nav-heading:hover {
            color: #fff;
        }
        
        .header .menu {
            float: right;
        }
        
        .header .menu ul {
            list-style: none;
        }
        
        .header .menu ul li {
            display: inline-block;
            padding: 10px 25px;
            margin-top: 15px;
            font-size: 25px;
        }
        
        .header .menu ul li .nav-item {
            text-decoration: none;
            color: rgb(36, 31, 31);
        }
        
        .header .menu ul li .nav-item:hover {
            color: #fff;
        }
        
        .banner {
            height: 400px;
            margin-bottom: 40px;
        }
        
        .banner .img-res {
            width: 100%;
            height: 400px;
            object-fit: cover;
        }
        
        .services .header-service {
            text-align: center;
            font-size: 35px;
            color: rgb(54, 52, 52);
        }
        
        .services .columns {
            float: left;
            width: 400px;
            text-align: center;
            margin-top: 20px;
            border-right: 2px solid;
            margin-bottom: 40px;
        }
        
        .services .columns:last-child {
            border-right: 0px;
        }
        
        .columns .columns-title {
            margin: 5px;
            font-size: 22px;
            color: rgb(61, 60, 60);
        }
        
        .columns .columns-text {
            font-size: 17px;
            margin: 5px;
            margin-bottom: 20px;
        }
        
        .columns .columns-link {
            background-color: blue;
            color: #fff;
            padding: 10px;
            font-size: 20px;
            border-radius: 10px;
            text-decoration: none;
        }
        
        .card-deck {}
        
        .card-deck .card-header {
            text-align: center;
            font-size: 35px;
            color: rgb(54, 52, 52);
            margin-bottom: 20px;
        }
        
        .card-deck .card {
            float: left;
            width: 400px;
            background-color: rgb(209, 201, 201);
            text-align: center;
            margin-right: 20px;
            border-radius: 20px;
            height: 350px;
        }
        
        .card .card-title {
            margin: 10px;
            font-size: 25px;
            color: rgb(32, 7, 7);
            margin-bottom: 10px;
        }
        
        .card .image-res {
            border-radius: 100%;
            margin-bottom: 10px;
        }
        
        .card .card-text {
            color: rgb(78, 78, 78);
            font-size: 17px;
            margin-bottom: 10px;
        }
        
        .card .card-price {
            color: rgb(31, 4, 4);
            font-size: 23px;
            margin-bottom: 20px;
        }
        
        .card .btn {
            background-color: rgb(77, 71, 71);
            padding: 10px;
            font-size: 22px;
            color: #fff;
            text-decoration: none;
            border-radius: 10px;
            border: 2px solid white;
        }
        
        small {
            font-size: 14px;
        }
        
        span {
            color: red;
        }
        
        @media screen and (max-width:600px) {
            .header {
                height: 300px;
            }
            .header .nav-heading {
                display: none;
            }
            .header .menu ul li {
                display: block;
            }
            .card {
                margin-bottom: 10px;
            }
        }
    </style>
</head>

<body>
    <div class="container">

        <!-- Navigation -->
        <div class="header">
            <a href="" class="nav-heading">eLearning</a>
            <div class="menu">
                <ul>
                    <li><a href="Home.html" class="nav-item">Home</a></li>
                    <li><a href="#service" class="nav-item">Services</a></li>
                    <li><a href="#course" class="nav-item">Courses</a></li>
                    <li><a href="" class="nav-item">Contact Us</a></li>
                </ul>
            </div>
        </div>
        <!-- Banner Image-->
        <div class="banner">
            <img src="images/e1.jpg" alt="" class="img-res">
        </div>

        <!-- Services Cards-->

        <div class="services" id="service">
            <h1 class="header-service">Services</h1>
            <div class="columns">
                <i class="fas fa-ad"></i>
                <h2 class="columns-title">Web Designing</h2>
                <p class="columns-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cupiditate, quae!</p>
                <a href="#" class="columns-link">Know More</a>
            </div>
            <div class="columns">
                <i class="far fa-file-code"></i>
                <h2 class="columns-title">Web Developement</h2>
                <p class="columns-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cupiditate, quae!</p>
                <a href="#" class="columns-link">Know More</a>
            </div>
            <div class="columns">
                <i class="fas fa-robot"></i>
                <h2 class="columns-title">Web Android</h2>
                <p class="columns-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cupiditate, quae!</p>
                <a href="#" class="columns-link">Know More</a>
            </div>
        </div>

        <!-- Courses Cards-->

        <div class="card-deck" id="course">
            <h1 class="card-header">Courses</h1>
            <div class="card">
                <h2 class="card-title">Learn Python</h2>
                <img src="images/Python.jpg" alt="" class="image-res">
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, repellat.</p>
                <h3 class="card-price">Price : <small><del> 8000 </del> </small> &nbsp;&nbsp; <span>9000</span></h3>
                <a href="" class="btn">Buy Now</a>
            </div>
            <div class="card">
                <h2 class="card-title">Learn PHP</h2>
                <img src="images/php.jpg" alt="" class="image-res">
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, repellat.</p>
                <h3 class="card-price">Price : <small><del> 8000 </del> </small> &nbsp;&nbsp; <span>9000</span></h3>
                <a href="" class="btn">Buy Now</a>
            </div>
            <div class="card">
                <h2 class="card-title">Learn Angular</h2>
                <img src="images/angular.jpg" alt="" class="image-res">
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, repellat.</p>
                <h3 class="card-price">Price : <small><del> 8000 </del> </small> &nbsp;&nbsp; <span>9000</span> </h3>
                <a href="" class="btn">Buy Now</a>
            </div>
        </div>

    </div>
</body>

</html>
