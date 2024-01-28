<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
    <title>RASHID</title>
  <style>
    *{
    padding: 0%;
    margin: 0%;
    box-sizing: border-box;
}
/* header{
    position: sticky;
    top: 0%;
    background:#fff;
} */
.header{
    display: flex;
    flex-wrap: wrap;
    gap: 90px;
    /* justify-content: center;  */
    border: 1px solid rgb(0, 0,0,0.2);
    padding: 30px 10px 10px 70px ;
    margin-top: 0px;
    /* position: relative; */
     /* position: sticky;  */
     /* width: 100vw;  */
     /* top: 0%;  */
    background-color: white;
    border-left: none;
    border-right: none;
}
/* .header{
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 100%;
    height: 75px;
    font-family: sans-serif;
    border-top: 1px solid rgb(0,0,0,0.2);
    border-bottom: 1px solid rgb(0,0,0,0.2);
    position: sticky;
    top: 0%;
    background-color: #fff;
} */
.header>nav>ul>li{
    display: inline-block;
    padding: 10px;
    margin-left: 20px;
    font-size:20px;
    font-family: sans-serif;
    font-weight: 500%;
    cursor: pointer;
}
.header>nav>ul>li:hover{
    color:  rgb(252, 22, 22);
    font-weight: 700;
}
/* @font-face {
    font-family: poppins;
    src: url(https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap);
    font-style: normal;
    font-weight: 400px;
    font-size: 20px;
} */
.header>nav>ul{
    margin-left: 70px;
    margin-top: 0px;
}
.header>span>button{
    position: absolute;
    right: 65px;
    top: 32px;
    padding: 5px 17px 9px 17px;
    background-color: rgb(252, 22, 22);
    color: white;
    border-radius: 20px;
    border: none;
    width: 110px;
    font-size: 18px;
    height: 30px;
    cursor: pointer;
}
.header>button{
    position: absolute;
    top: 37px;
    right: 215px;
    background-color: white;
    /* color: red; */
    border: none;
    font-size: 18px;
    cursor: pointer;
}
.header>button:hover{
    color: rgb(252, 22, 22);
    font-weight: 700;
}
.header>i{
    font-size: 27px;
    position: absolute;
    top: 37px;
    right: 330px;
    cursor: pointer;
}
.body-1{
    display: flex;
    justify-content: center;
    background-color: rgba(173, 216, 230, 0.144);
    /* gap: 50px; */
    width: 1250px;
    height: 600px;
    margin: 30px 30px 60px 50px ;
    border-radius: 20px;
    padding: 80px 20px;
    position: relative;
}
.body-1>.right>img{
    position: absolute;
    right: 50px;
    /* margin-left: 100px; */
    /* padding-left: 100px; */
}
/* .left{
    background-color: aquamarine;
    width: 900px;
} */
.body-1>.left>h1{
    font-size: 58px;
    font-family: algerian,courier;
    font-weight: 500;
    /* padding-left: 30px; */
    /* margin-left: 45px; */
    position: absolute;
    left: 70px;
    top: 60px;
}
.body-1>.left>h1>span{
    color: rgb(252, 22, 22);
}
.body-1>.left>p{
    font-size: 22px;
    position: absolute;
    left: 70px;
    top: 135px;
    /* margin-left: 45px; */
    /* padding-left: 30px; */
    /* padding-top: 13px; */
    /* padding-bottom: 18px; */
}
.body-1 .one{
    position: absolute;
    top: 185px;
    left: 73px;
    font-size: 25px;
    z-index: 1 ;
}
input[type=text]{
    width: 470px;
    position: absolute;
    left: 70px;
    top: 180px;
    height: 60px;
    border: 2px solid  rgb(252, 22, 22);
    padding-left: 50px;
    font-size: 20px;
    cursor: pointer;
    border-radius: 10px;
}
select{
    position: absolute;
    left: 70px;
    top: 260px;
    width: 470px;
    height: 60px;
    font-size: 20px;
    padding-left: 50px;
    border: 2px solid  rgb(252, 22, 22);
    cursor: pointer;
    border-radius: 10px;
}
.body-1 .two{
    position: absolute;
    top: 275px;
    left: 90px;
    font-size: 25px;
    z-index: 1 ;
}
.body-1 .three input[type=datetime-local]{
    position: absolute;
    top: 340px;
    left: 70px;
    width: 230px;
    height: 60px;
    font-size: 17px;
    padding-left: 45px;
    border: 2px solid  rgb(252, 22, 22);
    cursor: pointer;
    border-radius: 10px;
}
.body-1 .three>i{
    position: absolute;
    top: 360px;
    left: 80px;
    font-size: 25px;
    z-index: 1 ;
}
.body-1 .four input[type=datetime-local]{
    position: absolute;
    top: 340px;
    left: 310px;
    width: 230px;
    height: 60px;
    font-size: 17px;
    padding-left: 45px;
    border: 2px solid  rgb(252, 22, 22);
    cursor: pointer;
    border-radius: 10px;
}
.body-1 .four>i{
    position: absolute;
    top: 360px;
    left: 320px;
    font-size: 25px;
    z-index: 1 ;
}
.body-1>.left>label>button{
    background-color:   rgb(252, 22, 22);
    color: white;
    position: absolute;
    top: 430px;
    left: 70px;
    width: 300px;
    height: 60px;
    border-radius: 40px;
    border: none;
    font-size: 18px;
}
.body-2{
    margin-bottom: 150px;
}
.body-2>h1{
    font-family:  algerian,courier;
    text-align: center;
    font-size: 50px;
}
.body-2>h4{
    text-align: center;
    font-size: 30px;
    font-family: sans-serif;
    margin-top: 18px;
    font-weight: 400;
}
.body-2>.cards{
    display: flex;
    gap: 50px;
    justify-content: center;
    position: relative;
    top: 50px;
    cursor: pointer;
}
.body-2>.cards>.card-1,.card-2,.card-3{
    text-align: center;
    border: 1px solid gray;
    border-radius: 25px 25px 10px 10px ;
    padding-bottom: 20px;
}
.body-2 h3{
    font-size: 28px;
    font-family: system-ui;
    margin-top: 20px;
}
.body-2 button{
    margin-top: 40px;
    background-color:rgba(252, 22, 22, 0.815) ;
    border: none;
    padding: 15px;
    width: 150px;
    font-family: arial;
    color: rgba(255, 255, 255, 0.815);
    font-size: 15px;
    cursor: pointer;
    border-radius: 30px;
}
.body-2 button:hover{
    background-color: rgb(252, 22, 22);
    color: white;
}
.body-2 img{
    /* border: 1px solid royalblue; */
    border-radius: 25px 25px 1px 1px;
}
.body-3{
    background-color: rgba(253, 33, 33, 0.900);
    width: 1200px;
    position: relative;
    border-radius: 20px;
    left: 70px;
    max-height: 1000px;
    padding-bottom: 50px;
}
.body-3>h1{
    font-family: algerian,courier;
    text-align: center;
    padding-top: 65px;
    font-size: 40px;
    color: white;
    letter-spacing: 1px;
    padding-bottom: 30px;
}
.body-3>p{
    text-align: center;
    font-size: 25px;
    font-family: sans-serif;
    color: white;
}
.body-3>.cards{
    display: flex;
    gap: 50px;
    justify-content: center;
    cursor: pointer;
}
.body-3 .card-4,.card-5,.card-6{
    background-color: white;
    width: 350px;
    height: 380px;
    text-align: center;
    margin-left: -10px;
    border-radius: 20px;
    margin-top: 40px;
}
.body-3 .cards img{
    margin-top: 35px;
    margin-bottom: 10px;
}
.body-3 .cards h2{
    font-size: 30px;
    margin-bottom: 20px;
    font-family: arial;
}
.body-3 .cards p{
    margin-top: 5px;
    font-size: 20px;
}
.body-4>h1{
    font-family: algerian,courier;
    text-align: center;
    padding-top: 65px;
    font-size: 45px;
    letter-spacing: 1px;
    padding-bottom: 30px;
}
.body-4 .cards{
    display: flex;
    gap: 40px;
    justify-content: center;
    margin-top: 20px; 
    cursor: pointer;  
}
.body-4>.cards>.card{
    text-align: center;
    border: 1px solid gray;
    border-radius: 25px 25px 10px 10px ;
    padding-bottom: 20px;
}
.body-4 img{
    /* border: 1px solid royalblue; */
    border-radius: 25px 25px 1px 1px;
}
.body-4 button{
    margin-top: 40px;
    background-color:rgba(252, 22, 22, 0.815) ;
    border: none;
    padding: 15px;
    width: 150px;
    font-family: arial;
    color: rgba(255, 255, 255, 0.815);
    font-size: 15px;
    border-radius: 30px;
    cursor: pointer;
}
.body-4 button:hover{
    background-color: rgb(252, 22, 22);
    color: white;
}
.body-4 h2{
    font-size: 23px;
    font-family: system-ui;
    margin-top: 20px;
}
.body-4 p{
    font-family: arial;
    font-size: 17px;
    margin-top: 20px;
    font-weight: bold;
}
.body-4 span{
    font-family: arial;
    font-size: 17px;
    margin-top: 20px;
    font-weight: bold;
    color: gray;
}
.body-5 .comment{
    margin-top: 70px;
    margin-left: 50px;
    position: relative;
    border: 1px solid rgba(128, 128, 128, 0.726);
    width: 500px;
    height: 200px;
    padding: 30px;
    border-radius: 10px;
}
.body-5 h2{
    padding-left: 70px;
}
.body-5 span{
    padding-left: 70px;
}
.body-5 img{
    position: absolute;
    /* padding-bottom: 15px; */
}
.body-5>.para>span{
    padding-top: 15px;
    /* color: gray; */
}
.body-5 p{
    color: rgb(87, 86, 86);
    font-size: 17px;

}
.body-5 a{
    color:  rgb(252, 22, 22);
    text-decoration: none;
    font-size: 20px;
    padding-top: 10px;
    font-family: arial;
   position: absolute;
   top: 140px;
}
.body-6{
    margin-top: 70px;
    position: relative;
}
.body-6 h1{
    font-family: algerian,courier;
    text-align: center;
    padding-top: 65px;
    font-size: 45px;
    letter-spacing: 1px;
    padding-bottom: 30px;
}
.body-6>h2{
    position: absolute;
    left: 70px;
    font-size: 30px;
    font-family: sans-serif;
    top: 165px;
}
.body-6>a{
    color:  rgb(252, 22, 22);
    position: absolute;
    right: 70px;
    top: 165px;
    font-size: 25px;
    /* text-decoration: none; */
}
.body-6>.cards{
    display: flex;
    gap: 50px;
    justify-content: center;
    position: relative;
    top: 50px;
    cursor: pointer;
}
.body-6>.cards>.card{
    text-align: center;
    border: 1px solid gray;
    border-radius: 25px 25px 10px 10px ;
    padding-bottom: 20px;
}
.body-6 img{
    border-radius: 25px 25px 0px 0px ;
}
.body-6 h3{
    font-size: 28px;
    font-family: system-ui;
    margin-top: 20px;
    margin-bottom: 10px;
}
.body-6>.cards a{
    color:  rgb(252, 22, 22);
    text-decoration: none;
    font-size: 20px;
    font-family: arial;
    /* position: absolute; */
}
.body-7{
    background-image: url(img/hhh.avif);
    background-repeat: no-repeat;
    height: 700px;
    width: 1200px;
    background-size: 1200px;
    border-radius: 30px 30px 30px 30px;
    background-position: center;
    margin-left: 70px;
    margin-top: 120px;
    margin-bottom: 70px;
    object-fit: cover;
}
.body-7>h1{
    font-family: algerian,courier;
    text-align: center;
    padding-top: 150px;
    font-size: 50px;
    letter-spacing: 1px;
    padding-bottom: 30px;
    /* text-shadow: 2px 2px 2px lightgray;    */
}
.body-7 h5{
    font-size: 25px;
    font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    text-align: center;
}
.body-7 button{
    background-color:rgb(250, 60, 60) ;
    color: white;
    margin-left: 480px;
    margin-top: 100px;
    border: none;
    width: 250px;
    height: 70px;
    border-radius: 50px;
    font-size: 20px;
    font-weight: bold;
    cursor: pointer;
}
.body-8{
    background-color: lightcyan;
    width: 1200px;
    height: 230px;
    position: relative;
    left: 70px;
    margin-bottom: 50px;
    border-radius: 20px;
    text-align: center;      
    /* border-bottom: 3px solid rgb(250, 60, 60); */
}
.body-8>h2{
    font-family: algerian,courier;
    position: absolute;
    top: 38px;
    left: 500px;
    font-size: 33px;
}
.body-8>p{
    position: absolute;
    top: 90px;
    left: 400px;
    font-size: 22px;
    color: gray;
}
.body-8>input[type=email]{
    position: absolute;
    top: 150px;
    left: 400px;
    width: 300px;
    height: 50px;
    font-size: 15px;
    padding-left: 15px;
    border: 1px solid lightgray;
    border-radius: 10px 0px 0px 10px ;
}
.body-8>button{
    position: absolute;
    top: 150px;
    left: 680px;
    height: 50px;
    width: 130px;
    background-color:rgb(250, 60, 60) ;
    color: white;
    font-size: 18px;
    border: none;
    cursor: pointer;
    border-radius: 0px 10px 10px 0px;
}
.line{
    background-color: rgb(250, 60, 60);
    width: 100vw;
    height: 5px;
}
.foot>footer{
    display: flex;
    gap: 100px;
    justify-content: center;
    position: relative;
}
.foot h2{
    color: rgb(250, 60, 60);
    margin-top: 40px;
    font-family: Algerian,courier;
    margin-bottom: 50px;
    letter-spacing: 1px;
}
.foot>footer>.part-1>p{
    font-size: 18px;
    font-family: arial;
    color: gray;
}
.foot>footer>.part-2>ul>li{
    list-style-type: none;
    font-size: 18px;
    font-family: arial;
    color: gray;
}
.foot>footer>.part-3>ul>li{
    list-style-type: none;
    font-size: 18px;
    font-family: arial;
    color: gray;
    padding-top:5px ;
}
.foot>footer>.part-3>ul>li>i{
    font-size: 18px;
}
.foot>footer>.part-3>ul>li:nth-child(1){
    padding-top: 0px;
}
.foot>footer>.part-4>h2{
    margin-bottom: 15px;
}
.foot>footer>.part-4>h3{
    color: rgb(250, 60, 60);
    font-family: courier;
    font-size: 28px;
    margin-top: 10px;
    margin-bottom: 10px;
}
.foot>footer>.part-4>i{
    font-size: 30px;
    padding: 5px;
}
.buttom{
    background-color: darkgray;
    height: 2px;
    width: 1280px;
    margin-left: 40px;
    margin-top: 30px;
}
.boom{
    text-align: center;
    margin-top: 20px;
    font-weight: 700;
    margin-bottom: 40px;
}
  </style>
</head>
<body>
    <div class="main">
        <header>
        <div class="header">
            <img src="img/head.png" alt="" width="160px" height="50px">
            <nav>
                <ul>
                    <li>Home</li>
                    <li>Features</li>
                    <li>Blog</li>
                    <li>Become a partner</li>
                </ul>
            </nav>    
            <i class="fa-solid fa-bag-shopping" style="color: #e70404;"></i>
            <button>Login</button>
            <span><button>Register</button></span>
        </div><!--end header--></header>

        <div class="body-1">
            <div class="left">
                <h1>Parking <span>Simplified</span></h1>
                <p>Easily Find a Parking Space now!</p>

               <label for="form">
                <span class="one"><img src="img/download (3).png" alt="" height="50px" width="50px"></span>
                <input type="text" placeholder="Your Location" required="required"><br>
                <span class="two"><i class="fa-solid fa-car-rear" style="color: #e70404;"></i></span>
                <select name="cars" id="" required="required">
                    <option value="" selected>Select Vehicle Category</option>
                    <option value="">Car</option>
                    <option value="">Event</option>
                    <option value="">Valet</option>
                    <option value="">Semi Truck</option>
                </select><br>
                <span class="three"><i class="fa-solid fa-right-to-bracket" style="color: #e70404;"></i>
                <input type="datetime-local" placeholder="Check-In" required="required"></span>
                <span class="four"><i class="fa-solid fa-right-to-bracket fa-flip-both" style="color: #e70404;"></i>
                <input type="datetime-local" placeholder="Check-Out" required="required"></span><br>
                <button>Search Parking Spaces</button>
            </label> 
            </div>
            <div class="right">
                <img src="img/body 1.png" alt="" width="530px" height="430px">
            </div>
        </div><!--body-1 is end-->
        <div class="body-2">
            <h1>We are everywhere!</h1>
            <h4>Find a new home for your car.</h4>
            <div class="cards">
                <div class="card-1">
                    <img src="img/body 2.jpg" alt="" height="200px" width="370px">
                    <h3>City Parking</h3>
                    <button><b>Find a Parking</b></button>
                </div>
                <div class="card-2">
                    <img src="img/body 3.jpg" alt="" height="200px" width="370px">
                    <h3>Semi Truck Par...</h3>
                    <button><b>Find a Parking</b></button>
                </div>
                <div class="card-3">
                    <img src="img/body 4.jpg" alt="" height="200px" width="370px">
                    <h3>Airport Parking</h3>
                    <button><b>Find a Parking</b></button>
                </div>
            </div>
        </div><!--boy-2 is end-->
        <div class="body-3">
            <h1>Why Spot Finder?</h1>
            <p>We understand the pain for finding the right spot where your car feels home.</p>
            <p> Handicap friendly spots, diligent customer support, we aim to comfort you with</p>
            <p> nearest parking spot!</p>
            <div class="cards">
                <div class="card-4">
                    <img src="img/download.png" alt="" height="150px" width="150px">
                    <h2>It's fast</h2>
                    <p>Our new app makes finding spots in </p>
                    <p>not more than 3 steps. We're building</p>
                    <p> the largest network of parking spots!</p>
                </div>
                <div class="card-5">
                    <img src="img/download (1).png" alt="" height="150px" width="150px">
                    <h2>It's easy</h2>
                    <p>We aim to keep you hooked to our</p>
                    <p> services with an experience excellence</p>
                    <p>team!</p>
                </div>
                <div class="card-6">
                    <img src="img/download (2).png" alt="" height="150px" width="150px">
                    <h2>It's affordable</h2>
                    <p>Find affordable spots and spend your </p>
                    <p> days stress-free while your car is</p>
                    <p>parked with us.</p>
                </div>
            </div>
        </div><!--body-3 is end-->
        <div class="body-4">
            <h1>Airport Parking</h1>
            <div class="cards">
                <div class="card">
                    <img src="img/body 5.jpg" alt="" height="200px" width="280px">
                    <h2>Days Inn by Wynd...</h2>
                <span><p>Days Inn by Wyndham Hotel</p></span>
                    <button><b>Book Now</b></button>
                </div>
                <div class="card">
                    <img src="img/body 6.jpg" alt="" height="200px" width="280px">
                    <h2>Days Inn by Wynd...</h2>
                    <p>Da</p>
                    <button><b>Book Now</b></button>
                </div>
                <div class="card">
                    <img src="img/body 7.png" alt="" height="200px" width="280px">
                    <h2>Home2 Suites by H...</h2>
                    <p>Th</p>
                    <button><b>Book Now</b></button>
                </div>
                <div class="card">
                    <img src="img/body 8.jpg" alt="" height="200px" width="280px">
                    <h2>Holiday Inn Expres...</h2>
                    <span><p>Holdiay Inn Express & Suites </p></span>
                    <button><b>Book Now</b></button></div>
            </div>
        </div><!--body-4 is end-->
        <div class="body-5">
            <div class="comment">
                <img src="img/images.png" alt="" height="50px" width="50px">
                <h2>Anonymous</h2>
                <span><i class="fa-solid fa-star" style="color: #ffd43b;"></i>
                <i class="fa-solid fa-star" style="color: #ffd43b;"></i>
                <i class="fa-solid fa-star" style="color: #ffd43b;"></i>
                <i class="fa-solid fa-star" style="color: #ffd43b;"></i>
                <i class="fa-solid fa-star" style="color: #ffd43b;"></i></span>
                <div class="para">
                    <span><p>We love using Spotfinder.It was easy and simple for us.I am 80</p></span>
                    <p>years old and we liked how easy it was to do a booking.</p>
                    <a href="https://spotfinder.app/find-testimonial">Read More <i class="fa-solid fa-angle-right"></i><i class="fa-solid fa-angle-right"></i></a>
                </div>
            </div>    
        </div><!--body-5 is end-->
        <div class="body-6">
            <h1>Interesting Reads!</h1>
            <h2>New articles</h2>
            <a href="https://spotfinder.app/view-all-detail">Veiw All</a>
            <div class="cards">
                <div class="card">
                    <img src="img/body 9.jpg" alt="" height="200px" width="370px">
                    <h3>Why book your car parki...</h3>
                    <p>Online car parking can be a game-changer for</p>
                    <p> anyone planning a trip, whether it's for b</p><br>
                    <a href="https://spotfinder.app/find-blog">Read More <i class="fa-solid fa-angle-right"></i><i class="fa-solid fa-angle-right"></i></a>
                </div>
                <div class="card">
                    <img src="img/body 10.jpeg" alt="" height="200px" width="370px">
                    <h3>How parking Apps Outshi...</h3>
                    <a href=https://spotfinder.app/find-blog>Read More <i class="fa-solid fa-angle-right"></i><i class="fa-solid fa-angle-right"></i></a>
                </div>
                <div class="card">
                    <img src="img/body 11.PNG" alt="" height="200px" width="370px">
                    <h3>How parking Apps Outshi...</h3>
                    <a href=https://spotfinder.app/find-blog>Read More <i class="fa-solid fa-angle-right"></i><i class="fa-solid fa-angle-right"></i></a>
                </div>
            </div>
        </div><!--body-6 is end-->
        <div class="body-7">
            <h1>Partner With Spot Finder</h1>
                <h5>Grow your business by listing your service with us.</h5>
                <button>Become a Partner</button>
        </div><!--body-7 is end-->
        <div class="body-8">
            <h2>SUBSCRIBE</h2>
            <p>Subscribe to our Spot finder & stay Updated</p>
            <input type="email" placeholder="Enter Your Email" required="required">
            <button>Subscribe</button>
        </div><!--body-8 is end-->
        
        <div class="line"></div>

        <div class="foot">
            <footer>
                <div class="part-1">
                    <h2>About Us</h2>
                    <p>As Travelers and preplanners on a trip,</p>
                    <p> we hate not being able to find parking </p>
                    <p>on a reliable site. We decided to solve </p>
                    <p>this by starting in house!</p>
                </div>
                <div class="part-2">
                    <h2>Company</h2>
                    <ul>
                        <li>Privacy Policy</li>
                        <li>Cancellation Policy</li>
                        <li>Terms and Conditions</li>
                    </ul>
                </div>
                <div class="part-3">
                    <h2>Contact Info</h2>
                    <ul>
                        <li><i class="fa-regular fa-envelope" style="color: lightgray;"></i>&nbsp;&nbsp;Contact@SpotFinder.app</li>
                        <li><i class="fa-solid fa-phone"  style="color: lightgray;"></i>&nbsp;&nbsp;833-799-7770</li>
                        <li><i class="fa-solid fa-location-dot" style="color: lightgray;"></i>&nbsp;&nbsp;Fort Lauderale, Florida</li>
                        <li><i class="fa-solid fa-headphones" style="color: lightgray;"></i>&nbsp;&nbsp;Contact Support</li>
                    </ul>
                </div>
                <div class="part-4">
                    <h2>Payment Accepted</h2>
                    <img src="img/last.png" alt="" width="130px" height="30px"> 
                    <h3>Social</h3>
                    <i class="fa-brands fa-facebook" style="color: rgb(250, 60, 60);"></i>
                    <i class="fa-brands fa-twitter" style="color: rgb(250, 60, 60);"></i>
                    <i class="fa-brands fa-instagram" style="color: rgb(250, 60, 60);"></i>
                    <i class="fa-brands fa-tiktok" style="color: rgb(250, 60, 60);"></i>
                </div>
            </footer>
        </div>
        <div class="buttom"></div>
        <div class="boom">
            <p>All rights reserved © 2024 - SpotFinder by Travel Life LLC • Made with ❤️</p>
        </div>
    </div><!--main is end-->
</body>
</html>
