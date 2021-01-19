<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document
    <!--typo -->
        <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&family=Work+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/themify_icons.css">
    </title>
    <!--BOOTSTRAP-->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
    integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <!--CUSTOM CSS-->
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/themify-icons.css">
</head>

<body>
    <div class="container">
        <!--NAVBAR-->  
        <nav class="navbar navbar-expand-lg navbar-light">
          <a class="navbar-brand" href="#">
          <img src="images/logo.png" alt="" class="img-fluid"></a>
          <button class="navbar-toggler border-0" type="button" 
          data-toggle="collapse" data-target="#navbarNavDropdown" 
          aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="ti-align-justify"></span>
        </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">HOME<span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink1" role="button" 
        data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          ABOUT
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink1">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink2" role="button" 
        data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          PORTFOLIO
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink2">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink3" role="button" 
        data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          BLOG
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink3">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">CONTACT</a>
      </li>
    </ul>
    </div>
        </nav>
        <!--FIN NAVBAR-->
        <div class="px-lg-2">
        <!--TITRE ANIME--> 
        <h1 class="mt-5 mb-3 pt-3">I provide<span class="d-block">Design Solution.</span></h1>
        <p class="w-57 pb-5">I must explain to you how all this mistaken idea of denouncing pleasure and praising pain
            was born and I will give you a complete account of the system
        </p>
        <!--FIN TITRE ANIME--> 
        <!--MENU SECONDAIRE-->
        <nav>
            <ul class="d-flex flex-wrap list-unstyled my-2 pt-5">
                <li><a href="" class="text-secondary active d-inline-block mt-3 mb-2" data-cat="all">ALL PROJECTS</a></li>
                <li><a href=""class="text-secondary d-inline-block mt-3 mb-2" data-cat="design">UI/UX DESIGN</a></li>
                <li><a href=""class="text-secondary d-inline-block mt-3 mb-2" data-cat="branding">BRANDING</a></li>
                <li><a href=""class="text-secondary d-inline-block mt-3 mb-2" data-cat="web">WEB DEVELOPMENT</a></li>
                <li><a href=""class="text-secondary d-inline-block mt-3 mb-2" data-cat="photography">PHOTOGRAPHY</a></li>            
            </ul>
        </nav>
        <!--FIN MENU SECONDAIRE-->
        <!--MOSAIQUE IMAGE-->
        <section class="row" id="mosaique">
            <div class="col-6 col-md-4 mt-3" data-type="design"><img src="images/portfolio/1.jpg" class="img-fluid"></div>
            <div class="col-6 col-md-4 mt-3" data-type="design"><img src="images/portfolio/2.jpg" class="img-fluid"></div>
            <div class="col-6 col-md-4 mt-3" data-type="branding"><img src="images/portfolio/3.jpg" class="img-fluid"></div>
            <div class="col-6 col-md-4 mt-3" data-type="web"><img src="images/portfolio/4.jpg" class="img-fluid"></div>
            <div class="col-6 col-md-4 mt-3" data-type="barnding"><img src="images/portfolio/5.jpg" class="img-fluid"></div>
            <div class="col-6 col-md-4 mt-3" data-type="photography"><img src="images/portfolio/5.jpg" class="img-fluid"></div>
        </section>
        <!--FIN MOSAIQUE IMAGE-->
    </div>
</div>  
<hr class="my-5">
<div class="container services mb-5">
    <h2 class="mb-2">Core Services.</h2>
    <p class="w-50 mb-5 pb-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus,
        totam ipsa quia hic odit a sit laboriosam voluptatem in, blanditiis.</p>
    <div class="row">
        <div class="col-12 col-md-4 d-flex px 0 mb-5">
            <div class="col-2">
                <span class="ti-layout"></span>
            </div>
            <div class="col-10">
                <h3>Web Development </h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, earum.</p>
            </div>
        </div>
        <div class="col-12 col-md-4 d-flex px 0 mb-5">
            <div class="col-2">
                <span class="ti-announcement"></span>
            </div>
            <div class="col-10">
                <h3>Digital Marketing </h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, earum. </p>
            </div>
        </div>
        <div class="col-12 col-md-4 d-flex px 0 mb-5">
            <div class="col-2">
                <span class="ti-layers"></span>
            </div>
            <div class="col-10">
                <h3>Graphics Design</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, earum.</p>
            </div>
        </div>
        <div class="col-12 col-md-4 d-flex px 0 mb-5">
            <div class="col-2">
                <span class="ti-anchor"></span>
            </div>
            <div class="col-10">
                <h3>Branding Design </h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, earum.   
                </p>
            </div>
        </div>
        <div class="col-12 col-md-4 d-flex px 0 mb-5">
            <div class="col-2">
                <span class="ti-video-camera"></span>
            </div>
            <div class="col-10">
                <h3>Video Marketing</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, earum.</p>
                <span class="ti-video-design"></span>
            </div>
        </div>
        <div class="col-12 col-md-4 d-flex px 0 mb-5">
            <div class="col-2">
                <span class="ti-android"></span>
            </div>
            <div class="col-10">
                <h3>App Design</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, earum.</p>
                <span class="ti-video-design"></span>
            </div>
        </div>    
    </div>
</div>
<!--FOOTER-->
<footer class="container-fluid bg-black py-4">
<div class="container px-0">
  <div class="d-md-flex justify-content-between align-items-center">
    <span>Copyrights© 2019 Design & developped by Themfisher</span>
    <ul class="d-flex flex-wrap list-unstyled mb-0 mt-3 mt-md-0">
      <li><a href="https://www.facebook.com" target="new" class="pl-0 px-md-3"><span class="ti-facebook"></span></a></li>
      <li><a href="https://www.twitter.com"target="new" class="px-3"><span class="ti-twitter"></span></a></li>
      <li><a href="https://www.github.com"target="new" class="px-3"><span class="ti-github"></span></a></li>
      <li><a href="https://www.pinterest.com"target="new" class="px-3"><span class="ti-pinterest"></span></a></li>
      <li><a href="https://www.dribbble.com"target="new" class="px-3"><span class="ti-dribbble"></span></a></li>
    </ul>
  </div>
</footer>


<!--FIN FOOTER-->

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" 
integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" 
integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" 
integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
<!--SCRIPTS PERSONNALISES-->
<script>
// On ajoute un écouteur d'évennement sur les liens ahref du menu secondaire 
$(".text-secondary").on("click touchend", function(event){
  //pour empêcher leur comportement par défaut
  event.preventDefault();
  // ON regarde la valeur de l'attribut data-cat de l'élement menu cliqué
  //On utilise la méthode attr() de jQuery pou lire (getter) la valeur de l'attribut
  // $(this) fait ref à l'objet du DOM ayant déclenché l'évent danc la balise a
  var category = $(this).attr("data-cat");
  console.log("category=>", category);
  //Si la valeur est "all" on affiche toutes les images
  //sinon on masque les images dont l'attribut data-type n'est pas égal à la valeur de l'attribut data-cat bouton
  if(category=="all"){
    $("#mosaique").find("div").css("display", "block");
    }else{
      $("#mosaique").find("div").each(function(){
        // $(this) fait ref à la div enfant de #mosaiqie étant
        //passée en revue par la boucle (each jquery est égale à une boucle for en javascript)
        var imageType = $(this).attr("data-type");
        //Si le type est égal à la category on change la css de la div pour display block
        //sinon on change la css de la div pour display none
        if(imageType==category){
          $(this).css("display", "block");
        }else{
          $(this).css("display", "none"); 
        }
      });
    }
})
</script> 
<!--FIN-SCRIPTS PERSONNALISES-->
</body>
</html>
