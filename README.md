<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>https://welcome to craft market</title>

    
    <style>
       html{
         scroll-behavior: smooth;
       }
        body{
        margin: 0;
        padding: 0;
        background-color:rgb(255, 255, 255) ;
      }
      
      .navbar-brand{
        padding: 0;
        margin: 0;
        font-size: 30px;
        font-weight: 500;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        letter-spacing: 2px;
        color: rgb(214, 115, 49);

      }
      .nav-link{
        color: black;
        font-size: 20px;
        font-weight: 500;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
      }
      .nav-link:hover{
        transition: .3s;
        transform: scale(1.1);
      }
      .navbar-toggler-icon .fa{
        color: black;
        padding: auto;
        margin: auto;
      }
      
      .card{
        border: 1px;
        

        
      }
      
      
      .card-img-top{
        background-size: cover;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        display: block;
        border-radius: 20px;
      }
      .card:hover .card-img-top{
        transition: 1s;
        transform: scale(1.1);
        box-shadow:0 8px 19px rgba(0,0,0,0.7) ;
        border-radius: 2px;
       
      }
      .card-body{
        position:absolute;
        color: rgb(230, 222, 222);
        text-align: center;
        top: 13vh;
        left: 15px;
        right: 64px;
        font-weight: 500;
        background-color:rgba(43, 41, 41, 0.445) ;
        
      }
      #productx{
        width: 85%;
        margin: auto;
        
      }
      
      .product-img{
          display: grid;
          grid-template-rows: 280px 280px;
          grid-template-columns: repeat(4, 1fr);
          grid-gap: 30px;
          justify-content: center;
      }
    
      #div1{ background: url(https://images.pexels.com/photos/1253189/pexels-photo-1253189.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500);width: 310px; background-size: cover;}
      #div2{background: url(https://images.pexels.com/photos/744563/pexels-photo-744563.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500);width: 310px; background-size: cover;}
      #div3{background: url(https://t4.ftcdn.net/jpg/03/32/99/49/240_F_332994977_o5Znn5C45CZfjpdXajYVK2h89MgyfolK.jpg);width: 310px; background-size: cover;}
      #div4{background: url(https://t3.ftcdn.net/jpg/02/85/56/64/240_F_285566402_xmuOUoVodQNevtrd58v6KyCrF4hFCR30.jpg);width: 310px; background-size: cover;}
      #div5{background: url(https://t4.ftcdn.net/jpg/01/40/50/87/240_F_140508746_2aatqanjcWK8bqmTPXdZa9ZtPXBx9Cj1.jpg);width: 310px; background-size: cover;}
      #div6{background: url(https://t3.ftcdn.net/jpg/01/70/54/10/240_F_170541078_7PXiXDobdIbOvPitZJ46I2BsvTPxkPRi.jpg);width: 310px; background-size: cover;}
      #div7{background: url(https://t4.ftcdn.net/jpg/02/91/27/11/240_F_291271111_awZ0k6EhK7k6wnLCIzO5xCD3Hi10uWeL.jpg);width: 310px; background-size: cover;}
      #div8{background: url(https://t3.ftcdn.net/jpg/03/16/03/12/240_F_316031223_ngCAjLrEFmw9eyqzE5RYY2a9OGfiNXK0.jpg);width: 310px; background-size: cover;}
      .btn{
       color: black;
       font-size: 17px;
       font-weight: 400;
       margin-top: 220px;
       margin-left: 120px;
       padding-left: 20px;
       padding-right: 20px;
       background-color: rgba(31, 172, 177, 0.685);

     }
     .btn:hover{
      background-color: rgb(57, 237, 243);
      box-shadow:5px 10px 10px rgba(12, 12, 12, 0.7) ;
      font-size: 19px;
      font-weight: 500;
     }
      .pimage:hover{
        transition: 1s;
        transform: scale(1.08);
        box-shadow:0 8px 19px rgba(0,0,0,0.4) ;
        }
        #view1{
          margin-bottom: 2%;
          margin-top: 1%;
          margin-left: 43%;
          padding:5px 10px;
          font-size: 16px;
          font-weight: 500;
          background-color: rgb(207, 245, 233);
          box-shadow: 0px 8px 8px rgba(12, 12, 12, 0.7);
        }
        #view1:hover{background-color:rgb(144, 247, 214) ;
        }
        .container{
            width: 90%;
            margin: auto;
            overflow: hidden;

        }
        #contact-section{
            background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.9)), url(https://images.pexels.com/photos/326576/pexels-photo-326576.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500);
            background-size: cover;
            background-position: center;
            height: 100%;
            width: 100%;
            padding-bottom: 2%;
        }
        #contact-section .container h2{
            text-align: center;
            text-decoration: underline;
            text-underline-position: under;
            color: rgb(238,235,235);
            letter-spacing: 2px;

        }
        #contact-section .container p{
            text-align: center;
            width: 70%;
            margin-left: auto;
            margin-right: auto;
            padding-bottom: 3%;
            color: #fff;
            letter-spacing: 3px;
        }
        .contact-form i.fa{
            font-size: 22px;
            padding: 3%;
            background-color: none;
            margin: 2%;
            border-radius: 80%;
            cursor: pointer;
            border: 2px solid rgb(190,190,190);
            color: rgb(190,190,190);

        }
        .contact-form i.fa:hover{
            cursor: pointer;
            border: 2px solid #fff;
            color: #fff;


        }
        .contact-form{
            display: grid;
            grid-template-columns: auto auto;
            /* grid-gap: 5px; */

        }
        .form-info{
            font-size: 16px;
            font-style: italic;
            color: #fff;
            letter-spacing: 2px;
        }
        input{
            padding: 10px;
            margin: 10px 0;
            width: 70%;
            background-color: rgba(136, 133, 133,0.5);
            color: #fff;
            border: none;
            outline: none;


        }
        input::placeholder{
            color: #fff;

        }
        textarea{
            padding: 10px;
            margin: 10px;
            width: 70%;
            background-color: rgba(136, 133, 133,0.5);
            color: #fff;
            border: none;
            outline: none;

        }
        textarea::placeholder{
            color: #fff;

        }.submit{
            width: 40%;
            background: none;
            padding: 4px;
            outline: none;
            font-size: 13px;
            font-weight: bold;
            letter-spacing: 2px;
            height: 33px;
            text-align: center;
            cursor: pointer;
            margin-left:3% ;
            border: 2px solid rgb(190,190,190);
            color: rgb(190,190,190);

        }
        .submit:hover{
            border: 1px solid #fff;
            color: #fff;
            cursor: pointer;


        }
        .footer{
          width: 100%;
          background-color: rgb(243, 186, 111);
          text-align: center;
        }
        .text-footer{
          font-size: 17px;
          font-weight: 400;
        }
        /* media queries */
        @media (max-width: 768px){
          html{scroll-behavior: smooth;}
          body{
            margin: 0;
            padding: 0;
          }
          .carousel #carousel3{
            height: 164px;
          }
            #contact-section .contact-form{
                display: block;
                width: 100%;
                text-align: center;

            }
            #contact-section .submit{
                width: 60%;

            }
            .row{
              display: block;
              
            }
            .row .card{
              width: 150px;
            }
            .row #card1{margin-bottom: 20px;}
            .row #card2{margin-bottom: 30px;}
            
            .row .card-img-top{
              width: 150px;
              height: 200px;
            }
            .row .card .card-body{
              width: 300px;
            }
            .product-img{
              display: block;
              justify-content: center;
              
            }
            .product-img #div1{margin-bottom: 5%;}
            .product-img #div2{margin-bottom: 5%;}
            .product-img #div3{margin-bottom: 5%;}
            .product-img #div4{margin-bottom: 5%;}
            .product-img #div5{margin-bottom: 5%;}
            .product-img #div6{margin-bottom: 5%;}
            .product-img #div7{margin-bottom: 5%;}
        }
        



     
    </style>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg bg-light" style="position: sticky;top: 0;z-index: 1;">
        <a class="navbar-brand ml-5" href="#">CRAFT MARKET</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"><i class="fa fa-bars" aria-hidden="true"></i></span>
        </button>
      
        <div class="collapse navbar-collapse" id="navbarSupportedContent" style="font-size: large; font-weight: 500;">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a class="nav-link mr-5" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link mr-5" href="#features">Features</a>
            </li>
            <li class="nav-item">
                <a class="nav-link mr-5" href="#productx">Products</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#contact-section">Contact</a>
              </li>
          </ul>
        </div>
        
      </nav>

      <!--it's carousel-->
      <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://img1.wsimg.com/isteam/ip/244d0041-c285-4c69-bde7-a5a602c98e97/1e3e4f54-1dde-4e58-b7ba-ded397dc5186.JPG/:/cr=t:25.32%25,l:0%25,w:100%25,h:74.68%25/rs=w:900,h:450,cg:true" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://img1.wsimg.com/isteam/ip/244d0041-c285-4c69-bde7-a5a602c98e97/6f78a1f1-7a58-4048-a58f-06f8427bdba8.jpg/:/cr=t:0%25,l:18.56%25,w:76.92%25,h:100%25/rs=w:900,h:450,cg:true" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://img1.wsimg.com/isteam/ip/244d0041-c285-4c69-bde7-a5a602c98e97/5d002ad0-0a76-416c-8482-f5bddd165424.jpg/:/rs=w:1950,h:1200" class="d-block w-100" id="carousel3" height="760vh" alt="...">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
      <!--features box-->
      <div class=" container-fluid" id="features">
        <h1 class="text"  style="text-align: center;margin-top: 3rem;margin-bottom: 1.5rem; font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;">features</h1>
        <div class="row" style="justify-content: space-evenly;">
        <div class="card col-3" id="card1" >
          <img src="https://images.pexels.com/photos/230544/pexels-photo-230544.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" style="width:300px; height: 44vh;" class="card-img-top" alt="...">
          <div class="card-body">
            <h4 class="card-title">Superfast Delivery</h4>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
        <div class="card col-3" id="card2" >
          <img src="https://images.pexels.com/photos/296916/pexels-photo-296916.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" style="width:300px; height: 44vh;" class="card-img-top" alt="...">
          <div class="card-body">
            <h4 class="card-title">Online Shopping</h4>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
        <div class="card col-3" id="card3" >
          <img src="https://images.pexels.com/photos/259249/pexels-photo-259249.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" style="width:300px; height: 44vh;" class="card-img-top" alt="...">
          <div class="card-body">
            <h4 class="card-title">Ease Return</h4>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>
      </div>
      <div>
        <!-- product box -->
        <div class="Products" id="productx">
            <h2 style="text-align:center;padding-top: 30px;">products</h2>
            <div class="product-img" >
              <div class="pimage" id="div1">
                <button type="button" class="btn "> BUY </button>
              </div>
              <div class="pimage" id="div2">
                <button type="button" class="btn "> BUY </button>
                  </div>
                <div class="pimage" id="div3">
                  <button type="button" class="btn "> BUY </button>
                  </div>
                <div class="pimage" id="div4" >
                  <button type="button" class="btn "> BUY </button>
                  </div>
                <div class="pimage" id="div5">
                  <button type="button" class="btn "> BUY </button>
                  </div>
                <div class="pimage" id="div6">
                  <button type="button" class="btn "> BUY </button>
                  </div>
                <div class="pimage" id="div7" >
                  <button type="button" class="btn "> BUY </button>
                  </div>
                <div class="pimage" id="div8" >
                  <button type="button" class="btn "> BUY </button>
                  </div>
            </div>
          </div>
          <a href="productpage.html"><button type="button" class="button " id="view1" data-toggle="modal" data-target="#productpage">View More</button></a>
      </div>
      <!-- contact form -->
      <section id="contact-section">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email us and keep upto date with our latest news</p>
            <div class="contact-form">
                <!--first grid section-->
                <div>
                  <i class="fa fa-map-marker" aria-hidden="true"></i><span class="form-info">City Bhadrak Odisha #756</span><br>
                  <i class="fa fa-phone" aria-hidden="true"></i><span class="form-info">Phone no +91 9348201247</span><br>
                  <i class="fa fa-envelope" aria-hidden="true"></i><span class="form-info">srinath.bhadrak@gmail.com</span><br>
                </div>
                <!--second grid-->
                <div>
                    <form>
                        <input type="text" placeholder="Your Name" required>
                        <input type="text" placeholder="Last Name" required>
                        <input type="email" placeholder="Email" required>
                        <input type="text" placeholder="subject to this message" required>
                        <textarea name="message" placeholder="message" rows="5" required></textarea>
                        <button class="submit">Send Message</button>
                    </form>

                </div>
            </div>
        </div>

    </section>
    <div class="footer"><i class="text-footer">copyright &copy; 2020<br>
      Design & Developement By:-SRINATH SHITIKANTHA</i></div>

    <!-- Optional JavaScript -->
    

    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  </body>
</html>
