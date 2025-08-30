# ELEVANCE
Welcome 

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elevance Career Institute</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #1a237e;
            --secondary: #d4af37;
            --accent: #0d47a1;
            --light: #f8f9fa;
            --dark: #212121;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
       
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
       
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
       
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
       
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
            color: white;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: var(--shadow);
        }
       
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
       
        .logo {
            display: flex;
            align-items: center;
        }
       
        .logo h1 {
            font-size: 28px;
            font-weight: 700;
            margin-left: 10px;
            letter-spacing: 1px;
        }
       
        .logo-icon {
            font-size: 32px;
            color: var(--secondary);
        }
       
        nav ul {
            display: flex;
            list-style: none;
        }
       
        nav ul li {
            margin-left: 25px;
        }
       
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
            padding: 5px 10px;
            border-radius: 4px;
        }
       
        nav ul li a:hover {
            color: var(--secondary);
        }
       
        /* Hero Section */
        .hero {
            background: url('https://images.unsplash.com/photo-1522881193457-37ae97c905bf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80') no-repeat center center/cover;
            height: 600px;
            display: flex;
            align-items: center;
            position: relative;
            color: white;
        }
       
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
        }
       
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            padding: 40px;
            background: rgba(26, 35, 126, 0.8);
            border-radius: 10px;
            margin-left: 50px;
        }
       
        .hero-content h2 {
            font-size: 48px;
            margin-bottom: 20px;
            color: var(--secondary);
        }
       
        .hero-content p {
            font-size: 20px;
            margin-bottom: 30px;
        }
       
        .btn {
            display: inline-block;
            background: var(--secondary);
            color: var(--dark);
            padding: 12px 30px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            font-weight: 600;
            cursor: pointer;
            text-decoration: none;
            transition: all 0.3s;
        }
       
        .btn:hover {
            background: #c19b2e;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
       
        /* Sections */
        section {
            padding: 80px 0;
        }
       
        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }
       
        .section-title h2 {
            font-size: 36px;
            color: var(--primary);
            position: relative;
            display: inline-block;
            padding-bottom: 15px;
        }
       
        .section-title h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--secondary);
        }
       
        /* About Section */
        .about-content {
            display: flex;
            align-items: center;
            gap: 40px;
        }
       
        .about-text {
            width: 100%;
        }
       
        /* Courses Section */
        .courses {
            background: var(--light);
        }
       
        .course-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
       
        .course-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: transform 0.3s;
        }
       
        .course-card:hover {
            transform: translateY(-10px);
        }
       
        .course-image {
            height: 200px;
            overflow: hidden;
        }
       
        .course-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
       
        .course-card:hover .course-image img {
            transform: scale(1.1);
        }
       
        .course-content {
            padding: 20px;
        }
       
        .course-content h3 {
            font-size: 22px;
            color: var(--primary);
            margin-bottom: 15px;
        }
       
        .course-content p {
            margin-bottom: 20px;
        }
       
        /* Features Section */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
       
        .feature-card {
            text-align: center;
            padding: 30px;
            background: white;
            border-radius: 10px;
            box-shadow: var(--shadow);
            transition: transform 0.3s;
        }
       
        .feature-card:hover {
            transform: translateY(-5px);
        }
       
        .feature-icon {
            font-size: 50px;
            color: var(--secondary);
            margin-bottom: 20px;
        }
       
        .feature-card h3 {
            font-size: 22px;
            color: var(--primary);
            margin-bottom: 15px;
        }
       
        /* QR Payment Section */
        .payment {
            background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
            color: white;
        }
       
        .payment-content {
            display: flex;
            align-items: center;
            gap: 40px;
        }
       
        .payment-text {
            flex: 1;
        }
       
        .payment-qr {
            flex: 1;
            text-align: center;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: var(--shadow);
        }
       
        .payment-qr img {
            max-width: 100%;
            height: auto;
            margin-bottom: 15px;
        }
       
        /* Contact Section */
        .contact-content {
            display: flex;
            gap: 40px;
        }
       
        .contact-info {
            flex: 1;
        }
       
        .contact-form {
            flex: 1;
        }
       
        .info-item {
            display: flex;
            align-items: center;
            margin-bottom: 25px;
        }
       
        .info-icon {
            width: 50px;
            height: 50px;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            margin-right: 15px;
        }
       
        .form-group {
            margin-bottom: 20px;
        }
       
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 500;
        }
       
        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
       
        textarea.form-control {
            min-height: 120px;
            resize: vertical;
        }
       
        /* Login Modal */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: 2000;
            align-items: center;
            justify-content: center;
        }
       
        .modal-content {
            background: white;
            width: 100%;
            max-width: 500px;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            position: relative;
        }
       
        .close-modal {
            position: absolute;
            top: 15px;
            right: 15px;
            font-size: 24px;
            cursor: pointer;
            color: #999;
        }
       
        .close-modal:hover {
            color: var(--dark);
        }
       
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 60px 0 30px;
        }
       
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
       
        .footer-logo h2 {
            font-size: 28px;
            color: var(--secondary);
            margin-bottom: 20px;
        }
       
        .footer-links h3, .footer-newsletter h3 {
            font-size: 20px;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
       
        .footer-links h3::after, .footer-newsletter h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 40px;
            height: 3px;
            background: var(--secondary);
        }
       
        .footer-links ul {
            list-style: none;
        }
       
        .footer-links ul li {
            margin-bottom: 10px;
        }
       
        .footer-links ul li a {
            color: #ccc;
            text-decoration: none;
            transition: color 0.3s;
        }
       
        .footer-links ul li a:hover {
            color: var(--secondary);
        }
       
        .footer-newsletter form {
            display: flex;
            margin-bottom: 20px;
        }
       
        .footer-newsletter input {
            flex: 1;
            padding: 12px 15px;
            border: none;
            border-radius: 5px 0 0 5px;
        }
       
        .footer-newsletter button {
            background: var(--secondary);
            color: var(--dark);
            border: none;
            padding: 0 20px;
            border-radius: 0 5px 5px 0;
            font-weight: 600;
            cursor: pointer;
        }
       
        .social-icons {
            display: flex;
            gap: 15px;
        }
       
        .social-icons a {
            width: 40px;
            height: 40px;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: all 0.3s;
        }
       
        .social-icons a:hover {
            background: var(--secondary);
            color: var(--dark);
        }
       
        .footer-bottom {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
       
        /* Responsive Styles */
        @media (max-width: 992px) {
            .about-content, .payment-content, .contact-content {
                flex-direction: column;
            }
           
            .hero-content {
                margin-left: 0;
                text-align: center;
            }
           
            .hero-content h2 {
                font-size: 36px;
            }
        }
       
        @media (max-width: 768px) {
            nav ul {
                display: none;
            }
           
            .header-content {
                flex-direction: column;
                text-align: center;
            }
           
            .logo {
                margin-bottom: 15px;
            }
           
            .hero {
                height: 500px;
            }
           
            .hero-content {
                padding: 20px;
            }
           
            .hero-content h2 {
                font-size: 28px;
            }
           
            .hero-content p {
                font-size: 16px;
            }
           
            .section-title h2 {
                font-size: 28px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <i class="fas fa-graduation-cap logo-icon"></i>
                    <h1>Elevance Career Institute</h1>
                </div>
                <nav>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#courses">Courses</a></li>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#payment">Payment</a></li>
                        <li><a href="#contact">Contact</a></li>
                        <li><a href="#" onclick="openLoginModal()">Student Login</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h2>Elevate Your Learning With Elevance</h2>
                <p>Premier coaching for Class 10-12, NEET, JEE, and exams with exceptional results and expert faculty.</p>
                <a href="#courses" class="btn">Explore Courses</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="section-title">
                <h2>About Us</h2>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <h3>Transforming Education Since 2014</h3>
                    <p>Elevance Career Institute is a premier coaching institute dedicated to providing exceptional education for students preparing for Class 10-12 board exams, NEET, JEE, and NDA entrance tests.</p>
                    <p>Founded by Deepak Chaudhary, our institute has a proven track record of producing top rankers in various competitive exams. We believe in nurturing talent through personalized attention and innovative teaching methodologies.</p>
                    <p>Our state-of-the-art infrastructure, experienced faculty, and comprehensive study materials ensure that our students are well-prepared to excel in their academic pursuits and achieve their career goals.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Courses Section -->
    <section id="courses" class="courses">
        <div class="container">
            <div class="section-title">
                <h2>Our Courses</h2>
            </div>
            <div class="course-grid">
                <div class="course-card">
                    <div class="course-image">
                       <img src="https://images.unsplash.com/photo-1571260899304-425eee4c7efc?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="NEET">
                    </div>
                    <div class="course-content">
                        <h3>Class 10-12 (Science)</h3>
                        <p>Comprehensive coaching for CBSE and ICSE boards with focus on concept clarity and application.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                <div class="course-card">
                    <div class="course-image">
                        <img src="https://images.unsplash.com/photo-1532094349884-543bc11b234d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="JEE">
                    </div>
                    <div class="course-content">
                        <h3>JEE Preparation</h3>
                        <p>Focused coaching for engineering aspirants with regular tests and personalized doubt sessions.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
                <div class="course-card">
                    <div class="course-image">
                     <img src="https://images.unsplash.com/photo-1532094349884-543bc11b234d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="JEE">
                    </div>
                    <div class="course-content">
                        <h3>NEET Preparation</h3>
                        <p>Rigorous training program for medical entrance exams with expert faculty and comprehensive study material.</p>
                        <a href="#" class="btn">Learn More</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <div class="container">
            <div class="section-title">
                <h2>Why Choose Us</h2>
            </div>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-chalkboard-teacher"></i>
                    </div>
                    <h3>Expert Faculty</h3>
                    <p>Our faculty comprises IIT/NIT alumni and subject matter experts with years of teaching experience.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-book-open"></i>
                    </div>
                    <h3>Study Material</h3>
                    <p>Comprehensive and updated study material designed by experts to cover all aspects of the syllabus.</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-clipboard-list"></i>
                    </div>
                    <h3>Regular Tests</h3>
                    <p>Weekly tests and practice sessions to track progress and identify areas for improvement.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- QR Payment Section -->
    <section id="payment" class="payment">
        <div class="container">
            <div class="section-title">
                <h2>Fee Payment</h2>
            </div>
            <div class="payment-content">
                <div class="payment-text">
                    <h3>Easy & Secure Payment</h3>
                    <p>Pay your fees securely using our QR code payment system. Simply scan the QR code using your UPI app and complete the payment in seconds.</p>
                    <p>After successful payment, please share the transaction details with our accounts department for confirmation and receipt generation.</p>
                    <p>For any payment-related queries, please contact our support team at +91 9917155535 or email us at elevancecarrerinstitute@gmail.com</p>
                </div>
                <div class="payment-qr">
                    <h3>Scan to Pay</h3>
                    <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=upi://pay?pa=elevancecarrerinstitute@ybl&pn=Elevance%20Career%20Institute&am=&cu=INR" alt="QR Code for Payment">
                    <p>Use any UPI app to scan and pay</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us</h2>
            </div>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div>
                            <h4>Address</h4>
                            <p>2d, Mall Rd, opposite police control room, D Block, Yamunapuram, Bulandshahr, Uttar Pradesh 203001</p>
                        </div>
                    </div>
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div>
                            <h4>Phone</h4>
                            <p>+91 9917155535</p>
                        </div>
                    </div>
                    <div class="info-item">
                        <div class="info-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div>
                            <h4>Email</h4>
                            <p>elevancecarrerinstitute@gmail.com</p>
                        </div>
                    </div>
                    <div class="map-container">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3509.4279810228654!2d77.83054639356668!3d28.406340186857662!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390ca3223e4f5fc1%3A0x52434d350d24e1c2!2sELEVANCE%20CAREER%20INSTITUTE!5e0!3m2!1sen!2sin!4v1756402351458!5m2!1sen!2sin" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                    </div>
                </div>
                <div class="contact-form">
                    <h3>Send Message</h3>
                    <form id="messageForm">
                        <div class="form-group">
                            <label for="name">Full Name</label>
                            <input type="text" id="name" class="form-control" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" class="form-control" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Your Message</label>
                            <textarea id="message" class="form-control" placeholder="Type your message here..." required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">
                    <h2>Elevance Career Institute</h2>
                    <p>Excellence in education since 2014. Transforming lives through quality teaching and personalized guidance.</p>
                    <p>Founded by: <strong>Deepak Chaudhary</strong></p>
                </div>
                <div class="footer-links">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#courses">Courses</a></li>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#payment">Payment</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h3>Courses</h3>
                    <ul>
                        <li><a href="#">Class 10-12 Science</a></li>
                        <li><a href="#">JEE Preparation</a></li>
                        <li><a href="#">NEET Preparation</a></li>
                        <li><a href="#">Crash Courses</a></li>
                    </ul>
                </div>
                <div class="footer-newsletter">
                    <h3>Newsletter</h3>
                    <p>Subscribe to our newsletter for updates on new courses and events.</p>
                    <form>
                        <input type="email" placeholder="Your Email Address">
                        <button type="submit"><i class="fas fa-paper-plane"></i></button>
                    </form>
                    <div class="social-icons">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2014 Elevance Career Institute. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Login Modal -->
    <div id="loginModal" class="modal">
        <div class="modal-content">
            <span class="close-modal" onclick="closeLoginModal()">&times;</span>
            <h2>Student Login Portal</h2>
            <form id="loginForm">
                <div class="form-group">
                    <label for="studentName">Full Name</label>
                    <input type="text" id="studentName" class="form-control" placeholder="Enter your full name" required>
                </div>
                <div class="form-group">
                    <label for="fatherName">Father's Name</label>
                    <input type="text" id="fatherName" class="form-control" placeholder="Enter your father's name" required>
                </div>
                <div class="form-group">
                    <label for="contactNo">Contact Number</label>
                    <input type="tel" id="contactNo" class="form-control" placeholder="Enter your contact number" required>
                </div>
                <div class="form-group">
                    <label for="studentClass">Class/Course</label>
                    <select id="studentClass" class="form-control" required>
                        <option value="">Select your class/course</option>
                        <option value="10">Class 10</option>
                        <option value="11">Class 11</option>
                        <option value="12">Class 12</option>
                        <option value="neet">NEET</option>
                        <option value="jee">JEE</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" class="form-control" placeholder="Enter your password" required>
                </div>
                <button type="submit" class="btn">Login</button>
                <p style="margin-top: 15px; text-align: center;">
                    <a href="#" style="color: var(--primary);">Forgot Password?</a> |
                    <a href="#" style="color: var(--primary);">New Student Registration</a>
                </p>
            </form>
        </div>
    </div>

    <script>
        // Login Modal Functionality
        function openLoginModal() {
            document.getElementById('loginModal').style.display = 'flex';
        }
       
        function closeLoginModal() {
            document.getElementById('loginModal').style.display = 'none';
        }
       
        // Close modal if clicked outside of modal content
        window.onclick = function(event) {
            const modal = document.getElementById('loginModal');
            if (event.target === modal) {
                closeLoginModal();
            }
        }
       
        // Form Submission Handling
        document.getElementById('loginForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Login functionality would connect to a backend system in a production environment.');
            closeLoginModal();
        });
       
        document.getElementById('messageForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message. We will get back to you soon.');
            this.reset();
        });
    </script>
</body>
</html>

