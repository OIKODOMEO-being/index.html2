<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OBASITECH – HOME OF QUALITY PHONES AND ACCESSORIES</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="preloader">
        <div class="spinner"></div>
    </div>

    <header id="header">
        <div class="logo">
            <i class="fa-solid fa-mobile-screen-button"></i> OBASITECH
        </div>
        <nav>
            <ul id="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#accessories">Accessories</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="header-actions">
            <button id="theme-toggle"><i class="fa-solid fa-moon"></i></button>
            <div class="hamburger" id="hamburger">
                <i class="fa-solid fa-bars"></i>
            </div>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content animate-on-scroll">
            <h1>Welcome to OBASITECH</h1>
            <p>HOME OF QUALITY PHONES AND ACCESSORIES</p>
            <div class="hero-buttons">
                <a href="#products" class="btn primary">Shop Now</a>
                <a href="#contact" class="btn secondary">Contact Us</a>
            </div>
        </div>
    </section>

    <section id="search-section" class="container">
        <div class="search-bar animate-on-scroll">
            <i class="fa-solid fa-magnifying-glass"></i>
            <input type="text" id="search-input" placeholder="Search phones, gadgets, and accessories...">
        </div>
    </section>

    <section id="products" class="container">
        <h2 class="section-title animate-on-scroll">Featured Products</h2>
        <div class="filter-buttons animate-on-scroll">
            <button class="filter-btn active" data-filter="all">All</button>
            <button class="filter-btn" data-filter="phones">Phones</button>
            <button class="filter-btn" data-filter="gadgets">Gadgets</button>
            <button class="filter-btn" data-filter="accessories">Accessories</button>
        </div>
        
        <div class="product-grid" id="product-grid">
            <div class="card product-card animate-on-scroll" data-category="phones">
                <img src="https://images.unsplash.com/photo-1605236453806-6ff36851218e?auto=format&fit=crop&w=400&q=80" alt="iPhone Series">
                <h3>iPhone 15 Pro</h3>
                <p>Latest Apple smartphone with premium camera.</p>
                <div class="price">$999</div>
                <button class="btn primary">Buy Now</button>
            </div>
            <div class="card product-card animate-on-scroll" data-category="phones">
                <img src="https://images.unsplash.com/photo-1610945415295-d9bbf067e59c?auto=format&fit=crop&w=400&q=80" alt="Samsung Galaxy">
                <h3>Samsung Galaxy S24</h3>
                <p>Premium Android device with AI features.</p>
                <div class="price">$899</div>
                <button class="btn primary">Buy Now</button>
            </div>
            <div class="card product-card animate-on-scroll" data-category="gadgets">
                <img src="https://images.unsplash.com/photo-1546868871-7041f2a55e12?auto=format&fit=crop&w=400&q=80" alt="Smart Watch">
                <h3>Ultra Smart Watch</h3>
                <p>Fitness and productivity wearable.</p>
                <div class="price">$199</div>
                <button class="btn primary">Buy Now</button>
            </div>
            <div class="card product-card animate-on-scroll" data-category="accessories">
                <img src="https://images.unsplash.com/photo-1590658268037-6bf12165a8df?auto=format&fit=crop&w=400&q=80" alt="Earbuds">
                <h3>Pro Bluetooth Earbuds</h3>
                <p>Wireless audio with noise cancellation.</p>
                <div class="price">$149</div>
                <button class="btn primary">Buy Now</button>
            </div>
        </div>
    </section>

    <section id="services" class="container bg-light">
        <h2 class="section-title animate-on-scroll">Our Services</h2>
        <div class="grid-3">
            <div class="card service-card animate-on-scroll">
                <i class="fa-solid fa-mobile-retro"></i>
                <h3>Phone Sales</h3>
                <p>We offer the latest and genuine smartphones.</p>
                <a href="#" class="btn-text">Learn More</a>
            </div>
            <div class="card service-card animate-on-scroll">
                <i class="fa-solid fa-screwdriver-wrench"></i>
                <h3>Device Repairs</h3>
                <p>Expert screen replacements and hardware fixes.</p>
                <a href="#" class="btn-text">Learn More</a>
            </div>
            <div class="card service-card animate-on-scroll">
                <i class="fa-solid fa-laptop-code"></i>
                <h3>Software Setup</h3>
                <p>OS installations, updates, and configuration.</p>
                <a href="#" class="btn-text">Learn More</a>
            </div>
        </div>
    </section>

    <section id="stats" class="stats-section animate-on-scroll">
        <div class="stat-box">
            <h2 class="counter" data-target="5000">0</h2>
            <p>Products Sold</p>
        </div>
        <div class="stat-box">
            <h2 class="counter" data-target="3500">0</h2>
            <p>Happy Customers</p>
        </div>
        <div class="stat-box">
            <h2 class="counter" data-target="1200">0</h2>
            <p>Repairs Completed</p>
        </div>
        <div class="stat-box">
            <h2 class="counter" data-target="10">0</h2>
            <p>Years Experience</p>
        </div>
    </section>

    <section id="testimonials" class="container">
        <h2 class="section-title animate-on-scroll">What Our Clients Say</h2>
        <div class="testimonial-slider animate-on-scroll">
            <div class="slide active">
                <div class="stars">★★★★★</div>
                <p>"OBASITECH provided me with an original iPhone at an amazing price."</p>
                <h4>- Sarah M.</h4>
            </div>
            <div class="slide">
                <div class="stars">★★★★★</div>
                <p>"Excellent repair service and fast delivery. My screen looks brand new!"</p>
                <h4>- John D.</h4>
            </div>
            <div class="slide">
                <div class="stars">★★★★★</div>
                <p>"Best gadget store I have ever purchased from. Highly recommended."</p>
                <h4>- David O.</h4>
            </div>
        </div>
    </section>

    <section id="about-contact" class="container">
        <div class="grid-2">
            <div id="about" class="about-info animate-on-scroll">
                <h2>About Us</h2>
                <p>OBASITECH is a trusted technology company dedicated to providing quality smartphones, gadgets, and accessories. We pride ourselves on delivering genuine products, professional services, and exceptional customer satisfaction.</p>
                <div class="contact-details mt-4">
                    <p><i class="fa-solid fa-phone"></i> +233 123 456 789</p>
                    <p><i class="fa-solid fa-envelope"></i> info@obasitech.com</p>
                    <p><i class="fa-solid fa-location-dot"></i> Accra, Greater Accra Region, Ghana</p>
                </div>
            </div>
            <div id="contact" class="card form-card animate-on-scroll">
                <h2>Send a Message</h2>
                <form>
                    <input type="text" placeholder="Full Name" required>
                    <input type="email" placeholder="Email Address" required>
                    <input type="text" placeholder="Subject" required>
                    <textarea rows="4" placeholder="Message" required></textarea>
                    <button type="submit" class="btn primary w-100">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-content container">
            <div class="footer-logo">
                <h3>OBASITECH</h3>
                <p>HOME OF QUALITY PHONES AND ACCESSORIES</p>
            </div>
            <div class="social-links">
                <a href="#"><i class="fa-brands fa-facebook"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
                <a href="#"><i class="fa-brands fa-whatsapp"></i></a>
                <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
            </div>
        </div>
        <div class="copyright">
            &copy; 2026 OBASITECH. All Rights Reserved.
        </div>
    </footer>

    <button id="back-to-top"><i class="fa-solid fa-arrow-up"></i></button>

    <script src="script.js"></script>
</body>
</html>
