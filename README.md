<!DOCTYPE html>
<html lang="en">

<head>
     <meta charset="UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Shoehub</title>
     <link rel="stylesheet" href="bootstrap.min.css">
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
</head>

<body>
     <nav class="navbar navbar-expand-lg bg-white fixed-top">
          <div class="container">
               <a href="#" class="navbar-brand fw-bold">Shoehub</a>
               <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#nav">
                    <i class="bi-list"></i>
               </button>

               <div class="collapse navbar-collapse" id="nav">
                    <ul class="navbar-nav ms-auto">
                         <li class="nav-item">
                              <a href="#home" class="nav-link active">Home</a>
                         </li>
                         <li class="nav-item">
                              <a href="#about" class="nav-link">About</a>
                         </li>
                         <li class="nav-item">
                              <a href="#collections" class="nav-link">Collections</a>
                         </li>
                         <li class="nav-item">
                              <a href="#handcrafted" class="nav-link">Handcrafted</a>
                         </li>
                         <li class="nav-item">
                              <a href="#testimonies" class="nav-link">Testimonies</a>
                         </li>
                    </ul>
               </div>
          </div>
     </nav>
     <header class="p-5 p-lg-5 text-center text-sm-start" id="home">
          <div class="container mt-5">
               <div class="d-flex justify-content-center">
                    <div class="col-md-7">
                         <h1 class="display-2">Massive sales Discount</h1>
                         <p>A sales discount, also commonly known as just a 'discount' provides customers of a business
                              with a reduced rate on one or more of the products or services</p>
                         <button class="btn btn-warning">Get Started</button>
                    </div>
                    <div class="col-md-5 d-none d-sm-block">
                         <img src="introshoe.png" alt="" class="w-75 rounded-3">
                    </div>
               </div>
          </div>

     </header>

     <section class="p-5 bg-light" id="about">
          <div class="container text-center">
               <h3 class="text-muted">Are you looking for your favorite shoe?</h3>
               <div class="input-group mt-4">
                    <input type="text" placeholder="search for shoe" class="form-control shadow p-3">
                    <button class="btn btn-warning px-lg-5">Search</button>
               </div>

               <h3 class="my-4">About us</h3>
               <p class="px-lg-5">Most likely, they’re prospective customers considering the purchase
                    of your products or services. They’re trying to determine if
                    they can trust you. They want to peek behind the curtain and
                    see if your company is one they’d like to do business with.
                    They seek answers to questions like these:</p>
          </div>
     </section>




     <section class="p-5 bg-white" id="collections">
          <div class="container">
                <h3 class="text-center mb-3">Best selling shoes</h3>
               <div class="row">
                    <div class="col-md-3">
                         <img src="shoe1.png" alt="Shoe" class="w-100">
                         <div class="d-flex justify-content-between mt-3">
                              <div>
                                   <p class="m-0">Classic Brogues</p>
                                   <p class="m-0 fw-bold">$300</p>
                              </div>

                              <button class="btn btn-warning align-self-center"><i class="bi-cart"></i> </button>
                         </div>
                    </div>
                    <div class="col-md-3">
                         <img src="shoe2.png" alt="Shoe" class="w-100">
                         <div class="d-flex justify-content-between mt-3">
                              <div>
                                   <p class="m-0">Italian leather</p>
                                   <p class="m-0 fw-bold">$450</p>
                              </div>

                              <button class="btn btn-warning align-self-center"><i class="bi-cart"></i> </button>
                         </div>
                    </div>
                    <div class="col-md-3">
                         <img src="shoe3.png" alt="Shoe" class="w-100">
                         <div class="d-flex justify-content-between mt-3">
                              <div>
                                   <p class="m-0">Brogues</p>
                                   <p class="m-0 fw-bold">$200</p>
                              </div>

                              <button class="btn btn-warning align-self-center"><i class="bi-cart"></i> </button>
                         </div>
                    </div>
                    <div class="col-md-3">
                         <img src="shoe4.png" alt="Shoe" class="w-100">
                         <div class="d-flex justify-content-between mt-3">
                              <div>
                                   <p class="m-0">Classic covers</p>
                                   <p class="m-0 fw-bold">$800</p>
                              </div>

                              <button class="btn btn-warning align-self-center"><i class="bi-cart"></i> </button>
                         </div>
                    </div>
               </div>

          </div>
     </section>

     <section class="p-5 bg-light" id="handcrafted">
          <div class="container">
               <div class="row justify-content-center">
                    <div class="col-md-5">
                         <h1>Hand Crafted men Leather Shoe</h1>
                         <p class="fw-light text-muted my-3">Wearing adapted mens leather shoes is essential to walk comfortably.
                              Choose your walking shoe from our collection of wholesale Walking Style Shoes
                         </p>
                         <button class="btn btn-warning rounded-0 btn-lg mb-3">Buy now</button>
                    </div>
                    <div class="col-md-6">
                          <img src="shoe5.png" alt="" class="w-75 rounded-3">
                    </div>
               </div>
          </div>
     </section>

  <section class="p-5 bg-white" id="testimonies">
          <div class="container">
                <h2 class="text-center mb-1">Testimonies</h2>
                <div class="row">
                     <div class="col-md-4 mt-3">
                          <div class="card shadow border-0">
                                <div class="card-body">
                                       <div class="d-flex">
                                        <img src="img/julian.jpg" alt="" class="rounded-circle" height="53px" width="53px">
                                        <h6 class="align-self-center ms-3">Julian</h6>
                                        <div class="d-flex align-self-center ms-auto">
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                        </div>
                                       </div>
                                       <p class="text-muted">
                                           <small>  All the shoes that i bought from shoehub, fit in perfectly the quality is on another level. 
                                             the texture are good leather. I got my shoes three days after placing order, 
                                             i hope to buy more shoes from you guys.</small>
                                       </p>
                                       <p class="text-end fw-bold">03 sept 2022</p>
                                </div>
                          </div>
                     </div>
                     <div class="col-md-4 mt-3">
                          <div class="card shadow border-0">
                                <div class="card-body">
                                       <div class="d-flex">
                                        <img src="bellis.jpg" alt="" class="rounded-circle" height="53px" width="53px">
                                        <h6 class="align-self-center ms-3">Jennifer</h6>
                                        <div class="d-flex align-self-center ms-auto">
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                        </div>
                                       </div>
                                       <p class="text-muted">
                                           <small>  All the shoes that i bought from shoehub, fit in perfectly the quality is on another level. 
                                             the texture are good leather. I got my shoes three days after placing order, 
                                             i hope to buy more shoes from you guys.</small>
                                       </p>
                                       <p class="text-end fw-bold">03 sept 2022</p>
                                </div>
                          </div>
                     </div>
                     <div class="col-md-4 mt-3">
                          <div class="card shadow border-0">
                                <div class="card-body">
                                       <div class="d-flex">
                                        <img src="shipman.jpg" alt="" class="rounded-circle" height="53px" width="53px">
                                        <h6 class="align-self-center ms-3">Shipman</h6>
                                        <div class="d-flex align-self-center ms-auto">
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                              <i class="bi-star-fill text-warning" style="font-size:0.4rem ;"></i>
                                        </div>
                                       </div>
                                       <p class="text-muted">
                                           <small>  All the shoes that i bought from shoehub, fit in perfectly the quality is on another level. 
                                             the texture are good leather. I got my shoes three days after placing order, 
                                             i hope to buy more shoes from you guys.</small>
                                       </p>
                                       <p class="text-end fw-bold">03 sept 2022</p>
                                </div>
                          </div>
                     </div>
                </div>
          </div>
  </section>

  <footer class="bg-dark mt-5 p-5 position-relative">
       <div class="container">
               <p class="text-center text-white">Copyright &copy; Shoehub 2022</p>
               <a href="#" class="position-absolute bottom-0 end-0 p-5">
                     <i class="bi-arrow-up-square text-white"></i>
               </a>
       </div>
  </footer>



     <script src="bootstrap.min.js"></script>
</body>

</html>
