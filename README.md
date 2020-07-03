# E04
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Nature</title>
    <link rel="stylesheet" href="stylesheet.css">
  </head>
  <body>
    <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
</head>
<body>
  <!-- Ketik code Anda dibawah -->
  <header>
  <div class="container">
    <div class="header-left">
      <img class="logo" src="https://image.freepik.com/free-vector/set-natural-logo-branding-modern-design_25819-424.jpg">
    </div>
    <div class="header-right">
      <a href="#" class="login">Log in</a>
    </div>
  </div>
  </header>
  <div class="top-wrapper">
    <div class="container">
      <h1>Love Thyself, Love Nature</h1>
      <h1>Sustainability starts within you</h1>
      <p>Nature is beautifully crafted to serve your inner nature</p>
      <p>We provide to almost everything you need to begin earth-friendly living</p>
      <div class="btn-wrapper">
        <a href="#" class="btn signup">Sign up with Email</a>
        <p>or</p>
        <a href="#" class="btn facebook"><span class="fa fa-facebook"></span>Sign up with Facebook</a>
        <a href="#" class="btn twitter"><span class="fa fa-twitter"></span>Sign up with Twitter</a>
      </div>
    </div>
  </div>
  <div class="product-wrapper">
   <div class="container">
     <div class="heading">
       <h2>Please kindly inform us upon what you need</h2>
     </div>
     <div class="products">
       <div class="product">
         <div class="product-icon">
           <div class="img" style="background-image:url('https://i.pinimg.com/564x/54/12/e9/5412e98041685810dc013fa07d488b1e.jpg');"></div>

           <p><span class="highlight">Accessories</span></p>
         </div>
         <p class="txt-contents">Otherwordly handcrafted from woods and other natural ingridients, the shape of our accessories uniquely mimic flowers, plants, or animals.</p>
       </div>
       <div class="product">
         <div class="product-icon">
           <div class="img" style="background-image:url('https://i.pinimg.com/564x/76/c4/8f/76c48ff658b9077c323dbdc2486c35de.jpg');"></div>

           <p><span class="highlight">Make-Up</span></p>
         </div>
         <p class="txt-contents">less chemichal and obviously vegan can be lifetime guarantee that will atrract your eyes on, our make-up products suitable for all skin type to reflect the beauty of inclusivity</p>
       </div>
       <div class="product">
         <div class="product-icon">
           <div class="img" style="background-image:url('https://i.pinimg.com/564x/a2/7c/6b/a27c6ba2384845220e0e64536cdb99a5.jpg');"></div>

           <p><span class="highlight">Clothing</span></p>
         </div>
         <p class="txt-contents">Our philosophy does not merely about vegan living, instead it also talks about how we appreciate human rights, our clothings are tailored with love, and not by slave labor and child labor, we also comply with sustainable sewage system regulation. </p>
       </div>
        <div class="product">
         <div class="product-icon">
           <div class="img" style="background-image:url('https://i.pinimg.com/564x/8b/aa/94/8baa9485ebca6459846fe088ed021340.jpg');"></div>

           <p><span class="highlight">Small things</span></p>
         </div>
         <p class="txt-contents">Products under this category inlcude washable pads, grocery bags, even bamboo toothbrush, we realize that small things like these can give big contribution towards Mother of the Earth if conducted continuously and massively.</p>
       </div>
     </div>
   </div>
 </div>
 <div class="message-wrapper">
   <div class="container">
     <div class="heading">
       <h2>Are you ready to make small changes for the better world we live in?</h2>
       <h3>Let's make purchase in our website</h3>
     </div>
     <span class="btn message">Start Shopping</span>
   </div>
 </div>
 <footer>
  <div class="container">
    <img src="https://image.freepik.com/free-vector/set-natural-logo-branding-modern-design_25819-424.jpg">
    <p>Nature: Living on earth, loving the earth.</p>
  </div>
</footer
</body>
</html>
  </body>
</html>
html, body,
ul, ol, li,
h1, h2, h3, h4, h5, h6, p, div {
  margin: 0;
  padding: 0;
}

body {
  font-family: "Lucida Grande";
}

li {
  list-style: none;
}

a {
  text-decoration: none;
}

/* Ketik code Anda dibawah */




.top-wrapper {
  padding: 180px 0 100px 0;
  background-image: url(https://i.pinimg.com/564x/d3/69/7e/d3697e78a425125b0037c6ecfc6d58a8.jpg);
  background-size: cover;
  color: black;
  text-align: center;
}
.container {
  width: 1170px;

  margin: 0 auto;
}

.top-wrapper h1 {
  opacity: 0.7;
  font-size: 50px;
  letter-spacing: 5px;
  margin-bottom: 10px;
}

.top-wrapper p {
  opacity: 0.7;
  margin-bottom: 3px;
  font-size: 20px;
}

.btn-wrapper {
  margin: 20px 0;
}

.btn-wrapper p {
  margin: 10px 0;
}

.signup {
  background-color: #3c6382;
}


.facebook {
  background-color:#38ada9;
  margin-right: 10px;
}

.twitter {
  background-color:#079992;
}

.btn {
  padding: 12px 24px;
  color: white;
  display: inline-block;
  opacity: 0.8;
  border-radius: 4px;
}

.btn:hover {
  opacity: 0.5;
}

.fa {
  margin-right: 5px;
}

header {
  height: 65px;
  width: 100%;
  background-color:rgba(34, 49, 52, 0.9);
  position: fixed;
  top: 0;
  z-index: 10;
}

.logo {
  width: 124px;
  margin-top: 20px;
}

.header-left {
  float: left;
}

.header-right {
  float: right;
  background-color:rgba(255, 255, 255, 0.3);
  transition: all 0.5s;
}

.header-right:hover {
  background-color:rgba(255, 255, 255, 0.5);
}

.header-right a {
  line-height: 65px;
  padding: 0 25px;
  color: white;
  display: block;
}
.product-wrapper {
  height: 1200px;
  padding:50px 100px;
  background-color: #f7f7f7;
  text-align: center;
}

.heading {
  padding-top: 60px;
  padding-bottom: 30px;
  color: #5f5d60;
}

.heading h2 {
  font-weight: normal;
}

.product {
  float: left;
  width: 50%;
  font-size: 25px;

}

.product-icon {
  position: relative;
  float: left;
}

.product-icon p {
  position: absolute;
  top: 90px;
  width: 100%;
  color: black;

}

.txt-contents {
  width: 80%;
  display: inline-block;
  margin-top: 20px;
  font-size: 20px;
  color: #b3aeb5;
}

.highlight {
  background-color: #f7d794;
}

.img {
    float: left;
    width:  400px;
    height: 400px;
    background-size: cover;
    padding-right: 50px;
    padding-left: 70px;
    background-position: center;

}

.message-wrapper {
  border-bottom: 1px solid #eee;
  padding-bottom: 80px;
  text-align: center;
  background-color: #f7f1e3;
  font-size: 18px;
}

.message {
  padding: 15px 40px;
  background-color: #f3a683;
  cursor: pointer;
  box-shadow: 0 7px #e77f67;
}

.message:active {
  position: relative;
  top: 7px;
  box-shadow: none;
}

footer img {
  width: 100px;
  padding-bottom: 20px;
  position: sticky;
}

footer p {
  color: #303952;
  font-size: 20px;
  float: right;
  text-align: center;
  padding-right: 730px;
}

footer {
  padding-top: 25px;
  padding-bottom; 18px
  text-align: justify;
}
