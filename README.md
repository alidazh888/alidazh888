<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Home</title>


   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">


   <link rel="stylesheet" href="css/style.css">

</head>
<body>
   


<header class="header">

   <nav class="navbar nav-1">
      <section class="flex">
         <a href="home.html" class="logo"><i class="fas fa-house"></i>RealEstate</a>

      </section>
   </nav>

   <nav class="navbar nav-2">
      <section class="flex">
         <div id="menu-btn" class="fas fa-bars"></div>

         <div class="menu">
            <ul>
               <li><a href="C:\Users\Алида\OneDrive\Рабочий стол\desgin\images\services.html">Services</a>
               </li>
               
               <li><a href="listings.html">Featured</a>
                  
               </li>
               <li><a href="C:\Users\Алида\OneDrive\Рабочий стол\desgin\agents.html">Agents</a>
                  
               </li>
               <li><a href="#">Help<i class="fas fa-angle-down"></i></a>
                  <ul>
                     <li><a href="about.html">about us</a></i></li>
                     <li><a href="contact.html">contact us</a></i></li>
                  </ul>
               </li>
            </ul>
         </div>

         <ul>
            <li><a href="#">saved <i class="far fa-heart"></i></a></li>
            <li><a href="#">account <i class="fas fa-angle-down"></i></a>
               <ul>
                  <li><a href="login.html">login</a></li>
                  <li><a href="register.html">register</a></li>
               </ul>
            </li>
         </ul>
      </section>
   </nav>

</header>


<div class="home">

   <section class="center">

      <form action="search.html" method="post">
         <h3>find your perfect home</h3>
         <div class="box">
            <p>enter location <span>*</span></p>
            <input type="text" name="location" required maxlength="50" placeholder="enter ciyt name" class="input">
         </div>
         <div class="flex">
            <div class="box">
               <p>property type <span>*</span></p>
               <select name="type" class="input" required>
                  <option value="flat">flat</option>
                  <option value="house">house</option>
               </select>
            </div>
            <div class="box">
               <p>how many BHK <span>*</span></p>
               <select name="bhk" class="input" required>
                  <option value="1">1 BHK</option>
                  <option value="2">2 BHK</option>
                  <option value="3">3 BHK</option>
                  <option value="4">4 BHK</option>
                  <option value="5">5 BHK</option>
               </select>
            </div>
            <div class="box">
               <p>maximum budget <span>*</span></p>
               <select name="minimum" class="input" required>
                  <option value="5000000">5 lac</option>
                  <option value="1000000">10 lac</option>
                  <option value="2000000">20 lac</option>
                  <option value="3000000">30 lac</option>
                  <option value="4000000">40 lac</option>
                  <option value="4000000">40 lac</option>
                  <option value="5000000">50 lac</option>
                  
               </select>
            </div>
            <div class="box">
               <p>maximum budget <span>*</span></p>
               <select name="maximum" class="input" required>
                  <option value="5000000">5 lac</option>
                  <option value="1000000">10 lac</option>
                  <option value="2000000">20 lac</option>
                  <option value="3000000">30 lac</option>
                  <option value="4000000">40 lac</option>
                  <option value="4000000">40 lac</option>
                  <option value="5000000">50 lac</option>
                  <option value="6000000">60 lac</option>
                 
               </select>
            </div>
         </div>
         <input type="submit" value="search property" name="search" class="btn">
      </form>

   </section>

</div>


<section class="services">

   <h1 class="heading">our services</h1>

   <div class="box-container">

      <div class="box">
         <img src="images/icon-1.png" alt="">
         <h3>buy house</h3>
        
      </div>

      <div class="box">
         <img src="images/icon-2.png" alt="">
         <h3>rent house</h3>
       
      </div>

      <div class="box">
         <img src="images/icon-3.png" alt="">
         <h3>sell house</h3>
       
      </div>

      <div class="box">
         <img src="images/icon-4.png" alt="">
         <h3>flats and buildings</h3>

      </div>

      <div class="box">
         <img src="images/icon-5.png" alt="">
         <h3>shops and malls</h3>
    
      </div>

      <div class="box">
         <img src="images/icon-6.png" alt="">
         <h3>24/7 service</h3>
      
      </div>

   </div>

</section>



<section class="listings">

   <h1 class="heading">latest listings</h1>

   <div class="box-container">

      <div class="box">
         <div class="admin">
            <h3>A</h3>
            <div>
               <p>Alida Zhassulan</p>
               <span>10-11-2022</span>
            </div>
         </div>
         <div class="thumb">
            <p class="total-images"><i class="far fa-image"></i><span>4</span></p>
            <p class="type"><span>house</span><span>sale</span></p>
            <form action="" method="post" class="save">
               <button type="submit" name="save" class="far fa-heart"></button>
            </form>
            <img src="images/house-img-1.webp" alt="">
         </div>
         <h3 class="name">modern flats and appartments</h3>
         <p class="location"><i class="fas fa-map-marker-alt"></i><span>Astana, Kazakhstan</span></p>
         <div class="flex">
            <p><i class="fas fa-bed"></i><span>3</span></p>
            <p><i class="fas fa-bath"></i><span>2</span></p>
            <p><i class="fas fa-maximize"></i><span>750sqft</span></p>
         </div>
         <a href="view_property.html" class="btn">view property</a>
      </div>

      <div class="box">
         <div class="admin">
            <h3>E</h3>
            <div>
               <p>Elnura Yeraty</p>
               <span>11-11-2022</span>
            </div>
         </div>
         <div class="thumb">
            <p class="total-images"><i class="far fa-image"></i><span>4</span></p>
            <p class="type"><span>flat</span><span>sale</span></p>
            <form action="" method="post" class="save">
               <button type="submit" name="save" class="far fa-heart"></button>
            </form>
            <img src="images/house-img-2.webp" alt="">
         </div>
         <h3 class="name">modern flats and appartments</h3>
         <p class="location"><i class="fas fa-map-marker-alt"></i><span>Astana, Kazakhstan</span></p>
         <div class="flex">
            <p><i class="fas fa-bed"></i><span>2</span></p>
            <p><i class="fas fa-bath"></i><span>2</span></p>
            <p><i class="fas fa-maximize"></i><span>840sqft</span></p>
         </div>
         <a href="C:\Users\Алида\OneDrive\Рабочий стол\desgin\view_property.html2.html" class="btn">view property</a>
      </div>

      <div class="box">
         <div class="admin">
            <h3>N</h3>
            <div>
               <p>Nursulu Mukhambetova</p>
               <span>13-11-2022</span>
            </div>
         </div>
         <div class="thumb">
            <p class="total-images"><i class="far fa-image"></i><span>4</span></p>
            <p class="type"><span>flat</span><span>sale</span></p>
            <form action="" method="post" class="save">
               <button type="submit" name="save" class="far fa-heart"></button>
            </form>
            <img src="images/house-img-3.jpg" alt="">
         </div>
         <h3 class="name">modern flats and appartments</h3>
         <p class="location"><i class="fas fa-map-marker-alt"></i><span>Astana, Kazakhstan</span></p>
         <div class="flex">
            <p><i class="fas fa-bed"></i><span>3</span></p>
            <p><i class="fas fa-bath"></i><span>1</span></p>
            <p><i class="fas fa-maximize"></i><span>740sqft</span></p>
         </div>
         <a href="view_property.html3.html" class="btn">view property</a>
      </div>

   </div>

   <div style="margin-top: 2rem; text-align:center;">
      <a href="listings.html" class="inline-btn">view all</a>
   </div>

</section>


<footer class="footer">

   <section class="flex">

      <div class="box">
         <a href="tel:+7747567890"><i class="fas fa-phone"></i><span>+774756789</span></a>
         <a href="tel:+7707223333"><i class="fas fa-phone"></i><span>+7707223333</span></a>
         <a href="mailto:astana.apartments@gmail.com"><i class="fas fa-envelope"></i><span>astana.apartments@gmail.com</span></a>
         <a href="#"><i class="fas fa-map-marker-alt"></i><span>Astana, Kazakhstan</span></a>
      </div>

      <div class="box">
         <a href="home.html"><span>home</span></a>
         <a href="about.html"><span>about</span></a>
         <a href="contact.html"><span>contact</span></a>
         <a href="listings.html"><span>all listings</span></a>
         <a href="#"><span>saved properties</span></a>
      </div>

      <div class="box">
         <a href="#"><span>facebook</span><i class="fab fa-facebook-f"></i></a>
         <a href="#"><span>twitter</span><i class="fab fa-twitter"></i></a>
         <a href="#"><span>linkedin</span><i class="fab fa-linkedin"></i></a>
         <a href="#"><span>instagram</span><i class="fab fa-instagram"></i></a>

      </div>

   </section>

</footer>

<script src="js/script.js"></script>

</body>
</html>
