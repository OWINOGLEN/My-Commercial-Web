<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Annex Online Kilishop - Premium Shoes Store</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Montserrat:wght@800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <script src="myscript.js"></script>
</head>
<body>
    <!-- Top Bar -->
    <div class="top-bar">
        <div class="container">
            <div class="top-bar-content">
                <span><i class="fas fa-phone"></i> +254 723 396 147</span>
                <span><i class="fas fa-map-marker-alt"></i> Nairobi, Kenya</span>
                <span><i class="fas fa-truck"></i> Free Delivery in Nairobi</span>
            </div>
        </div>
    </div>

    <!-- Navigation -->
    <nav class="navbar">
        <div class="container">
            <div class="nav-container">
                <!-- Logo -->
                <div class="logo">
                    <h1><i class="fas fa-shoe-prints"></i> ANNEX<span>Kilishop</span></h1>
                    <p class="tagline">Online Premium Footwear</p>
                </div>

                <!-- Navigation Links -->
                <ul class="nav-links">
                    <li><a href="#home" class="active">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#categories">Categories</a></li>
                    <li><a href="#deals">Hot Deals</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>

                <!-- Cart & User -->
                <div class="nav-icons">
                    <a href="#" class="icon-link"><i class="fas fa-search"></i></a>
                    <a href="#" class="icon-link"><i class="fas fa-user"></i></a>
                    <a href="#" class="icon-link cart">
                        <i class="fas fa-shopping-cart" id="cartIcon"></i>
                        <span class="cart-count">0</span>
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <button class="menu-toggle" id="menuToggle">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <span class="hero-subtitle">PREMIUM FOOTWEAR COLLECTION</span>
                    <h2 class="hero-title">PICK THE PERFECT <span class="highlight">SHOES</span></h2>
                    <p class="hero-description">Discover our exclusive collection of stylish and comfortable shoes for every occasion. Quality meets fashion at unbeatable prices.</p>
                    
                    <div class="hero-offer">
                        <div class="discount-badge">
                            <span>UP TO</span>
                            <strong>30% OFF</strong>
                        </div>
                        <p class="offer-text">Limited time offer on selected items</p>
                    </div>
                    
                    <div class="hero-buttons">
                        <a href="#products" class="btn btn-primary">
                            <i class="fas fa-shopping-bag"></i> SHOP NOW
                        </a>
                        <a href="#deals" class="btn btn-secondary">
                            <i class="fas fa-tag"></i> VIEW DISCOUNTS
                        </a>
                    </div>
                    
                    <div class="hero-stats">
                        <div class="stat">
                            <strong>2,500+</strong>
                            <span>Happy Customers</span>
                        </div>
                        <div class="stat">
                            <strong>500+</strong>
                            <span>Shoe Styles</span>
                        </div>
                        <div class="stat">
                            <strong>24/7</strong>
                            <span>Support</span>
                        </div>
                    </div>
                </div>
                
                <div class="hero-image">
                    <div class="image-container">
                        <img src="https://images.unsplash.com/photo-1549298916-b41d501d3772?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Premium Shoes">
                        <div class="floating-tag">BEST SELLER</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Categories Section -->
    <section class="categories" id="categories">
        <div class="container">
            <div class="section-header">
                <h2>Shop By Category</h2>
                <p>Find the perfect shoes for your style</p>
            </div>
            
            <div class="categories-grid">
                <div class="category-card">
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1560769629-975ec94e6a86?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Sports Shoes">
                    </div>
                    <div class="category-content">
                        <h3>Sports Shoes</h3>
                        <p>Performance & Comfort</p>
                        <a href="#" class="category-link">Shop Now <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
                
                <div class="category-card">
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Formal Shoes">
                    </div>
                    <div class="category-content">
                        <h3>Formal Shoes</h3>
                        <p>Office & Business</p>
                        <a href="#" class="category-link">Shop Now <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
                
                <div class="category-card">
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1543163521-1bf539c55dd2?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Casual Shoes">
                    </div>
                    <div class="category-content">
                        <h3>Casual Shoes</h3>
                        <p>Everyday Comfort</p>
                        <a href="#" class="category-link">Shop Now <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
                
                <div class="category-card">
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1531315630201-bb15abeb1653?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Sneakers">
                    </div>
                    <div class="category-content">
                        <h3>Sneakers</h3>
                        <p>Street Style</p>
                        <a href="#" class="category-link">Shop Now <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Products -->
    <section class="products" id="products">
        <div class="container">
            <div class="section-header">
                <h2>Featured Products</h2>
                <p>Best sellers this week</p>
            </div>
            
            <div class="products-grid">
                <!-- Product 1 -->
                <div class="product-card">
                    <div class="product-image">
                        <img src="https://images.unsplash.com/photo-1606107557195-0e29a4b5b4aa?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Nike Air Max">
                        <div class="product-badges">
                            <span class="badge hot">HOT</span>
                            <span class="badge discount">-30%</span>
                        </div>
                        <button class="quick-view"><i class="fas fa-eye"></i></button>
                    </div>
                    <div class="product-content">
                        <span class="product-category">Sports Shoes</span>
                        <h3 class="product-title">Nike Air Max 270</h3>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span>(45 reviews)</span>
                        </div>
                        <div class="product-price">
                            <span class="current-price">Ksh. 4,500</span>
                            <span class="original-price">Ksh. 6,500</span>
                        </div>
                        <button class="btn btn-cart"><i class="fas fa-cart-plus"></i> Add to Cart</button>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card">
                    <div class="product-image">
                        <img src="https://images.unsplash.com/photo-1562183241-b937e95585b6?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Leather Formal">
                        <div class="product-badges">
                            <span class="badge new">NEW</span>
                        </div>
                        <button class="quick-view"><i class="fas fa-eye"></i></button>
                    </div>
                    <div class="product-content">
                        <span class="product-category">Formal Shoes</span>
                        <h3 class="product-title">Premium Leather Oxford</h3>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span>(32 reviews)</span>
                        </div>
                        <div class="product-price">
                            <span class="current-price">Ksh. 3,800</span>
                        </div>
                        <button class="btn btn-cart"><i class="fas fa-cart-plus"></i> Add to Cart</button>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card">
                    <div class="product-image">
                        <img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Adidas Sneakers">
                        <div class="product-badges">
                            <span class="badge discount">-25%</span>
                        </div>
                        <button class="quick-view"><i class="fas fa-eye"></i></button>
                    </div>
                    <div class="product-content">
                        <span class="product-category">Sneakers</span>
                        <h3 class="product-title">Adidas Ultra Boost</h3>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span>(67 reviews)</span>
                        </div>
                        <div class="product-price">
                            <span class="current-price">Ksh. 5,200</span>
                            <span class="original-price">Ksh. 7,000</span>
                        </div>
                        <button class="btn btn-cart"><i class="fas fa-cart-plus"></i> Add to Cart</button>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-card">
                    <div class="product-image">
                        <img src="https://images.unsplash.com/photo-1551107696-a4b0c5a0d9a2?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Casual Loafers">
                        <div class="product-badges">
                            <span class="badge best">BEST</span>
                        </div>
                        <button class="quick-view"><i class="fas fa-eye"></i></button>
                    </div>
                    <div class="product-content">
                        <span class="product-category">Casual Shoes</span>
                        <h3 class="product-title">Comfort Loafers</h3>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span>(89 reviews)</span>
                        </div>
                        <div class="product-price">
                            <span class="current-price">Ksh. 2,500</span>
                        </div>
                        <button class="btn btn-cart"><i class="fas fa-cart-plus"></i> Add to Cart</button>
                    </div>
                </div>
            </div>
            
            <div class="text-center">
                <a href="#" class="btn btn-view-all">View All Products <i class="fas fa-arrow-right"></i></a>
            </div>
        </div>
    </section>

    <!-- Discount Banner -->
    <section class="discount-banner" id="deals">
        <div class="container">
            <div class="banner-content">
                <div class="banner-text">
                    <h2>MEGA DISCOUNT SALE</h2>
                    <h3>UP TO <span>30% OFF</span> ON ALL SHOES</h3>
                    <p>Limited time offer. Shop now before stock runs out!</p>
                    <div class="countdown">
                        <div class="countdown-item">
                            <span id="days">00</span>
                            <small>Days</small>
                        </div>
                        <div class="countdown-item">
                            <span id="hours">00</span>
                            <small>Hours</small>
                        </div>
                        <div class="countdown-item">
                            <span id="minutes">00</span>
                            <small>Minutes</small>
                        </div>
                        <div class="countdown-item">
                            <span id="seconds">00</span>
                            <small>Seconds</small>
                        </div>
                    </div>
                    <a href="#products" class="btn btn-primary btn-large">
                        <i class="fas fa-shopping-cart"></i> BUY NOW
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials">
        <div class="container">
            <div class="section-header">
                <h2>Customer Reviews</h2>
                <p>What our customers say about us</p>
            </div>
            
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <i class="fas fa-quote-left"></i>
                        <p>"The quality of shoes is amazing! Got my Nike Air Max delivered in 2 days. Highly recommend Annex Kilishop!"</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="Images/G3.jpg" alt="Customer">
                        <div>
                            <h4>Glen Annex</h4>
                            <span>South Africa</span>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <i class="fas fa-quote-left"></i>
                        <p>"Best prices in town! Their customer service is excellent. Will definitely shop here again."</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Customer">
                        <div>
                            <h4>Ruth Shallom</h4>
                            <span>Canada</span>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <i class="fas fa-quote-left"></i>
                        <p>"Authentic products and fast delivery. The 30% discount was real! Saved a lot on my purchase."</p>
                    </div>
                    <div class="testimonial-author">
                        <img src="Images/zeddy zadock.jpg" alt="Customer">
                        <div>
                            <h4>Zeddy Zaddock</h4>
                            <span>United Kingdom</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer" id="contact">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <div class="logo">
                        <h2><i class="fas fa-shoe-prints"></i> ANNEX<span>Kilishop</span></h2>
                    </div>
                    <p>Your trusted online destination for premium footwear in Kenya. Quality, style, and comfort guaranteed.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#products">Products</a></li>
                        <li><a href="#categories">Categories</a></li>
                        <li><a href="#deals">Hot Deals</a></li>
                        <li><a href="#about">About Us</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Customer Service</h3>
                    <ul>
                        <li><a href="#">Contact Us</a></li>
                        <li><a href="#">Shipping Policy</a></li>
                        <li><a href="#">Return & Exchange</a></li>
                        <li><a href="#">FAQs</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Contact Info</h3>
                    <ul class="contact-info">
                        <li><i class="fas fa-phone"></i> +254 723 396 147</li>
                        <li><i class="fas fa-envelope"></i> info@annexkilishop.co.ke</li>
                        <li><i class="fas fa-map-marker-alt"></i> Nairobi, Kenya</li>
                        <li><i class="fas fa-clock"></i> Mon-Sat: 8AM - 8PM</li>
                    </ul>
                    <div class="payment-methods">
                        <i class="fab fa-cc-mastercard"></i>
                        <i class="fab fa-cc-visa"></i>
                        <i class="fab fa-cc-paypal"></i>
                        <i class="fas fa-money-bill-wave"></i>
                    </div>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2024 Annex Online Kilishop. All Rights Reserved.</p>
                <p>Designed with <i class="fas fa-heart"></i> for shoe lovers in Kenya</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Float Button -->
    <a href="https://wa.me/254723396147" class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script src="script.js"></script>
</body>
</html>


/* Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary: #ff6b6b;
    --secondary: #4ecdc4;
    --dark: #2d3436;
    --light: #f9f9f9;
    --gray: #636e72;
    --shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    --transition: all 0.3s ease;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: var(--dark);
    background-color: var(--light);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Buttons */
.btn {
    display: inline-block;
    padding: 12px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: 600;
    border: none;
    cursor: pointer;
    transition: var(--transition);
    font-size: 16px;
}

.btn-primary {
    background: linear-gradient(45deg, var(--primary), #ff8e8e);
    color: white;
}

.btn-primary:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(255, 107, 107, 0.3);
}

.btn-secondary {
    background: white;
    color: var(--primary);
    border: 2px solid var(--primary);
}

.btn-secondary:hover {
    background: var(--primary);
    color: white;
}

/* Top Bar */
.top-bar {
    background: var(--dark);
    color: white;
    padding: 10px 0;
    font-size: 14px;
}

.top-bar-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.top-bar-content span {
    display: flex;
    align-items: center;
    gap: 8px;
}

/* Navigation */
.navbar {
    background: white;
    box-shadow: var(--shadow);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
}

.logo h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 28px;
    color: var(--primary);
    display: flex;
    align-items: center;
    gap: 10px;
}

.logo span {
    color: var(--dark);
}

.tagline {
    font-size: 12px;
    color: var(--gray);
    margin-top: -5px;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 30px;
}

.nav-links a {
    text-decoration: none;
    color: var(--dark);
    font-weight: 500;
    transition: var(--transition);
}

.nav-links a:hover,
.nav-links a.active {
    color: var(--primary);
}

.nav-icons {
    display: flex;
    gap: 20px;
    align-items: center;
}

.icon-link {
    color: var(--dark);
    font-size: 18px;
    position: relative;
    transition: var(--transition);
}

.icon-link:hover {
    color: var(--primary);
}

.cart-count {
    position: absolute;
    top: -8px;
    right: -8px;
    background: var(--primary);
    color: white;
    font-size: 12px;
    width: 18px;
    height: 18px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.menu-toggle {
    display: none;
    background: none;
    border: none;
    font-size: 24px;
    color: var(--dark);
    cursor: pointer;
}

/* Hero Section */
.hero {
    padding: 80px 0;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
}

.hero-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    align-items: center;
}

.hero-subtitle {
    color: var(--primary);
    font-weight: 600;
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 15px;
    display: block;
}

.hero-title {
    font-family: 'Montserrat', sans-serif;
    font-size: 48px;
    line-height: 1.2;
    margin-bottom: 20px;
}

.highlight {
    color: var(--primary);
}

.hero-description {
    color: var(--gray);
    font-size: 18px;
    margin-bottom: 30px;
}

.hero-offer {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 30px;
}

.discount-badge {
    background: linear-gradient(45deg, var(--primary), #ff8e8e);
    color: white;
    padding: 15px 25px;
    border-radius: 10px;
    text-align: center;
    min-width: 120px;
}

.discount-badge span {
    display: block;
    font-size: 14px;
}

.discount-badge strong {
    font-size: 28px;
    display: block;
}

.offer-text {
    color: var(--gray);
    font-size: 16px;
}

.hero-buttons {
    display: flex;
    gap: 20px;
    margin-bottom: 40px;
}

.hero-stats {
    display: flex;
    gap: 40px;
}

.stat {
    text-align: center;
}

.stat strong {
    display: block;
    font-size: 32px;
    color: var(--primary);
    font-weight: 700;
}

.stat span {
    font-size: 14px;
    color: var(--gray);
}

.hero-image {
    position: relative;
}

.image-container {
    position: relative;
    border-radius: 20px;
    overflow: hidden;
    box-shadow: var(--shadow);
}

.image-container img {
    width: 100%;
    height: auto;
    display: block;
}

.floating-tag {
    position: absolute;
    top: 20px;
    right: 20px;
    background: var(--secondary);
    color: white;
    padding: 8px 15px;
    border-radius: 20px;
    font-weight: 600;
    animation: float 3s ease-in-out infinite;
}

@keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
}

/* Categories */
.categories {
    padding: 80px 0;
    background: white;
}

.section-header {
    text-align: center;
    margin-bottom: 50px;
}

.section-header h2 {
    font-size: 36px;
    margin-bottom: 10px;
    color: var(--dark);
}

.section-header p {
    color: var(--gray);
    font-size: 18px;
}

.categories-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 30px;
}

.category-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: var(--shadow);
    transition: var(--transition);
}

.category-card:hover {
    transform: translateY(-10px);
}

.category-image {
    height: 200px;
    overflow: hidden;
}

.category-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
}

.category-card:hover .category-image img {
    transform: scale(1.1);
}

.category-content {
    padding: 20px;
}

.category-content h3 {
    margin-bottom: 5px;
    font-size: 20px;
}

.category-content p {
    color: var(--gray);
    margin-bottom: 15px;
    font-size: 14px;
}

.category-link {
    color: var(--primary);
    text-decoration: none;
    font-weight: 600;
    display: flex;
    align-items: center;
    gap: 5px;
}

.category-link:hover {
    gap: 10px;
}

/* Products */
.products {
    padding: 80px 0;
    background: #f8f9fa;
}

.products-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 30px;
    margin-bottom: 40px;
}

.product-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: var(--shadow);
    transition: var(--transition);
}

.product-card:hover {
    transform: translateY(-10px);
}

.product-image {
    position: relative;
    height: 250px;
    overflow: hidden;
}

.product-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.product-badges {
    position: absolute;
    top: 15px;
    left: 15px;
    display: flex;
    gap: 10px;
}

.badge {
    padding: 5px 10px;
    border-radius: 5px;
    font-size: 12px;
    font-weight: 600;
    color: white;
}

.badge.hot {
    background: var(--primary);
}

.badge.discount {
    background: var(--secondary);
}

.badge.new {
    background: #3498db;
}

.badge.best {
    background: #f39c12;
}

.quick-view {
    position: absolute;
    bottom: 15px;
    right: 15px;
    background: white;
    border: none;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    opacity: 0;
    transform: translateY(20px);
    transition: var(--transition);
    color: var(--dark);
}

.product-card:hover .quick-view {
    opacity: 1;
    transform: translateY(0);
}

.product-content {
    padding: 20px;
}

.product-category {
    color: var(--gray);
    font-size: 14px;
    display: block;
    margin-bottom: 5px;
}

.product-title {
    font-size: 18px;
    margin-bottom: 10px;
    color: var(--dark);
}

.product-rating {
    display: flex;
    align-items: center;
    gap: 5px;
    margin-bottom: 15px;
    color: #f1c40f;
}

.product-rating span {
    color: var(--gray);
    font-size: 14px;
    margin-left: 5px;
}

.product-price {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 15px;
}

.current-price {
    font-size: 20px;
    font-weight: 700;
    color: var(--primary);
}

.original-price {
    font-size: 16px;
    color: var(--gray);
    text-decoration: line-through;
}

.btn-cart {
    width: 100%;
    background: var(--dark);
    color: white;
}

.btn-cart:hover {
    background: var(--primary);
}

.text-center {
    text-align: center;
}

.btn-view-all {
    background: transparent;
    color: var(--primary);
    border: 2px solid var(--primary);
    padding: 12px 40px;
}

.btn-view-all:hover {
    background: var(--primary);
    color: white;
}

/* Discount Banner */
.discount-banner {
    padding: 100px 0;
    background: linear-gradient(rgba(45, 52, 54, 0.9), rgba(45, 52, 54, 0.9)), url('https://images.unsplash.com/photo-1441986300917-64674bd600d8?ixlib=rb-4.0.3&auto=format&fit=crop&w=1500&q=80');
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
}

.banner-content h2 {
    font-size: 36px;
    margin-bottom: 10px;
    color: var(--secondary);
}

.banner-content h3 {
    font-size: 48px;
    margin-bottom: 20px;
}

.banner-content h3 span {
    color: var(--primary);
}

.banner-content p {
    font-size: 18px;
    margin-bottom: 40px;
    opacity: 0.9;
}

.countdown {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-bottom: 40px;
}

.countdown-item {
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    border-radius: 10px;
    min-width: 100px;
}

.countdown-item span {
    font-size: 40px;
    font-weight: 700;
    display: block;
    color: var(--primary);
}

.countdown-item small {
    font-size: 14px;
    opacity: 0.8;
}

.btn-large {
    padding: 15px 50px;
    font-size: 18px;
}

/* Testimonials */
.testimonials {
    padding: 80px 0;
    background: white;
}

.testimonials-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
}

.testimonial-card {
    background: #f8f9fa;
    border-radius: 15px;
    padding: 30px;
    transition: var(--transition);
}

.testimonial-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow);
}

.testimonial-content i {
    font-size: 24px;
    color: var(--primary);
    margin-bottom: 20px;
}

.testimonial-content p {
    font-style: italic;
    color: var(--gray);
    margin-bottom: 20px;
}

.testimonial-author {
    display: flex;
    align-items: center;
    gap: 15px;
}

.testimonial-author img {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    object-fit: cover;
}

.testimonial-author h4 {
    font-size: 18px;
    margin-bottom: 5px;
}

.testimonial-author span {
    color: var(--gray);
    font-size: 14px;
}

/* Footer */
.footer {
    background: var(--dark);
    color: white;
    padding: 60px 0 20px;
}

.footer-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 40px;
    margin-bottom: 40px;
}


const express = require('express');
const app = express();

app.use(express.static(__dirname));

app.listen(8080, () => {
    console.log('Server running on http://localhost:8080');
});

//Toggle cart dropdown
document.getElementById("CartIcon").addEventListener("click", function(e){
    const dropdown = document.getElementById("cart-dropdown");
})


{
  "name": "shoe-shop",
  "version": "1.0.0",
  "main": "myscript.js",
  "scripts": {
    "start": "node myscript.js"
  },
  "dependencies": {
    "express": "^4.18.2"
  }
}
