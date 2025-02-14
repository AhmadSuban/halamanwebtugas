<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

    <style>
      body{

         font-family: arial, sans-serif;
         background-image: url(nana.jpg);
      
      h1{
        margin-top: 20px;
         margin-left: ;
         color: blue;
         font-weight: bold;
      }
      p{
        text-align: justify;
      }
      img{
        width: 100%;
        margin-top: 50px;
        border-radius: 10px; <--
        padding: 10px; <--

            }

      button{
         align-items: center;
         font-family: Arial, Helvetica, sans-serif;
         background-color: aqua;
         position-area: center;
          }
      
    

    </style>



  </head>
  <body class="mt-2 ms-5 me-4">
    <div >
      <div>
        <nav class="navbar navbar-dark bg-dark fixed-top">
          <div class="container-fluid">
            <a class="navbar-brand" href="#">Menu</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
              <div class="offcanvas-header">
                <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Tomorrowland</h5>
                <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
              </div>
              <div class="offcanvas-body">
                <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Link Live</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      More Information
                    </a>
                    <ul class="dropdown-menu dropdown-menu-dark">
                      <li><a class="dropdown-item" href="#">Artist</a></li>
                      <li><a class="dropdown-item" href="#">Priceng List</a></li>
                      <li>
                        <hr class="dropdown-divider">
                      </li>
                      <li><a class="dropdown-item" href="#">Schedule</a></li>
                    </ul>
                  </li>
                </ul>
                <form class="d-flex mt-3" role="search">
                  <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                  <button class="btn btn-success" type="submit">Search</button>
                </form>
              </div>
            </div>
          </div>
        </nav>
      </div> <br><br>

      <div class="row">
        <div class="col-12 col-lg-6">
          <br><br>
            <h4><u>@WorldFestivalMusic</u></h3>
                
            <h1>Tomorrowland Winter returns to Alpe d'Huez in 2025</h1> 

            <p>The magical story of Tomorrowland Winter continues! Tomorrowland will return in 2025 to the breathtaking French ski resort of Alpe d'Huez for the fifth edition of Tomorrowland Winter.Prepare for a magnificent new chapter on October 10-12, 2025, Pre-Registration for ticket sales is now open.</p>

            <p>Get ready for an unforgettable experience as Tomorrowland Winter returns to the stunning French Alps for its fifth edition! From March 15 to March 22, 2025, the world's most iconic winter festival will once again transform Alpe d'Huez into a breathtaking wonderland of music, snow, and adventure.

            Join thousands of festival lovers from around the globe and immerse yourself in a unique fusion of electronic beats, mesmerizing stage designs, and the magical backdrop of the mountains. With an incredible lineup of world-class artists, thrilling ski slopes, and legendary après-ski parties, this is a journey you don't want to miss!</p>

            <button style="display: block; margin: auto;"><b>Register Now</b></button> <br>

            <p>Don't miss out on the magic! Pre-register now and secure your chance to be part of Tomorrowland Winter 2025—an unforgettable fusion of music, snow, and adventure in the heart of the French Alps! 🎶❄️✨ #TomorrowlandWinter</p>

        </div>
        <div class="col-lg-6">
            <img src="festival.png" alt="">
            <br><br>
        </div>

        <div>
          <form>
            <div class="mb-3">
              <label for="exampleInputEmail1" class="form-label">Email address</label>
              <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
              <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
            </div>
            <div class="mb-3">
              <label for="exampleInputPassword1" class="form-label">Password</label>
              <input type="password" class="form-control" id="exampleInputPassword1">
            </div>
            <div class="mb-3 form-check">
              <input type="checkbox" class="form-check-input" id="exampleCheck1">
              <label class="form-check-label" for="exampleCheck1">Check me out</label>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
          </form>
        </div>
        
    </div>

    
   
   


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
