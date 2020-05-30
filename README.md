# codeleaf.github.io
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Website creator</title>
 <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap" rel="stylesheet">
<style>
body{
margin: 0;
padding: 0;
font-family: 'Josefin Sans', sans-serif;
}
.leaf{
font-family: 'Pacifico', cursive;
}
img{
width: 100%;
height: 100%;
}
.anim2{
text-align: center;
margin-top: 20px;
border-radius: 0% 100% 0% 100% / 50% 50% 50% 50% ;
}

.img1{
animation: bounce 2s linear infinite;
}
.anim2 img{
animation: bounce 2s linear infinite;
}
@keyframes bounce{
0%{transform: translateY(-15px); }
50%{transform: translateY(0px); }
100%{transform: translateY(-15px); }
}
.leaf1{
transform: scaleX(-1);
}
.card1{
transition: .5s;
}
.card{
overflow:hidden;
}
.card1:hover{
transform: scale(1.05);
}
.card1 img{
animation: cardanim 3s linear infinite;
}

.card2{
transition: .5s;
}
.card2:hover{
transform: scale(1.05);
}
.card2 img{
animation: cardanim 3s linear infinite;
animation-delay: .5s;
}

.card3{
transition: .5s;
}
.card3:hover{
transform: scale(1.05);
}
.card3 img{
animation: cardanim 3s linear infinite;
}
@keyframes cardanim{
0%{
transform: scale(1);
}
50%{
transform: scale(1.05);
}
}
.covid{
height: auto;
width: 100%;
}
.covid span{
font-family: 'pacifico';
}
.newid{
background: url("https://images.pexels.com/photos/212265/pexels-photo-212265.jpeg?auto=compress&cs=tinysrgb&h=650&w=940.jpg");
}
.newid h2{
width: 85px;
border: 2px solid #fff;
border-radius: 4px;
padding: 4px 7px;
}
.newid div{
padding: 20px;
background-color: rgba(46, 49, 49, .5);
opacity: 1;
}
.newid button{
}
#magic{
display: none;
}
</style>
<script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>

<body>
<header>

<div class="bs-example">
    <nav class="navbar navbar-expand-md navbar-light bg-light">
        <a href="#" class="navbar-brand">Code<span class="text-success leaf">Leaf</span></a>
        <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarCollapse">
            <div class="navbar-nav">
                <a href="#" class="nav-item nav-link active">Home</a>
                <a href="#" class="nav-item nav-link">Services</a>
                <a href="#" class="nav-item nav-link">About us</a>
                <a href="#" class="nav-item nav-link disabled" tabindex="-1">Contact us</a>
            </div>
            <div class="navbar-nav ml-auto">
                <a href="#" class="nav-item nav-link">Login</a>
            </div>
        </div>
    </nav>
</div>


<div id="demo" class="carousel slide" data-ride="carousel">
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
  </ul>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://images.pexels.com/photos/583846/pexels-photo-583846.jpeg?auto=compress&cs=tinysrgb&h=650&w=940.jpg" alt="Los Angeles" width="1100" height="500">
      <div class="carousel-caption">
        <h3>Welcome</h3>
        <p>Hi welcome to my website</p>
      </div>   
    </div>
    <div class="carousel-item">
      <img src="https://images.pexels.com/photos/373966/pexels-photo-373966.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500.jpg" alt="Chicago" width="1100" height="500">
      <div class="carousel-caption">
        <h3>Order to create website</h3>
        <p>Contact me if you need a website</p>
      </div>   
    </div>
    <div class="carousel-item">
      <img src="https://images.pexels.com/photos/326519/pexels-photo-326519.jpeg?auto=compress&cs=tinysrgb&h=650&w=940.jpg" alt="New York" width="1100" height="500">
      <div class="carousel-caption">
        <h3> Reasonable price </h3>
        <p>I create website for a cheap price!</p>
      </div>   
    </div>
  </div>
  <a class="carousel-control-prev" href="#demo" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#demo" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div>
</header>

<h1 class="text-center mt-4 text-capitalize">Code<span class="text-success leaf">Leaf</span></h1>
<hr class="w-75">

<section>
  <div class="container-fluid ">
<div class="row">
      <img class="col-sm-6 img1" src="https://cdn.dribbble.com/users/2424687/screenshots/6065697/cat-01.png" alt=""/>
<div class="col-sm-6">
  <h2 class="text-center">Who am I?</h2>
<hr class="w-50"/>
  <p class="text-justify m-4">
 My name is Riju Sharma. I'm from Kolkata, India. I'm pursuing a Bachelor's degree in EE. My passion is to create smooth and affordable websites for my clients for their business and personal purpose. If you are looking for a website creator then you can hire me.
</p>
<button type="button" class="btn btn-primary ml-4">Hire me</button>
</div>
</div>
  </div>
</section>

<div class="container-fluid row">
<div class="col-sm-6 mt-4 text-center stay">
<h3 class="covid mb-4">Stay <span class="text-success" >Safe</span>, Stay <span class="text-success" >Home</span></h3>
<h4 class="">Protect yourself and others</h4>
<p class="">To protect yourself and others against COVID-19, clean your hands frequently and thoroughly. Use alcohol-based hand sanitizer or wash your hands with soap and water. 
</p>
<p>Maintain at least 1 metre (3 feet) distance between yourself and others.</p>
<p>Avoid going to crowded places.</p>
<p>Make sure you, and the people around you, follow good respiratory hygiene.</p>
</div>
<div class="col-sm-6 mt-3">
<img class="img-fluid rounded" src="https://cdn.dribbble.com/users/5024684/screenshots/10813428/stay-save-stay-home.gif"/>
</div>
</div>

<div class="text-center mt-5">
<h3 class="fas fa-wrench text-success"></h3>

<h2 class="mb-4" >Products</h2>
</div>
<!--card-->

<section>
<div class="container-fluid">
<div class="row ml-2">
<div class="col-sm-3 mr-4 mb-3 card1">
<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="https://images.pexels.com/photos/1029757/pexels-photo-1029757.jpeg?auto=compress&cs=tinysrgb&h=650&w=940.jpg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Scratch Website</h5>
    <p class="card-text">Simple and classic look can catch more audience to your website</p>
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item"><i class="fas fa-check-circle mr-2 text-success"></i>Responsive design</li>
    <li class="list-group-item"><i class="fas fa-check-circle mr-2 text-success"></i>Maximum 5 pages</li>
    <li class="list-group-item"><i class="fas fa-times-circle mr-2 text-danger"></i>
Domain</li>
  </ul>
  <div class="card-body">
    <a href="#" class="card-link">View deal</a>
    <a href="#" class="card-link">Contact</a>
  </div>
</div>
</div>

<div class="col-sm-3 mr-4 ml-5 card2">
<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="https://images.pexels.com/photos/109371/pexels-photo-109371.jpeg?auto=compress&cs=tinysrgb&h=650&w=940.jpg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Wordpress Website</h5>
    <p class="card-text">With cool and modern theme you can get a exellent website for your uses. Best option <b>Now</b></p>
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item"><i class="fas fa-check-circle mr-2 text-success"></i>Responsive design</li>
    <li class="list-group-item"><i class="fas fa-check-circle mr-2 text-success"></i>Maximum 5 pages</li>
    <li class="list-group-item"><i class="fas fa-times-circle mr-2 text-danger"></i>
Domain</li>
  </ul>
  <div class="card-body">
    <a href="#" class="card-link">View deal</a>
    <a href="#" class="card-link">Contact</a>
  </div>
</div>
</div>



<div class="col-sm-3 mr-4 ml-5 card3">
<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="https://images.pexels.com/photos/461073/pexels-photo-461073.jpeg?auto=compress&cs=tinysrgb&h=650&w=940.jpg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Advanced website</h5>
    <p class="card-text">A website for your online marketing makes you profitable</p>
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item"><i class="fas fa-check-circle mr-2 text-success"></i>
Responsive design</li>
    <li class="list-group-item"><i class="fas fa-check-circle mr-2 text-success"></i>
Infinite pages</li>
    <li class="list-group-item"><i class="fas fa-check-circle mr-2 text-success"></i>
Domain</li>
  </ul>
  <div class="card-body">
    <a href="#" class="card-link text-danger">Currently not available</a>
  <!--  <a href="#" class="card-link">Contact</a>-->
  </div>
</div>
</div>
</div>
</div>

</section>

<!-- product end-->
<div class="container-fluid mt-5 text-light newid">
<div class="">
<h2 class="">New</h2>
<h4>I have a special offer for you!! Now the starting price of a webpage is <b>only $4</b>. Discuss your what you want and give a order.
Re-attempt available.
<b>Hurry up</b></h4>
<button type="button" class="btn btn-secondary btn-lg btn-block">Know More</button></div>
</div>

<div class="text-center mt-5">
<h3 class="fas fa-trophy text-success pt-2"></h3>
<h2 class=" text-dark">Certified on</h2>
</div>

<hr class="w-75">

<div class="accordion container-fluid row mt-5" id="myAccordion">
  <div class="col-sm-6">
    <div class="card">
        <div class="card-header" id="headingOne">
            <h2 class="mb-0">
                <button type="button" class="btn btn-link text-success " data-toggle="collapse" data-target="#collapseOne">1. What is HTML?</button>
            </h2>
        </div>
        <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#myAccordion">
            <div class="card-body">
                <p>HTML stands for HyperText Markup Language. HTML is the standard markup language for describing the structure of web pages. <a href="https://www.tutorialrepublic.com/html-tutorial/" target="_blank">Learn more.</a></p>
            </div>
        </div>
    </div>
    <div class="card">
        <div class="card-header" id="headingTwo">
            <h2 class="mb-0">
                <button type="button" class="btn btn-link collapsed text-success " data-toggle="collapse" data-target="#collapseTwo">2. What is Bootstrap?</button>
            </h2>
        </div>
        <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#myAccordion">
            <div class="card-body">
                <p>Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development. It is a collection of CSS and HTML conventions. <a href="https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/" target="_blank">Learn more.</a></p>
            </div>
        </div>
    </div>
    <div class="card">
        <div class="card-header" id="headingThree">
            <h2 class="mb-0">
                <button type="button" class="btn btn-link collapsed text-success " data-toggle="collapse" data-target="#collapseThree">3. What is CSS?</button>
            </h2>
        </div>
        <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#myAccordion">
            <div class="card-body">
                <p>CSS stands for Cascading Style Sheet. CSS allows you to specify various style properties for a given HTML element such as colors, backgrounds, fonts etc. <a href="https://www.tutorialrepublic.com/css-tutorial/" target="_blank">Learn more.</a></p>
            </div>
        </div>
    </div>

      <div class="card">
        <div class="card-header" id="headingFour">
            <h2 class="mb-0">
                <button type="button" class="btn btn-link collapsed text-success" data-toggle="collapse" data-target="#collapseFour">4. What is JavaScript?</button>
            </h2>
        </div>
        <div id="collapseFour" class="collapse" aria-labelledby="headingFour" data-parent="#myAccordion">
            <div class="card-body">
                JavaScript is a dynamic computer programming language. It is lightweight and most commonly used as a part of web pages, whose implementations allow client-side script to interact with the user and make dynamic pages. It is an interpreted programming language with object-oriented capabilities. etc. <a href="https://www.tutorialspoint.com/javascript/javascript_overview.htm" target="_blank">Learn more.</a></p>
            </div>
        </div>
    </div>
</div>
    <div class="col-sm-6">
       <div class="p-4 anim2">
      <img clas="img-fluid img2" src="https://assets-ouch.icons8.com/preview/921/cdd912b0-27a4-48be-bc91-0aec7570dbce.png"/>
     </div></div>
</div>

<div class="container text-center mt-3 magicdiv">
<h2>Hi, Welcome to Web World</h2>
<button type="button" class="btn btn-success" onclick="showMagic()">Touch to see Magic</button>
<img class="img-fluid mt-2" id="magic" src="https://i.pinimg.com/originals/30/f8/f7/30f8f7eaa9f4dcfa506df11ddae32de2.gif"/>
</div>

<section>
<div class="container-fluid bg-success text-light mt-3">
<h2 class="text-center pt-3">+91 9874334745</h2>
<p class="text-center">Get information on telephone</p>
<div class="text-center">
<button class="btn btn-warning mb-4" type="button" disabled>
        <span class="spinner-grow spinner-grow-sm"></span>
       <a href="tel:+919874334745" class="text-light text-50">CALL ME</a>
    </button>
</div>
</section>


<!-- footer-->
<footer>
<p class="text-center text-light bg-dark p-2 mb-0"> © 2020 All Rights Reserved</p>
</footer>


<script>
function showMagic(){
document.getElementById("magic").style.display="block";
}
</script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>

</body>
</html>
