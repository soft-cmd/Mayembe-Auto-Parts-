# HTML (index.html)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mayembe Auto Parts | Japanese Car Parts Specialist</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&family=Oswald:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Top Bar -->
    <div class="top-bar">
        <div class="container">
            <div class="top-bar-content">
                <div class="contact-info">call-Mayembe
                    <span><i class="fas fa-phone"></i> +256 754 370 323</span>
                    <span><i class="fas fa-envelope"></i> info@mayembeautoparts.com</span>
                </div>
                <div class="social-icons">
                    <a href="#"><i class="fab fa-facebook-f"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-whatsapp"></i></a>
                </div>
            </div>
        </div>
    </div>

    <!-- Header -->
    <header class="header">
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <a href="index.html">
                        <img src="images/logo.png" alt="Mayembe Auto Parts">
                        <span>Mayembe Auto Parts</span>
                    </a>
                </div>
                <nav class="main-nav">
                    <ul>
                        <li><a href="index.html" class="active">Home</a></li>
                        <li><a href="products.html">Products</a></li>
                        <li><a href="about.html">About Us</a></li>
                        <li><a href="services.html">Services</a></li>
                        <li><a href="blog.html">Blog</a></li>
                        <li><a href="contact.html">Contact</a></li>
                    </ul>
                </nav>
                <div class="header-actions">
                    <a href="#" class="search-btn"><i class="fas fa-search"></i></a>
                    <a href="#" class="cart-btn"><i class="fas fa-shopping-cart"></i><span class="cart-count">0</span></a>
                    <a href="#" class="account-btn"><i class="fas fa-user"></i></a>
                    <div class="mobile-menu-btn">
                        <i class="fas fa-bars"></i>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-slider">
            <div class="slide active" style="background-image: url('images/hero1.jpg');">
                <div class="container">
                    <div class="slide-content">
                        <h1>Premium Japanese Auto Parts</h1>
                        <p>New and used high-quality parts for all Japanese car models</p>
                        <a href="products.html" class="btn btn-primary">Shop Now</a>
                    </div>
                </div>
            </div>
            <div class="slide" style="background-image: url('images/hero2.jpg');">
                <div class="container">
                    <div class="slide-content">
                        <h1>Genuine Used Parts</h1>
                        <p>Affordable, tested parts with warranty</p>
                        <a href="products.html" class="btn btn-primary">Browse Inventory</a>
                    </div>
                </div>
            </div>
            <div class="slide" style="background-image: url('images/hero3.jpg');">
                <div class="container">
                    <div class="slide-content">
                        <h1>Expert Technical Support</h1>
                        <p>Our team is ready to help you find the right parts</p>
                        <a href="contact.html" class="btn btn-primary">Contact Us</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="slider-controls">
            <button class="prev-slide"><i class="fas fa-chevron-left"></i></button>
            <button class="next-slide"><i class="fas fa-chevron-right"></i></button>
        </div>
        <div class="slider-dots"></div>
    </section>

    <!-- Search Box -->
    <section class="search-box">
        <div class="container">
            <form class="search-form">
                <div class="form-group">
                    <select class="form-control">
                        <option value="">All Categories</option>
                        <option value="engine">Engine Parts</option>
                        <option value="transmission">Transmission</option>
                        <option value="electrical">Electrical</option>
                        <option value="suspension">Suspension</option>
                        <option value="exterior">Exterior Parts</option>
                        <option value="interior">Interior Parts</option>
                    </select>
                </div>
                <div class="form-group">
                    <select class="form-control">
                        <option value="">All Makes</option>
                        <option value="toyota">Toyota</option>
                        <option value="honda">Honda</option>
                        <option value="nissan">Nissan</option>
                        <option value="mitsubishi">Mitsubishi</option>
                        <option value="subaru">Subaru</option>
                        <option value="mazda">Mazda</option>
                    </select>
                </div>
                <div class="form-group">
                    <input type="text" class="form-control" placeholder="Search by part name or number...">
                </div>
                <button type="submit" class="btn btn-primary">Search</button>
            </form>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="container">
            <div class="features-grid">
                <div class="feature-item">
                    <div class="feature-icon">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3>Quality Guarantee</h3>
                    <p>All parts tested and come with warranty</p>
                </div>
                <div class="feature-item">
                    <div class="feature-icon">
                        <i class="fas fa-truck"></i>
                    </div>
                    <h3>Fast Shipping</h3>
                    <p>Nationwide delivery within 2-3 days</p>
                </div>
                <div class="feature-item">
                    <div class="feature-icon">
                        <i class="fas fa-headset"></i>
                    </div>
                    <h3>24/7 Support</h3>
                    <p>Expert advice whenever you need it</p>
                </div>
                <div class="feature-item">
                    <div class="feature-icon">
                        <i class="fas fa-hand-holding-usd"></i>
                    </div>
                    <h3>Best Prices</h3>
                    <p>Competitive pricing on all parts</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Popular Categories -->
    <section class="categories">
        <div class="container">
            <div class="section-header">
                <h2>Popular Categories</h2>
                <a href="products.html" class="view-all">View All</a>
            </div>
            <div class="categories-grid">
                <a href="products.html?category=engine" class="category-item">
                    <div class="category-image">
                        <img src="images/category-engine.jpg" alt="Engine Parts">
                    </div>
                    <h3>Engine Parts</h3>
                    <span class="item-count">245 Items</span>
                </a>
                <a href="products.html?category=transmission" class="category-item">
                    <div class="category-image">
                        <img src="images/category-transmission.jpg" alt="Transmission">
                    </div>
                    <h3>Transmission</h3>
                    <span class="item-count">189 Items</span>
                </a>
                <a href="products.html?category=electrical" class="category-item">
                    <div class="category-image">
                        <img src="images/category-electrical.jpg" alt="Electrical">
                    </div>
                    <h3>Electrical</h3>
                    <span class="item-count">312 Items</span>
                </a>
                <a href="products.html?category=suspension" class="category-item">
                    <div class="category-image">
                        <img src="images/category-suspension.jpg" alt="Suspension">
                    </div>
                    <h3>Suspension</h3>
                    <span class="item-count">176 Items</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Popular Products -->
    <section class="products">
        <div class="container">
            <div class="section-header">
                <h2>Featured Products</h2>
                <a href="products.html" class="view-all">View All</a>
            </div>
            <div class="products-grid">
                <!-- Product 1 -->
                <div class="product-item">
                    <div class="product-badge">New</div>
                    <div class="product-image">
                        <img src="images/product1.jpg" alt="Toyota Engine">
                        <div class="product-actions">
                            <button class="quick-view"><i class="fas fa-eye"></i></button>
                            <button class="add-to-wishlist"><i class="far fa-heart"></i></button>
                            <button class="add-to-cart"><i class="fas fa-shopping-cart"></i></button>
                        </div>
                    </div>
                    <div class="product-details">
                        <span class="product-category">Engine Parts</span>
                        <h3 class="product-title">Toyota 2JZ-GTE Engine</h3>
                        <div class="product-price">
                            <span class="current-price">$2,450.00</span>
                            <span class="original-price">$2,899.00</span>
                        </div>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span>(12)</span>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-item">
                    <div class="product-badge">Used</div>
                    <div class="product-image">
                        <img src="images/product2.jpg" alt="Honda Transmission">
                        <div class="product-actions">
                            <button class="quick-view"><i class="fas fa-eye"></i></button>
                            <button class="add-to-wishlist"><i class="far fa-heart"></i></button>
                            <button class="add-to-cart"><i class="fas fa-shopping-cart"></i></button>
                        </div>
                    </div>
                    <div class="product-details">
                        <span class="product-category">Transmission</span>
                        <h3 class="product-title">Honda B-Series Transmission</h3>
                        <div class="product-price">
                            <span class="current-price">$850.00</span>
                        </div>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                            <span>(8)</span>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-item">
                    <div class="product-badge">-15%</div>
                    <div class="product-image">
                        <img src="images/product3.jpg" alt="Nissan Alternator">
                        <div class="product-actions">
                            <button class="quick-view"><i class="fas fa-eye"></i></button>
                            <button class="add-to-wishlist"><i class="far fa-heart"></i></button>
                            <button class="add-to-cart"><i class="fas fa-shopping-cart"></i></button>
                        </div>
                    </div>
                    <div class="product-details">
                        <span class="product-category">Electrical</span>
                        <h3 class="product-title">Nissan 140A Alternator</h3>
                        <div class="product-price">
                            <span class="current-price">$120.00</span>
                            <span class="original-price">$140.00</span>
                        </div>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span>(23)</span>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="product-item">
                    <div class="product-image">
                        <img src="images/product4.jpg" alt="Toyota Suspension">
                        <div class="product-actions">
                            <button class="quick-view"><i class="fas fa-eye"></i></button>
                            <button class="add-to-wishlist"><i class="far fa-heart"></i></button>
                            <button class="add-to-cart"><i class="fas fa-shopping-cart"></i></button>
                        </div>
                    </div>
                    <div class="product-details">
                        <span class="product-category">Suspension</span>
                        <h3 class="product-title">Toyota Hilux Shock Absorbers</h3>
                        <div class="product-price">
                            <span class="current-price">$75.00</span>
                        </div>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span>(17)</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Brands Section -->
    <section class="brands">
        <div class="container">
            <div class="section-header">
                <h2>Our Top Brands</h2>
            </div>
            <div class="brands-slider">
                <div class="brand-item">
                    <img src="images/brand-toyota.png" alt="Toyota">
                </div>
                <div class="brand-item">
                    <img src="images/brand-honda.png" alt="Honda">
                </div>
                <div class="brand-item">
                    <img src="images/brand-nissan.png" alt="Nissan">
                </div>
                <div class="brand-item">
                    <img src="images/brand-mitsubishi.png" alt="Mitsubishi">
                </div>
                <div class="brand-item">
                    <img src="images/brand-subaru.png" alt="Subaru">
                </div>
                <div class="brand-item">
                    <img src="images/brand-mazda.png" alt="Mazda">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about">
        <div class="container">
            <div class="about-content">
                <div class="about-text">
                    <h2>About Mayembe Auto Parts</h2>
                    <p>Since 2005, Mayembe Auto Parts has been the trusted source for high-quality Japanese auto parts in the region. We specialize in both new and used parts for all major Japanese car brands.</p>
                    <p>Our team of experts carefully inspects and tests every part to ensure it meets our strict quality standards before offering it to our customers. We source directly from Japan to provide authentic parts at competitive prices.</p>
                    <div class="about-stats">
                        <div class="stat-item">
                            <span class="stat-number">18+</span>
                            <span class="stat-label">Years Experience</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">10,000+</span>
                            <span class="stat-label">Parts in Stock</span>
                        </div>
                        <div class="stat-item">
                            <span class="stat-number">5,000+</span>
                            <span class="stat-label">Satisfied Customers</span>
                        </div>
                    </div>
                    <a href="about.html" class="btn btn-outline">Learn More</a>
                </div>
                <div class="about-image">
                    <img src="images/about.jpg" alt="About Mayembe Auto Parts">
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials">
        <div class="container">
            <div class="section-header">
                <h2>What Our Customers Say</h2>
            </div>
            <div class="testimonials-slider">
                <div class="testimonial-item">
                    <div class="testimonial-content">
                        <div class="testimonial-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p>"I was skeptical about buying a used transmission online, but Mayembe Auto Parts exceeded my expectations. The part was in excellent condition and arrived faster than promised. Saved me hundreds compared to dealership prices!"</p>
                        <div class="testimonial-author">
                            <img src="images/customer1.jpg" alt="John D.">
                            <div class="author-info">
                                <h4>John D.</h4>
                                <span>Toyota Hilux Owner</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="testimonial-item">
                    <div class="testimonial-content">
                        <div class="testimonial-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p>"The team at Mayembe helped me find the exact alternator I needed for my Nissan Patrol. Their knowledge of Japanese cars is impressive, and the part works perfectly. Will definitely be my first stop for any future needs."</p>
                        <div class="testimonial-author">
                            <img src="images/customer2.jpg" alt="Sarah M.">
                            <div class="author-info">
                                <h4>Sarah M.</h4>
                                <span>Nissan Patrol Owner</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="testimonial-item">
                    <div class="testimonial-content">
                        <div class="testimonial-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                        <p>"As a mechanic, I regularly source parts from Mayembe for my customers. Their inventory is extensive, prices are fair, and the quality is consistently good. Saves me time and keeps my customers happy."</p>
                        <div class="testimonial-author">
                            <img src="images/customer3.jpg" alt="David K.">
                            <div class="author-info">
                                <h4>David K.</h4>
                                <span>Auto Mechanic</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="cta">
        <div class="container">
            <div class="cta-content">
                <h2>Need Help Finding the Right Part?</h2>
                <p>Our experts are ready to assist you with any questions about compatibility, installation, or availability.</p>
                <div class="cta-buttons">
                    <a href="contact.html" class="btn btn-primary">Contact Us</a>
                    <a href="tel:+255123456789" class="btn btn-outline"><i class="fas fa-phone"></i> Call Now</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Section -->
    <section class="blog">
        <div class="container">
            <div class="section-header">
                <h2>Latest From Our Blog</h2>
                <a href="blog.html" class="view-all">View All</a>
            </div>
            <div class="blog-grid">
                <article class="blog-post">
                    <div class="post-image">
                        <img src="images/blog1.jpg" alt="Blog Post">
                        <span class="post-category">Maintenance Tips</span>
                    </div>
                    <div class="post-content">
                        <div class="post-meta">
                            <span><i class="far fa-calendar"></i> June 15, 2023</span>
                            <span><i class="far fa-comment"></i> 8 Comments</span>
                        </div>
                        <h3 class="post-title"><a href="blog-single.html">5 Signs Your Car's Suspension Needs Attention</a></h3>
                        <p class="post-excerpt">Learn the warning signs that indicate your suspension system may need repair or replacement...</p>
                        <a href="blog-single.html" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                    </div>
                </article>
                <article class="blog-post">
                    <div class="post-image">
                        <img src="images/blog2.jpg" alt="Blog Post">
                        <span class="post-category">Buying Guide</span>
                    </div>
                    <div class="post-content">
                        <div class="post-meta">
                            <span><i class="far fa-calendar"></i> May 28, 2023</span>
                            <span><i class="far fa-comment"></i> 14 Comments</span>
                        </div>
                        <h3 class="post-title"><a href="blog-single.html">New vs Used Auto Parts: Making the Right Choice</a></h3>
                        <p class="post-excerpt">Discover when it makes sense to buy new parts versus quality used parts to save money without compromising...</p>
                        <a href="blog-single.html" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                    </div>
                </article>
                <article class="blog-post">
                    <div class="post-image">
                        <img src="images/blog3.jpg" alt="Blog Post">
                        <span class="post-category">Product Spotlight</span>
                    </div>
                    <div class="post-content">
                        <div class="post-meta">
                            <span><i class="far fa-calendar"></i> May 10, 2023</span>
                            <span><i class="far fa-comment"></i> 5 Comments</span>
                        </div>
                        <h3 class="post-title"><a href="blog-single.html">The Reliability of Japanese Engines: What Makes Them Special</a></h3>
                        <p class="post-excerpt">Explore the engineering behind Japanese engines and why they're renowned for their durability and performance...</p>
                        <a href="blog-single.html" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="newsletter">
        <div class="container">
            <div class="newsletter-content">
                <div class="newsletter-text">
                    <h3>Subscribe to Our Newsletter</h3>
                    <p>Get updates on new arrivals, special offers, and automotive tips directly to your inbox.</p>
                </div>
                <form class="newsletter-form">
                    <input type="email" placeholder="Your email address" required>
                    <button type="submit" class="btn btn-primary">Subscribe</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="footer-top">
            <div class="container">
                <div class="footer-grid">
                    <div class="footer-col">
                        <div class="footer-logo">
                            <img src="images/logo-white.png" alt="Mayembe Auto Parts">
                            <span>Mayembe Auto Parts</span>
                        </div>
                        <p class="footer-about">Specializing in high-quality Japanese auto parts since 2005. We provide new and used parts for all major Japanese car brands with a commitment to quality and customer satisfaction.</p>
                        <div class="footer-social">
                            <a href="#"><i class="fab fa-facebook-f"></i></a>
                            <a href="#"><i class="fab fa-instagram"></i></a>
                            <a href="#"><i class="fab fa-twitter"></i></a>
                            <a href="#"><i class="fab fa-youtube"></i></a>
                        </div>
                    </div>
                    <div class="footer-col">
                        <h3 class="footer-title">Quick Links</h3>
                        <ul class="footer-links">
                            <li><a href="index.html">Home</a></li>
                            <li><a href="products.html">Products</a></li>
                            <li><a href="about.html">About Us</a></li>
                            <li><a href="services.html">Services</a></li>
                            <li><a href="blog.html">Blog</a></li>
                            <li><a href="contact.html">Contact</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h3 class="footer-title">Customer Service</h3>
                        <ul class="footer-links">
                            <li><a href="#">My Account</a></li>
                            <li><a href="#">Order Tracking</a></li>
                            <li><a href="#">Wishlist</a></li>
                            <li><a href="#">Shipping Policy</a></li>
                            <li><a href="#">Returns & Refunds</a></li>
                            <li><a href="#">FAQ</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h3 class="footer-title">Contact Info</h3>
                        <ul class="footer-contact">
                            <li><i class="fas fa-map-marker-alt"></i> 123 Auto Parts Street, Dar es Salaam, Tanzania</li>
                            <li><i class="fas fa-phone"></i> +255 123 456 789</li>
                            <li><i class="fas fa-envelope"></i> info@mayembeautoparts.com</li>
                            <li><i class="fas fa-clock"></i> Mon-Sat: 8:00 AM - 6:00 PM</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <div class="container">
                <div class="footer-bottom-content">
                    <p class="copyright">&copy; 2023 Mayembe Auto Parts. All Rights Reserved.</p>
                    <div class="payment-methods">
                        <img src="images/payment-visa.png" alt="Visa">
                        <img src="images/payment-mastercard.png" alt="Mastercard">
                        <img src="images/payment-mpesa.png" alt="M-Pesa">
                        <img src="images/payment-tigopesa.png" alt="Tigo Pesa">
                        <img src="images/payment-airtelmoney.png" alt="Airtel Money">
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- Quick View Modal -->
    <div class="modal quick-view-modal">
        <div class="modal-overlay"></div>
        <div class="modal-content">
            <button class="modal-close"><i class="fas fa-times"></i></button>
            <div class="quick-view-content">
                <!-- Content will be loaded via JavaScript -->
            </div>
        </div>
    </div>

    <!-- Mobile Menu -->
    <div class="mobile-menu">
        <div class="mobile-menu-header">
            <div class="logo">
                <img src="images/logo.png" alt="Mayembe Auto Parts">
            </div>
            <button class="mobile-menu-close"><i class="fas fa-times"></i></button>
        </div>
        <nav class="mobile-nav">
            <ul>
                <li><a href="index.html" class="active">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="blog.html">Blog</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <div class="mobile-menu-footer">
            <div class="mobile-contact">
                <a href="tel:+255123456789"><i class="fas fa-phone"></i> +255 123 456 789</a>
                <a href="mailto:info@mayembeautoparts.com"><i class="fas fa-envelope"></i> info@mayembeautoparts.com</a>
            </div>
            <div class="mobile-social">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-whatsapp"></i></a>
            </div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
```

## CSS (styles.css)

```css
/* Base Styles */
:root {
    --primary-color: #e63946;
    --secondary-color: #1d3557;
    --accent-color: #457b9d;
    --light-color: #f1faee;
    --dark-color: #1a1a1a;
    --gray-color: #6c757d;
    --light-gray: #f8f9fa;
    --white: #ffffff;
    --black: #000000;
    --font-primary: 'Roboto', sans-serif;
    --font-secondary: 'Oswald', sans-serif;
    --transition: all 0.3s ease;
    --box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    --border-radius: 5px;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: var(--font-primary);
    color: var(--dark-color);
    line-height: 1.6;
    background-color: var(--white);
    overflow-x: hidden;
}

a {
    text-decoration: none;
    color: inherit;
    transition: var(--transition);
}

ul {
    list-style: none;
}

img {
    max-width: 100%;
    height: auto;
}

.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 15px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    border-radius: var(--border-radius);
    font-weight: 500;
    text-align: center;
    cursor: pointer;
    transition: var(--transition);
    border: none;
    font-size: 16px;
}

.btn-primary {
    background-color: var(--primary-color);
    color: var(--white);
}

.btn-primary:hover {
    background-color: #c1121f;
    transform: translateY(-3px);
    box-shadow: var(--box-shadow);
}

.btn-outline {
    background-color: transparent;
    border: 2px solid var(--primary-color);
    color: var(--primary-color);
}

.btn-outline:hover {
    background-color: var(--primary-color);
    color: var(--white);
    transform: translateY(-3px);
    box-shadow: var(--box-shadow);
}

.section-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 40px;
}

.section-header h2 {
    font-family: var(--font-secondary);
    font-size: 32px;
    font-weight: 600;
    color: var(--secondary-color);
    position: relative;
    padding-bottom: 10px;
}

.section-header h2::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 60px;
    height: 3px;
    background-color: var(--primary-color);
}

.section-header .view-all {
    color: var(--primary-color);
    font-weight: 500;
    display: flex;
    align-items: center;
}

.section-header .view-all:hover {
    text-decoration: underline;
}

.section-header .view-all i {
    margin-left: 5px;
    font-size: 14px;
}

/* Top Bar */
.top-bar {
    background-color: var(--secondary-color);
    color: var(--white);
    padding: 8px 0;
    font-size: 14px;
}

.top-bar-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.contact-info span {
    margin-right: 20px;
}

.contact-info i {
    margin-right: 5px;
    color: var(--primary-color);
}

.social-icons a {
    display: inline-block;
    width: 25px;
    height: 25px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 50%;
    text-align: center;
    line-height: 25px;
    margin-left: 8px;
    color: var(--white);
}

.social-icons a:hover {
    background-color: var(--primary-color);
}

/* Header */
.header {
    background-color: var(--white);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.header-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
}

.logo a {
    display: flex;
    align-items: center;
    font-family: var(--font-secondary);
    font-size: 24px;
    font-weight: 600;
    color: var(--secondary-color);
}

.logo img {
    height: 40px;
    margin-right: 10px;
}

.main-nav ul {
    display: flex;
}

.main-nav ul li {
    margin: 0 10px;
}

.main-nav ul li a {
    font-weight: 500;
    padding: 5px 0;
    position: relative;
}

.main-nav ul li a::after {
    content: '';
    position: absolute;
    bottom
