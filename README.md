<!DOCTYPE html>
<html lang="en">
<head>
  <title>WEBSITE-NEW</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
<meta name="viewport" content="width= device-width initial-scale=1.0">
  <style>
  	ul a:hover{

  background-color: aqua;
  }
  </style>
  
</head>


<body>
	<div class="container-fluid">
<div class="row">
<div class="col-md-8">
<nav class="navbar navbar-expand-sm navbar-dark bg-dark">
  <!-- Brand/logo -->
  <a class="navbar-brand" href="#">
    <img src="ec.jpg" alt="logo" style="width:90px;">
  </a>
   <ul class="nav nav-pills ">
    <li class="nav-item">
      <a class="nav-link" href="#cl1">Men</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#cl2">Women</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#cl3">Kids</a>
    </li>
  </ul>
</nav>
</div>
<div class="col-md-4">
<nav class="navbar navbar-expand-lg navbar-dark ">
	<form class="form-inline" action="css.html">
		<input type="text" placeholder="search" class="form-control mr-sm-4">
		<button class="btn btn-danger" type="submit">Search</button>
		</form></nav></div>	
</div>
</div>
<div class="container-fluid">
<div id="demo" class="carousel slide" data-ride="carousel">

  <!-- Indicators -->
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
     <li data-target="#demo" data-slide-to="3"></li>
  </ul>
  
  <!-- The slideshow -->
  <div class="carousel-inner">
    <div class="carousel-item active">

      <img src="a1.jpg" alt="" width="100%">
     <div class="center"> abc </div>
    </div>
    <div class="carousel-item">
      <img src="a2.jpg" alt="Chicago" width="100%" >
    </div>
    <div class="carousel-item">
      <img src="rs.jpg" alt="New York" width="100%" >
    </div>
     <div class="carousel-item">
      <img src="js.jpg" alt="New York" width="100%">
    </div>
  </div>
  
  <!-- Left and right controls -->
  <a class="carousel-control-prev" href="#demo" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#demo" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div>
<div class="row">
	<div class="col-md-4">

<div class="card" style="width:400px" id="cl1">
    <img class="card-img-top" src="men.png" alt="Card image" style="width:100%">
    <div class="card-body bg-danger">
      <h4 class="card-title">MEN</h4>
      <p class="card-text">Branded Collections</p>
      <a href="Mencoll.html" class="btn btn-primary">Go for it</a>
    </div>


	</div>

</div>




	<div class="col-md-4">

		<div class="card" style="width:400px" id="cl2">
    <img class="card-img-top" src="wm1.png" alt="Card image" style="width:100%">
    <div class="card-body bg-primary">
      <h4 class="card-title">WOMEN</h4>
      <p class="card-text">Branded Collections</p>
      <a href="womencoll.html" class="btn btn-primary">Go for it</a>
    </div>
	</div>
</div>
	<div class="col-md-4">

		<div class="card" style="width:400px"id="cl3">
    <img class="card-img-top" src="kids.png" alt="Card image" style="width:100%">
    <div class="card-body bg-warning">
      <h4 class="card-title">KIDS</h4>
      <p class="card-text">Branded Collections</p>
      <a href="kidscoll.html" class="btn btn-primary">Go for it</a>
    </div>
	</div>
</div>
</div>
<div class="row">
	<div class="col-md-6">
		  <form action="boot.html">
    <div class="form-group">
      <label for="email">Email:</label>
      <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
    </div>
    <div class="form-group">
      <label for="pwd">Password:</label>
      <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd">
    </div>
   
      <div class="form-group">
      <label for="mobileno">mobile no : </label>
      <input type="number" class="form-control" id="number" placeholder="Enter number" name="mbno">
    </div>
      <div class="dropdown">
<button type="button" class="btn btn-success dropdown-toggle" data-toggle="dropdown">abc</button>
<div class="dropdown-menu">
<a href="" class="dropdown-item">India</a>
<a href="" class="dropdown-item">USA</a>
<a href="" class="dropdown-item ">France</a>
<a href="" class="dropdown-item ">Japan</a>

</div></div>
 <div class="form-group">
      <label for="address">Address:</label>
      <input type="text" class="form-control" id="adrs" placeholder="Enter address" name="address">
    </div>

 <div class="form-group form-check">
      <label class="form-check-label">
        <input class="form-check-input" type="checkbox" name="remember">remember me
      </label></div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
	</div>
<div class="col-md-6">
	<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d874032.7595142358!2d76.70595346542946!3d31.159989431804398!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390578e3e35d6e67%3A0x1f7e7ff6ff9f54b7!2sShimla%2C%20Himachal%20Pradesh!5e0!3m2!1sen!2sin!4v1600847004592!5m2!1sen!2sin" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe></div></div>	</div>
<ul class="pagination justify-content-center">
    <li class="page-item"><a class="page-link" href="">Previous</a></li>
    <li class="page-item"><a class="page-link" href="">1</a></li>
    <li class="page-item"><a class="page-link" href="Mencoll.html">2</a></li>
     <li class="page-item"><a class="page-link" href="womencoll.html">3</a></li>
     <li class="page-item"><a class="page-link" href="kidscoll.html">4</a></li>
    <li class="page-item"><a class="page-link" href="">Next</a></li>
  </ul>

</body>
</html>
