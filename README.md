# HTML BOOTSTRAP WEBSITE


<!DOCTYPE html>
<html lang="en">

<head>
    <meta http-equiv="Content-Type" content="text/html" charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
    <title>My BootStrap Example</title>
    <!--  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" /> -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <!--     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous"> -->
        <link rel="stylesheet" href="menu.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0-alpha.4/css/bootstrap.min.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/baguettebox.js/1.11.1/baguetteBox.min.css">

        <style>
          .jumbotron {
            text-align: center;
            padding: 20px;
            margin: 10px 0;
          }
    
          .gallery {
            padding: 40px;
          }
    
          .gallery img {
            width: 100%;
            height: 200px;
            border-radius: 0;
            position: relative;
            border-radius: 1;
          }
          div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

        </style>
    </head>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
    <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
<!-- <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"
    integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p"
    crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js"
    integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF"
    crossorigin="anonymous"></script> -->
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
    integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
    crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
    integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
    crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
    integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
    crossorigin="anonymous"></script>
    
<body>
    
    <div class="container" style="background-image: url('m.jpg');width:max-content;height:max-content">
        <nav class="navbar navbar-expand-lg navbar-inverse navbar-fixed-top">
            <div class="navbar-header nav nav-tabs">
                <div class="thumbnail">
                   
                <a class="navbar-brand" href="ARAVIND.jpg">Logo</a>
              </div></div>
            
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto nav nav-tabs">
                    <li class="nav-item active">
                        <a class="nav-link" href="">Home <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About Us</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"href="#photo">
                            Photographs
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="https://www.bing.com/images/search?q=landscape&form=HDRSC3&first=1&tsc=ImageBasicHover">landscape</a>
                            <a class="dropdown-item" href="https://www.bing.com/images/search?q=nature&qs=n&form=QBIR&sp=-1&ghc=1&pq=nature&sc=8-6&cvid=A9065FB2574E4C4F9A1C840FD6893086&first=1&tsc=ImageBasicHover">Nature</a>
                            <div class="dropdown-divider"></div>
                            <a class="dropdown-item" href="https://www.bing.com/images/search?q=river&qs=n&form=QBIR&sp=-1&pq=river&sc=8-5&cvid=82E81F30565246369356DD5F0F7D6F84&first=1&tsc=ImageBasicHover">River</a>
                        </div>
                    </li>
                   
                </ul>
               
                
       
                <li class="dropdown">
                    <a class="dropdown-toggle" data-toggle="dropdown" href="#">MORE
                    <span class="caret"></span></a>
                    <ul class="dropdown-menu">
                <li><a href=""class="btn btn-default btn-rounded mb-4" data-toggle="modal" data-target="#modalRegisterForm"> Sign Up</a></li>
                
                </li>
                    <li><a href=""class="btn btn-default btn-rounded mb-4" data-toggle="modal" data-target="#modalRegisterForm2"> Login</a></li>
                </ul>
            </li>
            <form class="form-inline my- my-1 lg-1">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-lg my-2 my-sm-0" type="submit">Search</button>
                
                
            </form>
               
            
            </div>
        </nav>
    </div>

    
    

    <section class="about" id="about">
        <div class="content">
          <div class="title"><span><h1>Photography</h1></span></div>
          <div class="media">
            <div class="media-left">
              <img src="x.png" class="media-object" style="width:300px">
            </div>
          
        </div>
        
        </div>
      </section>


    

      <div class="container-fluid">
        <div class="jumbotron">
          <h1>Photography</h1>
          <p>Photography is the art, application, and practice of creating durable images by recording light, either electronically by means of an image sensor, or chemically by means of a light-sensitive material such as photographic film. It is employed in many fields of science, manufacturing, and business, as well as its more direct uses for art, film and video production, recreational purposes, hobby, and mass communication.</p>
        </div>
        
        <div class="row gallery">
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="20.jpg">
              <img class="img-fluid"src="20.jpg">
            </a>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="25.JPG">
              <img class="img-fluid" src="25.JPG">
            </a>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="27.jpg">
              <img class="img-fluid"src="27.jpg">
            </a>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="28.jpg">
              <img class="img-fluid"src="28.jpg">
            </a>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="29.jpg">
              <img class="img-fluid"src="29.jpg">
            </a>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="30.jpg">
              <img class="img-fluid"src="30.jpg">
            </a>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="31.jpg">
              <img class="img-fluid"src="31.jpg">
            </a>
          </div>
          <div class="col-sm-6 col-md-4 col-lg-3">
            <a href="32.jpg">
              <img class="img-fluid"src="32.jpg">
            </a>
          </div>
        </div>
      </div>
    
      <script src="https://cdnjs.cloudflare.com/ajax/libs/baguettebox.js/1.11.1/baguetteBox.min.js"></script>
      <script>
        baguetteBox.run(".gallery", {
          animation: "slideIn"
        });
      </script>
      

<div class="modal fade" id="modalRegisterForm" tabindex="-1" role="dialog" aria-labelledby="myModalLabel"
  aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header text-center">
        <h4 class="modal-title w-100 font-weight-bold">Sign up</h4>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body mx-3">

        <form action="/action_page.php" class="was-validated">
    <div class="form-group">
      <label for="uname">Username:</label>
     
      <input type="text" class="form-control" id="uname" placeholder="Enter username" name="uname" required>
      
      <div class="valid-feedback">Valid.</div>
      <div class="invalid-feedback">Please fill out this field.</div>
    </div>
    <div class="form-group">
      <label for="pwd">Password:</label>
      <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd" required>
      <div class="valid-feedback">Valid.</div>
      <div class="invalid-feedback">Please fill out this field.</div>
    </div>
  
    <div class="form-group">
      <label for="DATE">DOB:</label>
      <input type="datetime-local" class="form-control" id="DATE" placeholder="Enter DATE" name="DATE" required>
      <div class="valid-feedback">Valid.</div>
      <div class="invalid-feedback">Please fill out this field.</div>
    </div>
    <fieldset class="form-group">
      <div class="row">
      <legend class="col-form-label col-3">Gender</legend>
      <div class="col-9">
      <div class="form-check">
      <label class="form-check-label">
      <input class="form-check-input" type="radio" name="legendRadio" id="legendRadio1" value="1">
      Male
      </label>
      </div>
      <div class="form-check">
      <label class="form-check-label">
      <input class="form-check-input" type="radio" name="legendRadio" id="legendRadio2" value="2" checked>
      Female
      </label>
      </div>
      
      </div>
      </div>
      </fieldset>
      <div class="custom-file">
        <input type="file" class="custom-file-input" id="customFile">
        <label class="custom-file-label" for="customFile">Choose file</label>
      </div>
    <div class="form-group form-check">
      <label class="form-check-label">
        <input class="form-check-input" type="checkbox" name="remember" required> I agree on Terms and Condition.
        <div class="valid-feedback">Valid.</div>
        <div class="invalid-feedback">Check this checkbox to continue.</div>
      </label>
    </div>
    
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
      </div>
      <div class="modal-footer d-flex justify-content-center">
        
      </div>
    </div>
  </div>
</div>


<div class="modal fade" id="modalRegisterForm2" tabindex="-1" role="dialog" aria-labelledby="myModalLabel"
  aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header text-center">
       
        <h4 class="modal-title w-100 font-weight-bold">Sign up</h4>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body mx-3">

        <form action="/action_page.php" class="was-validated">
    <div class="form-group">
      <label for="uname">Username:</label>
     
      <input type="text" class="form-control" id="uname" placeholder="Enter username" name="uname" required>
      
      <div class="valid-feedback">Valid.</div>
      <div class="invalid-feedback">Please fill out this field.</div>
    </div>
    <div class="form-group">
      <label for="pwd">Password:</label>
      <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd" required>
      <div class="valid-feedback">Valid.</div>
      <div class="invalid-feedback">Please fill out this field.</div>
    </div>
  
    
   
  </form>
      </div>
      <div class="modal-footer d-flex justify-content-center">
        <button type="submit" class="btn btn-primary">Submit</button>
      </div>
    </div>



          </div>
        </div>
      </div>

      
</body>

</html>
