# marketing-company-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AquaBrand Marketing - Personalized Water Bottles & Marketing Solutions</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">
                <a href="index.html">
                    <img src="images/logo.png" alt="AquaBrand Marketing Logo">
                </a>
            </div>
            <nav>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#customization">Customize</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="blog.html">Blog</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                <div class="nav-buttons">
                    <a href="#" class="cart-btn" id="cartBtn">
                        <i class="fas fa-shopping-cart"></i>
                        <span class="cart-count">0</span>
                    </a>
                    <a href="#" class="btn login-btn">Login</a>
                    <a href="#" class="btn primary-btn">Get Started</a>
                </div>
                <div class="mobile-menu-toggle">
                    <i class="fas fa-bars"></i>
                </div>
            </nav>
        </div>
    </header>

    <!-- Mobile Menu -->
    <div class="mobile-menu">
        <div class="close-menu">
            <i class="fas fa-times"></i>
        </div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#customization">Customize</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="blog.html">Blog</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <div class="mobile-buttons">
            <a href="#" class="btn login-btn">Login</a>
            <a href="#" class="btn primary-btn">Get Started</a>
        </div>
    </div>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>Elevate Your Brand with Personalized Marketing Solutions</h1>
                <p>From custom water bottles to comprehensive digital campaigns, we help businesses make a lasting impression both online and on the ground.</p>
                <div class="hero-buttons">
                    <a href="#products" class="btn primary-btn">Shop Bottles</a>
                    <a href="#customization" class="btn secondary-btn">Customize Now</a>
                </div>
            </div>
            <div class="hero-image">
                <img src="images/hero-bottles.png" alt="Custom branded water bottles">
            </div>
        </div>
        <div class="hero-brands">
            <div class="container">
                <p>Trusted by leading brands worldwide</p>
                <div class="brand-logos">
                    <img src="images/brand1.png" alt="Brand Logo">
                    <img src="images/brand2.png" alt="Brand Logo">
                    <img src="images/brand3.png" alt="Brand Logo">
                    <img src="images/brand4.png" alt="Brand Logo">
                    <img src="images/brand5.png" alt="Brand Logo">
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <div class="section-header">
                <span class="subtitle">Our Expertise</span>
                <h2>Comprehensive Marketing Solutions</h2>
                <p>We offer a range of services designed to boost your brand visibility and engagement both digitally and physically</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-flask"></i>
                    </div>
                    <h3>Custom Water Bottles</h3>
                    <p>Premium quality personalized water bottles with your branding, perfect for events, promotions, and corporate gifts.</p>
                    <a href="#customization" class="learn-more">Learn More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-bullhorn"></i>
                    </div>
                    <h3>Digital Marketing</h3>
                    <p>Comprehensive digital marketing strategies including SEO, social media, email marketing, and paid advertising.</p>
                    <a href="#" class="learn-more">Learn More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-store"></i>
                    </div>
                    <h3>Ground Marketing</h3>
                    <p>Impactful physical presence through event marketing, guerrilla marketing, and promotional campaigns.</p>
                    <a href="#" class="learn-more">Learn More <i class="fas fa-arrow-right"></i></a>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Analytics & ROI</h3>
                    <p>Data-driven insights and reporting to track campaign performance and maximize your marketing ROI.</p>
                    <a href="#" class="learn-more">Learn More <i class="fas fa-arrow-right"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <div class="container">
            <div class="section-header">
                <span class="subtitle">Our Products</span>
                <h2>Premium Branded Water Bottles</h2>
                <p>Choose from our selection of high-quality bottles ready for your custom branding</p>
            </div>
            <div class="product-filters">
                <button class="filter-btn active" data-filter="all">All Bottles</button>
                <button class="filter-btn" data-filter="glass">Glass</button>
                <button class="filter-btn" data-filter="stainless">Stainless Steel</button>
                <button class="filter-btn" data-filter="plastic">Eco-Plastic</button>
                <button class="filter-btn" data-filter="aluminum">Aluminum</button>
            </div>
            <div class="products-grid">
                <!-- Products will be loaded dynamically via JavaScript -->
                <!-- Example product card structure -->
                <div class="product-card" data-category="glass">
                    <div class="product-badge">Best Seller</div>
                    <div class="product-image">
                        <img src="images/products/glass-bottle-1.jpg" alt="Premium Glass Bottle">
                        <div class="product-actions">
                            <button class="quick-view" data-product-id="1"><i class="fas fa-eye"></i></button>
                            <button class="add-to-cart" data-product-id="1"><i class="fas fa-shopping-cart"></i></button>
                            <button class="add-to-wishlist" data-product-id="1"><i class="far fa-heart"></i></button>
                        </div>
                    </div>
                    <div class="product-info">
                        <h3>Premium Glass Bottle</h3>
                        <div class="product-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span>(42)</span>
                        </div>
                        <div class="product-price">
                            <span class="current-price">$24.99</span>
                            <span class="old-price">$29.99</span>
                        </div>
                        <a href="product-details.html?id=1" class="btn product-btn">View Details</a>
                    </div>
                </div>
                <!-- More product cards will be added dynamically -->
            </div>
            <div class="load-more-container">
                <button id="loadMoreBtn" class="btn secondary-btn">Load More</button>
            </div>
        </div>
    </section>

    <!-- Customization Section -->
    <section id="customization" class="customization">
        <div class="container">
            <div class="section-header">
                <span class="subtitle">Make It Yours</span>
                <h2>Custom Bottle Designer</h2>
                <p>Create the perfect branded water bottles for your business or event</p>
            </div>
            <div class="customization-container">
                <div class="customization-preview">
                    <div id="bottlePreview" class="bottle-preview">
                        <img src="images/bottles/glass-clear.png" id="bottleImage" alt="Bottle Preview">
                        <div id="logoPreview" class="logo-preview"></div>
                        <div id="textPreview" class="text-preview"></div>
                    </div>
                    <div class="preview-controls">
                        <button id="rotateLeft" class="preview-btn"><i class="fas fa-undo"></i></button>
                        <button id="zoomIn" class="preview-btn"><i class="fas fa-search-plus"></i></button>
                        <button id="zoomOut" class="preview-btn"><i class="fas fa-search-minus"></i></button>
                        <button id="rotateRight" class="preview-btn"><i class="fas fa-redo"></i></button>
                    </div>
                </div>
                <div class="customization-options">
                    <form id="customizationForm">
                        <div class="customization-step active" id="step1">
                            <h3>Step 1: Choose Your Bottle</h3>
                            <div class="form-group">
                                <label>Bottle Type</label>
                                <div class="bottle-options">
                                    <div class="bottle-option active" data-bottle-type="glass">
                                        <img src="images/bottles/glass-thumb.png" alt="Glass Bottle">
                                        <span>Glass</span>
                                    </div>
                                    <div class="bottle-option" data-bottle-type="stainless">
                                        <img src="images/bottles/stainless-thumb.png" alt="Stainless Bottle">
                                        <span>Stainless</span>
                                    </div>
                                    <div class="bottle-option" data-bottle-type="plastic">
                                        <img src="images/bottles/plastic-thumb.png" alt="Eco-Plastic Bottle">
                                        <span>Eco-Plastic</span>
                                    </div>
                                    <div class="bottle-option" data-bottle-type="aluminum">
                                        <img src="images/bottles/aluminum-thumb.png" alt="Aluminum Bottle">
                                        <span>Aluminum</span>
                                    </div>
                                </div>
                            </div>
                            <div class="form-group">
                                <label>Bottle Color</label>
                                <div class="color-options">
                                    <div class="color-option active" data-color="clear" style="background-color: #f5f5f5;"></div>
                                    <div class="color-option" data-color="blue" style="background-color: #3498db;"></div>
                                    <div class="color-option" data-color="green" style="background-color: #2ecc71;"></div>
                                    <div class="color-option" data-color="black" style="background-color: #2c3e50;"></div>
                                    <div class="color-option" data-color="red" style="background-color: #e74c3c;"></div>
                                </div>
                            </div>
                            <div class="form-group">
                                <label>Bottle Size</label>
                                <select id="bottleSize" name="bottleSize">
                                    <option value="small">Small (350ml)</option>
                                    <option value="medium" selected>Medium (500ml)</option>
                                    <option value="large">Large (750ml)</option>
                                    <option value="xl">Extra Large (1000ml)</option>
                                </select>
                            </div>
                            <div class="form-action">
                                <button type="button" class="btn primary-btn next-step">Next Step</button>
                            </div>
                        </div>
                        
                        <div class="customization-step" id="step2">
                            <h3>Step 2: Add Your Branding</h3>
                            <div class="form-group">
                                <label>Upload Logo</label>
                                <div class="file-upload">
                                    <input type="file" id="logoUpload" name="logoUpload" accept="image/*">
                                    <label for="logoUpload" class="upload-label">
                                        <i class="fas fa-cloud-upload-alt"></i>
                                        <span>Choose File</span>
                                    </label>
                                    <div id="fileName" class="file-name">No file chosen</div>
                                </div>
                                <div class="help-text">Recommended: PNG or SVG with transparent background</div>
                            </div>
                            <div class="form-group">
                                <label>Logo Position</label>
                                <div class="position-options">
                                    <button type="button" class="position-btn active" data-position="center">Center</button>
                                    <button type="button" class="position-btn" data-position="top">Top</button>
                                    <button type="button" class="position-btn" data-position="bottom">Bottom</button>
                                </div>
                            </div>
                            <div class="form-group">
                                <label>Logo Size</label>
                                <input type="range" id="logoSize" name="logoSize" min="10" max="100" value="50">
                                <div class="range-values">
                                    <span>Small</span>
                                    <span>Large</span>
                                </div>
                            </div>
                            <div class="form-group">
                                <label>Custom Text</label>
                                <input type="text" id="customText" name="customText" placeholder="Add your slogan or website">
                            </div>
                            <div class="form-group">
                                <label>Text Color</label>
                                <div class="color-options">
                                    <div class="color-option active" data-text-color="#000000" style="background-color: #000000;"></div>
                                    <div class="color-option" data-text-color="#ffffff" style="background-color: #ffffff; border: 1px solid #ddd;"></div>
                                    <div class="color-option" data-text-color="#3498db" style="background-color: #3498db;"></div>
                                    <div class="color-option" data-text-color="#e74c3c" style="background-color: #e74c3c;"></div>
                                    <div class="color-option" data-text-color="#2ecc71" style="background-color: #2ecc71;"></div>
                                </div>
                            </div>
                            <div class="form-action">
                                <button type="button" class="btn secondary-btn prev-step">Previous Step</button>
                                <button type="button" class="btn primary-btn next-step">Next Step</button>
                            </div>
                        </div>
                        
                        <div class="customization-step" id="step3">
                            <h3>Step 3: Order Details</h3>
                            <div class="form-group">
                                <label>Quantity</label>
                                <div class="quantity-selector">
                                    <button type="button" id="decreaseQty" class="qty-btn"><i class="fas fa-minus"></i></button>
                                    <input type="number" id="quantity" name="quantity" min="50" value="100">
                                    <button type="button" id="increaseQty" class="qty-btn"><i class="fas fa-plus"></i></button>
                                </div>
                                <div class="help-text">Minimum order: 50 bottles</div>
                            </div>
                            <div class="form-group">
                                <label>Packaging Options</label>
                                <select id="packaging" name="packaging">
                                    <option value="standard">Standard Packaging</option>
                                    <option value="individual">Individual Box (+$1.00/unit)</option>
                                    <option value="premium">Premium Gift Box (+$2.50/unit)</option>
                                </select>
                            </div>
                            <div class="form-group">
                                <label>Production Time</label>
                                <select id="productionTime" name="productionTime">
                                    <option value="standard">Standard (10-14 business days)</option>
                                    <option value="express">Express (7-9 business days, +15%)</option>
                                    <option value="rush">Rush (4-6 business days, +25%)</option>
                                </select>
                            </div>
                            <div class="order-summary">
                                <h4>Order Summary</h4>
                                <div class="summary-row">
                                    <span>Base Price:</span>
                                    <span id="basePrice">$14.99/unit</span>
                                </div>
                                <div class="summary-row">
                                    <span>Quantity:</span>
                                    <span id="summaryQty">100 units</span>
                                </div>
                                <div class="summary-row">
                                    <span>Packaging:</span>
                                    <span id="summaryPackaging">Standard Packaging</span>
                                </div>
                                <div class="summary-row">
                                    <span>Production:</span>
                                    <span id="summaryProduction">Standard (10-14 days)</span>
                                </div>
                                <div class="summary-row">
                                    <span>Setup Fee:</span>
                                    <span id="setupFee">$99.00</span>
                                </div>
                                <div class="summary-row total">
                                    <span>Estimated Total:</span>
                                    <span id="totalPrice">$1,598.00</span>
                                </div>
                            </div>
                            <div class="form-action">
                                <button type="button" class="btn secondary-btn prev-step">Previous Step</button>
                                <button type="button" id="addToCartBtn" class="btn primary-btn">Add to Cart</button>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio">
        <div class="container">
            <div class="section-header">
                <span class="subtitle">Our Work</span>
                <h2>Success Stories</h2>
                <p>See how our custom marketing solutions have helped brands stand out</p>
            </div>
            <div class="portfolio-tabs">
                <button class="tab-btn active" data-tab="bottles">Water Bottles</button>
                <button class="tab-btn" data-tab="digital">Digital Campaigns</button>
                <button class="tab-btn" data-tab="events">Event Marketing</button>
                <button class="tab-btn" data-tab="integrated">Integrated Campaigns</button>
            </div>
            <div class="tab-content active" id="bottlesTab">
                <div class="portfolio-grid">
                    <div class="portfolio-item">
                        <img src="images/portfolio/bottle-case1.jpg" alt="Tech Conference Branding">
                        <div class="portfolio-overlay">
                            <div class="portfolio-info">
                                <h3>Tech Conference Branding</h3>
                                <p>Custom water bottles for a major tech conference with 5,000 attendees</p>
                                <a href="case-study.html?id=1" class="btn secondary-btn">View Case Study</a>
                            </div>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <img src="images/portfolio/bottle-case2.jpg" alt="Fitness Brand Launch">
                        <div class="portfolio-overlay">
                            <div class="portfolio-info">
                                <h3>Fitness Brand Launch</h3>
                                <p>Premium stainless steel bottles for a new fitness brand launch</p>
                                <a href="case-study.html?id=2" class="btn secondary-btn">View Case Study</a>
                            </div>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <img src="images/portfolio/bottle-case3.jpg" alt="Corporate Wellness Program">
                        <div class="portfolio-overlay">
                            <div class="portfolio-info">
                                <h3>Corporate Wellness Program</h3>
                                <p>Custom branded bottles for a Fortune 500 employee wellness initiative</p>
                                <a href="case-study.html?id=3" class="btn secondary-btn">View Case Study</a>
                            </div>
                        </div>
                    </div>
                    <!-- More portfolio items -->
                </div>
            </div>
            <div class="tab-content" id="digitalTab">
                <!-- Digital marketing case studies -->
            </div>
            <div class="tab-content" id="eventsTab">
                <!-- Event marketing case studies -->
            </div>
            <div class="tab-content" id="integratedTab">
                <!-- Integrated campaign case studies -->
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <div class="container">
            <div class="section-header">
                <span class="subtitle">Client Feedback</span>
                <h2>What Our Clients Say</h2>
                <p>Don't just take our word for it - hear from brands that have worked with us</p>
            </div>
            <div class="testimonial-slider">
                <div class="testimonial-track">
                    <div class="testimonial-slide">
                        <div class="testimonial-card">
                            <div class="testimonial-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                            <p class="testimonial-text">"The custom water bottles we ordered for our tech conference were a huge hit! AquaBrand delivered exceptional quality, and the bottles became a talking point among attendees. Their team was professional and guided us through every step of the customization process."</p>
                            <div class="testimonial-author">
                                <img src="images/testimonials/client1.jpg" alt="Sarah Johnson">
                                <div class="author-info">
                                    <h4>Sarah Johnson</h4>
                                    <p>Event Director, TechNow Conference</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- More testimonial slides -->
                </div>
                <div class="slider-controls">
                    <button id="prevTestimonial" class="slider-btn"><i class="fas fa-arrow-left"></i></button>
                    <div class="slider-dots">
                        <span class="dot active"></span>
                        <span class="dot"></span>
                        <span class="dot"></span>
                        <span class="dot"></span>
                    </div>
                    <button id="nextTestimonial" class="slider-btn"><i class="fas fa-arrow-right"></i></button>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog Preview Section -->
    <section class="blog-preview">
        <div class="container">
            <div class="section-header">
                <span class="subtitle">Latest Articles</span>
                <h2>Marketing Insights</h2>
                <p>Expert tips and strategies to enhance your marketing efforts</p>
            </div>
            <div class="blog-preview-grid">
                <div class="blog-card">
                    <div class="blog-image">
                        <a href="blog-detail.html?id=1">
                            <img src="images/blog/blog1.jpg" alt="Blog post image">
                        </a>
                        <div class="blog-category">Strategy</div>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> Feb 18, 2025</span>
                            <span><i class="far fa-user"></i> Alex Morgan</span>
                        </div>
                        <h3><a href="blog-detail.html?id=1">7 Ways Custom Water Bottles Can Boost Your Brand Recognition</a></h3>
                        <p>Discover how branded water bottles can enhance your visibility and create lasting impressions with your audience.</p>
                        <a href="blog-detail.html?id=1" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
                <div class="blog-card">
                    <div class="blog-image">
                        <a href="blog-detail.html?id=2">
                            <img src="images/blog/blog2.jpg" alt="Blog post image">
                        </a>
                        <div class="blog-category">Digital</div>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> Feb 12, 2025</span>
                            <span><i class="far fa-user"></i> Maria Chen</span>
                        </div>
                        <h3><a href="blog-detail.html?id=2">Integrating Physical Products with Digital Marketing: A Complete Guide</a></h3>
                        <p>Learn how to create powerful marketing campaigns that bridge the gap between physical products and digital channels.</p>
                        <a href="blog-detail.html?id=2" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
                <div class="blog-card">
                    <div class="blog-image">
                        <a href="blog-detail.html?id=3">
                            <img src="images/blog/blog3.jpg" alt="Blog post image">
                        </a>
                        <div class="blog-category">Case Study</div>
                    </div>
                    <div class="blog-content">
                        <div class="blog-meta">
                            <span><i class="far fa-calendar"></i> Feb 5, 2025</span>
                            <span><i class="far fa-user"></i> James Wilson</span>
                        </div>
                        <h3><a href="blog-detail.html?id=3">How a Startup Increased Event Engagement by 87% with Branded Merchandise</a></h3>
                        <p>A detailed case study on how strategic use of branded water bottles transformed a startup's event marketing strategy.</p>
                        <a href="blog-detail.html?id=3" class="read-more">Read More <i class="fas fa-arrow-right"></i></a>
                    </div>
                </div>
            </div>
            <div class="view-all-container">
                <a href="blog.html" class="btn secondary-btn">View All Articles</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header">
                <span class="subtitle">Get In Touch</span>
                <h2>Let's Discuss Your Project</h2>
                <p>Have questions or ready to start your custom marketing campaign? Contact us today.</p>
            </div>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="info-card">
                        <div class="info-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="info-content">
                            <h4>Office Location</h4>
                            <p>123 Marketing Street, Suite 400<br>New York, NY 10001, USA</p>
                        </div>
                    </div>
                    <div class="info-card">
                        <div class="info-icon">
                            <i class="fas fa-phone-alt"></i>
                        </div>
                        <div class="info-content">
                            <h4>Call Us</h4>
                            <p>Toll-free: (800) 123-4567<br>Direct: (212) 555-6789</p>
                        </div>
                    </div>
                    <div class="info-card">
                        <div class="info-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="info-content">
                            <h4>Email Us</h4>
                            <p>info@aquabrand.com<br>sales@aquabrand.com</p>
                        </div>
                    </div>
                    <div class="info-card">
                        <div class="info-icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <div class="info-content">
                            <h4>Office Hours</h4>
                            <p>Monday - Friday
