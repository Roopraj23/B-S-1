# B-S-1
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <link rel="stylesheet" type="text/css" href="css/style2.css">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
  <style>
     .carousel-inner img {
        width: 100%;
        height: 100%;
       }
  </style>
  <style>
  .dropdown:hover>.dropdown-menu{
    display: block;
    
  } </style>
</head>
<body>
    <div claass="container">
      <nav class="navbar navbar-expand-sm fixed-top bg-dark navbar-dark justify-content-end" >
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          
          <div class="collapse navbar-collapse" id="collapsibleNavbar">
             
              <div class="container">
                  <ul class="navbar-nav justify-content-end ">
                  <li class="nav-item"><a class="nav-link active" href="#">Home</a></li> 
                  <li class="nav-item dropdown"> 
                    <a class="nav-link " href="#" id="DropdownLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" >Service</a>
                    <div class="dropdown-menu" aria-labelledby="DropdownLink">
                      <a class="dropdown-item" href="#">Action</a>
                      <a class="dropdown-item" href="#">Another action</a>
                      <a class="dropdown-item" href="#">Something else here</a>
                    </div>   
                  </li>            
                  <li class="nav-item"><a class="nav-link" href="#">Gallery</a></li> 
                  <li class="nav-item"><a class="nav-link" href="#">About</a></li>  
                
                  <form class="form-inline" action="/action_page.php">
                    <input class="form-control mr-xs-2" type="text" placeholder="Search">
                    <button class="btn btn-success" type="submit">Search</button>
                  </form>
              </ul>  
              
  </div>            
  
  
</div>

</nav>
</div>

<div id="demo" class="carousel slide" data-ride="carousel"  >

  <!-- Indicators -->
  <ul class="carousel-indicators" >
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
  </ul>
  
  <!-- The slideshow -->
  <div class="carousel-inner"   >
    <div class="carousel-item active">
      <img src="bike1.jpg" alt="Los Angeles"  >
      <div class="carousel-caption">
        <div class="" >
          <button type="button" class="btn btn-light" >Log in</button>
          <button type="button" class="btn btn-light ">Sign in</button>
        </div>
      </div>
    </div>
    <div class="carousel-item">
      <img src="bike2.jpg" alt="Chicago">
    </div>
    <div class="carousel-item">
      <img src="bike3.jpg" alt="New York" >
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

    
      </div>
      <br><br><br><br>
     
     
    <div class="container">
  
      <div class="card-deck ">
        <div class="card bg-light col-sm-6 col-md-4">
          <div class="card-body text-center">
            <p class="card-text">History of bicycle started with the first two wheeled transportation device made by German Baron Karl Drais in early 19th century.</p>
            
            
          </div>
        </div>
        <div class="card bg-light col-sm-6 col-md-4">
          <div class="card-body text-center">
            <p class="card-text">In the 21st century, the motorcycle industry is mainly dominated by the Indian motorcycle industry and by Japanese motorcycle companies.</p>
          </div>
        </div>
        
        <div class="card bg-light col-sm-6 col-md-4">
          <div class="card-body text-center">
            <p class="card-text"> The future of transportation looks to be merging with sci-fi. But the bike-tech revolution reminds us that innovation isn't always about the totally new</p>
          </div>
        </div>  
      </div>
    </div>
    <br><br>
    <div class="jumbotron text-center " style="margin-bottom:0; background-color: black; color: white">
        <div class="row">
            <div class=" col-sm-4 col-md-3 col-lg-3">
              <h4>Web create</h4>
              <h6>Rj_creater</h6> 
              <h6>ready_to_start</h6>  
            </div>
            <div class="col-sm-4 col-md-3 col-lg-3">
                <h4>Useful Links</h4>
                <h6>Lets together</h6> 
                <h6>Be reaady</h6>
                <h6>Contact Us</h6>
              </div>
            <div class="col-sm-4 col-md-3 col-lg-3">
              <h4>follow Us</h4>
             <a href="#" class="twitter"><i class="fa fa-twitter"></i></a>
             <a href="#" class="facebook"><i class="fa fa-facebook"></i></a>
             <a href="#" class="instagram"><i class="fa fa-instagram"></i></a>
            </div>
          </div>
    </div>
   
 </body>
</html>
