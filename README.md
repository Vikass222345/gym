<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Gold Gym</title>
    <link  rel="icon" type="image/x-icon" href="icons8-gym-50.png" style="width: auto;">
</head>
<link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    /* CSS Reset */
    *{
        box-sizing: border-box;
        user-select: none;
    }
    body {
        font-family: 'Baloo Bhai', cursive;
        color: rgb(197, 196, 196);
        margin: 0px;
        padding: 0px;
        background: url('danielle-cerullo-CQfNt66ttZM-unsplash.jpg');
    }

    .left {
        display: inline-block;
        position: absolute;
        left: 60px;
        top: 20px;
    }

    .left img {
        width: 136px;
        filter: invert(100%);
    }

    .left div {
        line-height: 19px;
        font-size: 26px;
        text-align: center;
    }

    .mid {
        display: block;
        width: 40%;
        margin: 29px auto;
    }

    .right {
        position: absolute;
        right: 34px;
        top: 43px;
        display: inline-block;

    }

  
    .navbar li {
     display: inline-block;
     /* display: flex; */
        font-size: 25px;
    }
    
    .navbar li a {
        color: white;
        text-decoration: none;
        /* border: 2px solid white; */
        /* padding: 34px 23px; */
        margin: 20px;

    }

    .navbar li a:hover {
        text-decoration: none;
        color: grey;

    }

    .btn {
        font-family: 'Baloo Bhai', cursive;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px solid grey;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(31, 30, 30);
    }

    .container {
        border: 2px solid white;
        margin: 106px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }

    .form-group input {
        font-family: 'Baloo Bhai', cursive;
        text-align: center;
        display: block;
        width: 508px;
        padding: 1px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 74%;
        margin: 20px auto;
    }
</style>

<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <img src="icons8-gym-50.png" alt="abc" style="width: auto;">
            <div>Gold Gym</div>
        </div>
        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>

        <!-- Right box for buttons -->
        <div class="right">
            <button class="btn">Call Us Now</button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h1>Join the best gym of mohali now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="number" placeholder="Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your Locality">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your Email Id">
            </div>
            <div class="form-group">
                <input type="number" name="" placeholder="Enter your Phone Number">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>

</html>
