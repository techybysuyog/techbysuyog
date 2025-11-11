<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gaming Store - Amazon Style</title>

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: url('https://img.freepik.com/free-vector/luxury-wave-gradient-background-dark-modern-design_343694-3089.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #222;
    }
    
    /* Header / Navbar */
    header {
      background: rgba(19, 25, 33, 0.95);
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 20px;
    }

    .logo {
      font-size: 1.4rem;
      font-weight: 700;
      color: #febd69;
      text-decoration: none;
    }

    .search-bar {
      display: flex;
      flex: 1;
      max-width: 600px;
      margin: 0 20px;
    }

    .search-bar input {
      width: 100%;
      padding: 8px 12px;
      border: none;
      border-radius: 4px 0 0 4px;
      outline: none;
      font-size: 0.95rem;
    }

    .search-bar button {
      background: #0ee1a5;
      border: none;
      padding: 8px 16px;
      border-radius: 0 4px 4px 0;
      cursor: pointer;
      font-weight: 600;
    }

    .language-select select {
      padding: 6px 10px;
      border-radius: 6px;
      border: none;
      background: #fff;
      color: #333;
      font-weight: 600;
    }

    /* Section heading */
    h2 {
      text-align: center;
      font-size: 1.9rem;
      margin: 40px 0 20px;
      font-weight: 600;
      color: #b1f10f;
    }

    /* Centered scroll container */
    .scroll-container {
      display: flex;
      justify-content: center; /* 🔥 Centers the product row */
      flex-wrap: wrap; /* allows wrapping if screen small */
      gap: 18px;
      padding: 0 20px;
    }

    .product-card {
      flex: 0 0 220px;
      background: rgba(255, 255, 255, 0.9);
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
      text-align: center;
      padding: 14px;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .product-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    .product-card img {
      width: 100%;
      height: 160px;
      object-fit: contain;
      border-radius: 8px;
    }

    .product-title {
      font-size: 0.95rem;
      font-weight: 600;
      margin: 10px 0 4px;
      color: #333;
    }

    .product-price {
      color: #e53935;
      font-weight: 700;
      font-size: 1rem;
    }

    .product-discount {
      font-size: 0.85rem;
      color: #388e3c;
    }

    .buy-btn {
      display: inline-block;
      margin-top: 8px;
      padding: 7px 14px;
      background: #007bff;
      color: #fff;
      border-radius: 6px;
      text-decoration: none;
      font-size: 0.85rem;
      transition: background 0.3s;
    }

    .buy-btn:hover {
      background: #0056b3;
    }

    footer {
      text-align: center;
      background: rgba(19,25,33,0.95);
      color: #fff;
      padding: 15px 0;
      margin-top: 50px;
    }

    ::-webkit-scrollbar {
      height: 8px;
    }

    ::-webkit-scrollbar-thumb {
      background: #ccc;
      border-radius: 4px;
    }

    ::-webkit-scrollbar-thumb:hover {
      background: #aaa;
    }

    @media (max-width: 600px) {
      .product-card {
        flex: 0 0 160px;
      }
      .product-card img {
        height: 120px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <a href="#" class="logo">Techbysuyog</a>

    <div class="search-bar">
      <input type="text" placeholder="Search for products, brands and more...">
      <button>Search</button>
    </div>

    <div class="language-select">
      <select>
        <option>English</option>
        <option>हिंदी</option>
        <option>मराठी</option>
      </select>
    </div>
  </header>

  <!-- All Products -->
  <section>
    <h2>All Products</h2>
    <div class="scroll-container">
      <div class="product-card">
        <img src="https://github.com/techybysuyog/TechbySuyog.com/blob/main/Screenshot%202025-10-02%20211742.png?raw=true">
        <div class="product-title">HP Smartchoice Victus Gaming Laptop</div>
       </ul>
      <p class="text-xl font-semibold text-gray-500 line-through">₹ 1,00,594</p>
      <p class="text-2xl font-bold text-[#00ff88] mb-4">₹ 81,990 (After 18% OFF)</p>
      <a href="https://amzn.to/3J8Icm2" target="_blank" class="buy-btn block w-full text-center py-3 text-lg">
        Buy Now on Amazon
      </a>
    </div>
    
      <div class="product-card">
        <img src="https://github.com/techybysuyog/TechbySuyog.com/blob/main/projectora%20a.jpg?raw=true">
        <div class="product-title">WZATCO Yuva Go Smart Projector</div>
           </ul>

    <p class="text-xl font-semibold text-gray-500 line-through">₹ 21,990</p>
    <p class="text-2xl font-bold text-[#00ff88] mb-4">₹ 4,999 (After 77% OFF)</p>

    <a href="https://amzn.to/4oonlKi" target="_blank"
       class="buy-btn block w-full text-center py-3 text-lg">
       Buy Now on Amazon
    </a>
  </div>
      <div class="product-card">
        <img src="https://m.media-amazon.com/images/I/61Qe0euJJZL._SL1500_.jpg">
        <div class="product-title">Logitech G102 RGB Mouse</div>
        <div class="product-price">₹1,499</div>
        <div class="product-discount">25% Off</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
    </div>
  </section>

  <!-- Fresh Products -->
  <section>
    <h2>Fresh Products</h2>
    <div class="scroll-container">
      <div class="product-card">
        <img src="https://rukminim2.flixcart.com/image/480/640/xif0q/computer/q/t/d/fa566nc-hn083w-gaming-laptop-asus-original-imah2qjgyhmnz3v8.jpeg?q=90">
        <div class="product-title">ASUS TUF Gaming F15 144Hz Laptop</div>
        <div class="product-price">₹89,999</div>
        <div class="product-discount">10% Off</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
      <div class="product-card">
        <img src="https://m.media-amazon.com/images/I/71L26Qve3jL.jpg">
        <div class="product-title">Redgear Cloak RGB Headphones</div>
        <div class="product-price">₹1,899</div>
        <div class="product-discount">10% Off</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
      <div class="product-card">
        <img src="https://cdns3.thecosmicbyte.com/wp-content/uploads/Corona_RGB_1.jpg">
        <div class="product-title">Cosmic Byte Gaming Keyboard</div>
        <div class="product-price">₹2,499</div>
        <div class="product-discount">15% Off</div>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
    </div>
  </section>

  <!-- History -->
  <section>
    <h2>Your Browsing History</h2>
    <div class="scroll-container">
      <div class="product-card">
        <img src="https://m.media-amazon.com/images/I/51iEja086gL._AC_UF1000,1000_QL80_.jpg">
        <div class="product-title">WINZELLA 3-in-1 Charging Cable</div>
        <div class="product-price">₹499</div>
        <div class="product-discount">30% Off</div>
        <a href="#" class="buy-btn">Buy Again</a>
      </div>
      <div class="product-card">
        <img src="https://cdn.shopify.com/s/files/1/0356/9850/7909/files/Zeb-Transformer-banner1.jpg?v=1627643716">
        <div class="product-title">Zebronics Zeb-Transformer Keyboard + Mouse Combo</div>
        <div class="product-price">₹1,299</div>
        <div class="product-discount">20% Off</div>
        <a href="#" class="buy-btn">Buy Again</a>
      </div>
    </div>
  </section>



  <footer>
    © 2025 GameStore | Designed ❤️ by Suyog Deore
  </footer>

</body>
</html>
