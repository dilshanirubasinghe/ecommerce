# ecommerce
ui/ux design for online jewelry shop
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Precious Jewels</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-QFy3l+7Ckl9q9rAjq/TIN7xsP5IjpTjcfb/gjY2/zHXKoq+9zW1y5NkNr2v6Fy3ScjyafWwPiQQq3gVxhU8XzQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    /* Custom CSS for the shine effect */
    body {
      background-color: gray; /* Use any shade of gray you prefer */
    }
    .shine-text {
      background-image: linear-gradient(to right, transparent 0%, rgb(243, 29, 1) 50%, transparent 100%);
      -webkit-background-clip: text;
      background-clip: text;
      color: gainsboro;
    }
    .navbar-nav .nav-link {
      color: darkgoldenrod !important; /* Set navigation link color to gold */
    }
    .navbar-nav .nav-link:hover {
      color: darkgoldenrod !important; /* Set hover color */
    }
    .navbar-brand .shine-text {
      color: darkgoldenrod;
    }
    .shop-now-btn {
      background-color: red;
      color: white;
      border: black;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .shop-now-btn:hover {
      background-color: darkgoldenrod;
    }
    /* Set fixed height for card images */
    .card-img-top {
      height: 250px; /* Adjust as needed */
      object-fit: cover;
    }
    /* Moving text animation */
    .moving-text {
      animation: slide 2s infinite alternate;
      color: black;
      lighting-color: black;
    }
    .display-4 .shine-text {
      color: darkgoldenrod;
    }
    .lead {
      color: gold;
    }
    @keyframes slide {
      0% {
        transform: translateY(-50%);
      }
      100% {
        transform: translateY(50%);
      }
    }
  </style>
</head>
<body>

<header>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#"><span class="shine-text">Precious Jewels</span></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Cart <span class="cart-count">0</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="jumbotron jumbotron-fluid bg-dark text-white text-center">
    <div class="container">
      <h1 class="display-4"><span class="shine-text">Welcome to Precious Jewels</span></h1>
      <p class="lead">Discover unique handmade jewelry crafted with passion and skill.</p>
      <div class="d-flex justify-content-center">
        <form class="input-group w-50 me-3">
          <input type="text" class="form-control" placeholder="Search products">
          <button class="btn btn-outline-light" type="button"><i class="fas fa-search"></i></button>
        </form>
        <a href="#" class="btn btn-outline-light mx-3"><i class="fas fa-mobile-alt"></i> Download App</a>
      </div>
    </div>
  </div>
  <br>
</header>
<br>
<div class="moving-text text-center py-3">
  <h2 class="display-5">Discover Unique Handcrafted Jewelry</h2>
</div>
<br>
<main class="container">
  <div class="row">
    <div class="col-lg-4 col-md-6 mb-4">
      <div class="card">
        <img src="https://cdn.dsmcdn.com/ty988/product/media/images/prod/SPM/PIM/20230821/20/7878d62c-65d2-3d86-918b-5d9699eab9bd/1_org_zoom.jpg" class="card-img-top" alt="Necklaces">
        <div class="card-body">
          <h5 class="card-title">Necklaces</h5>
          <p class="card-text">Discover our collection of handmade necklaces, each a unique work of art.</p>
          <button class="btn btn-danger shop-now-btn">Shop Now</button>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-md-6 mb-4">
      <div class="card">
        <img src="https://assets.vogue.com/photos/65e219ede461eb34e0bf04cf/master/w_2560%2Cc_limit/weddingband_holding_01.jpg" class="card-img-top" alt="Rings">
        <div class="card-body">
          <h5 class="card-title">Rings</h5>
          <p class="card-text">Explore our selection of handmade rings, crafted with attention to detail.</p>
          <button class="btn btn-danger shop-now-btn">Shop Now</button>
        </div>
      </div>
    </div>
    <div class="col-lg-4 col-md-6 mb-4">
      <div class="card">
        <img src="https://cdn.staticans.com/image/tr:e-sharpen-01,h-1440,w-1080,cm-pad_resize/data/ToniQ/16-march-2023/OAW22TIJE63_1.jpg" class="card-img-top" alt="Earrings">
        <div class="card-body">
          <h5 class="card-title">Earrings</h5>
          <p class="card-text">Adorn yourself with our exquisite handmade earrings, each telling a unique story.</p>
          <button class="btn btn-danger shop-now-btn">Shop Now</button>
        </div>
      </div>
    </div>
  </div>
</main>

<footer class="bg-dark text-white text-center py-3">
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <ul class="list-inline mb-0">
          <li class="list-inline-item me-4">
            <a href="#"><i class="fab fa-facebook-f"></i> Facebook</a>
          </li>
          <li class="list-inline-item me-4">
            <a href="#"><i class="fab fa-instagram"></i> Instagram</a>
          </li>
          <li class="list-inline-item me-4">
            <a href="#"><i class="fab fa-tiktok"></i> TikTok</a>
          </li>
          <li class="list-inline-item me-4">
            <a href="mailto:info@preciousjewels.com"><i class="far fa-envelope"></i> Email</a>
          </li>
          <li class="list-inline-item">
            <a href="tel:+118536956"><i class="fas fa-phone"></i> Telephone</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
  <p>&copy; 2024 Precious Jewels. All rights reserved.</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/js/bootstrap.bundle.min.js"></script>
<script>
  // Update cart count
  let cartCount = 0;
  const cartCountSpan = document.querySelector('.cart-count');

  document.querySelectorAll('.shop-now-btn').forEach(btn => {
    btn.addEventListener('click', () => {
      cartCount++;
      cartCountSpan.textContent = cartCount;
    });
  });
</script>

</body>
</html>
