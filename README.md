<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Summer Internship 2025 | High Tech Software House & Training Center</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap"
        rel="stylesheet">
    <style>
        :root {
            --primary: #2563eb;
            --primary-light: #3b82f6;
            --secondary: #10b981;
            --dark: #1e293b;
            --light: #f8fafc;
            --gray: #64748b;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            color: var(--dark);
            line-height: 1.6;
            background-color: #f1f5f9;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        section {
            padding: 80px 0;
        }

        h1,
        h2,
        h3 {
            font-weight: 600;
            line-height: 1.2;
        }

        h1 {
            font-size: 2.5rem;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 40px;
            text-align: center;
        }

        h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        p {
            color: var(--gray);
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            background-color: var(--primary);
            color: white;
            padding: 12px 24px;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }

        .btn-secondary {
            background-color: var(--secondary);
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .btn-secondary:hover {
            background-color: #0ca678;
        }

        /* Header */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            z-index: 100;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary);
            text-decoration: none;
        }

        .logo img {
            height: 40px;
        }

        .nav-links {
            display: flex;
            list-style: none;
        }

        .nav-links li {
            margin-left: 30px;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--dark);
        }

        /* Hero Section */
        #hero {
            padding-top: 120px;
            background: linear-gradient(135deg, #e0f2fe 0%, #f0f9ff 100%);
        }

        .hero-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 40px;
        }

        .hero-text {
            flex: 1;
        }

        .hero-image {
            flex: 1;
            text-align: center;
        }

        .hero-image img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .hero-text h1 {
            margin-bottom: 20px;
        }

        .hero-text p {
            font-size: 1.1rem;
            margin-bottom: 30px;
            max-width: 500px;
        }

        .badge {
            display: inline-block;
            background-color: var(--secondary);
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            margin-right: 10px;
            margin-bottom: 10px;
        }

        /* About Section */
        #about {
            background-color: white;
        }

        .about-content {
            display: flex;
            align-items: center;
            gap: 40px;
        }

        .about-text {
            flex: 1;
        }

        .about-image {
            flex: 1;
            text-align: center;
        }

        .about-image img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .timing-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .timing-card {
            background-color: #f8fafc;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            word-wrap: break-word;
            overflow-wrap: break-word;
            hyphens: auto;
        }

        .timing-card h4 {
            color: var(--primary);
            margin-bottom: 10px;
        }

        /* Roles Section */
        #roles {
            background-color: #f8fafc;
        }

        .roles-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .role-card {
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
            word-wrap: break-word;
            overflow-wrap: break-word;
            hyphens: auto;
        }

        .role-card:hover {
            transform: translateY(-5px);
        }

        .role-icon {
            font-size: 2rem;
            color: var(--primary);
            margin-bottom: 15px;
        }

        /* Benefits Section */
        #benefits {
            background-color: white;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .benefit-card {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            word-wrap: break-word;
            overflow-wrap: break-word;
            hyphens: auto;
        }

        .benefit-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .benefit-icon {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 20px;
        }

        /* Contact Section */
        #contact {
            background-color: #f8fafc;
        }

        .contact-container {
            display: flex;
            gap: 40px;
        }

        .contact-info {
            flex: 1;
        }

        .contact-form {
            flex: 1;
            background-color: white;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #e2e8f0;
            border-radius: 4px;
            font-size: 1rem;
            transition: border-color 0.3s ease;
        }

        .form-group input:focus,
        .form-group select:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: var(--primary);
        }

        .form-group textarea {
            min-height: 120px;
            resize: vertical;
        }

        .error {
            color: #dc2626;
            font-size: 0.875rem;
            margin-top: 5px;
            display: none;
        }

        .success-message {
            background-color: #dcfce7;
            color: #166534;
            padding: 15px;
            border-radius: 4px;
            margin-bottom: 20px;
            text-align: center;
            display: none;
        }

        .info-card {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            word-wrap: break-word;
            overflow-wrap: break-word;
        }

        .info-card h4 {
            color: var(--primary);
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 40px 0 20px;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }

        .footer-column h3 {
            color: white;
            margin-bottom: 20px;
            font-size: 1.2rem;
        }

        .footer-column ul {
            list-style: none;
        }

        .footer-column ul li {
            margin-bottom: 10px;
        }

        .footer-column ul li a {
            color: #cbd5e1;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .footer-column ul li a:hover {
            color: white;
        }

        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #334155;
        }

        /* Scroll to top button */
        .scroll-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 50px;
            height: 50px;
            background-color: var(--primary);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            z-index: 99;
        }

        .scroll-top.active {
            opacity: 1;
            visibility: visible;
        }

        .scroll-top:hover {
            background-color: var(--primary-light);
        }

        /* Responsive styles */
        @media (max-width: 992px) {
            .contact-container {
                flex-direction: column;
            }

            .about-content {
                flex-direction: column;
            }
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 1.8rem;
            }

            h2 {
                font-size: 1.6rem;
                margin-bottom: 30px;
            }

            section {
                padding: 50px 0;
            }

            .hero-content,
            .about-content {
                flex-direction: column;
                text-align: center;
                gap: 30px;
            }

            .hero-text p,
            .about-text p {
                max-width: 100%;
                font-size: 1rem;
            }

            .nav-links {
                position: fixed;
                top: 70px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 70px);
                background-color: white;
                flex-direction: column;
                align-items: center;
                padding: 20px;
                transition: left 0.3s ease;
                overflow-y: auto;
            }

            .nav-links.active {
                left: 0;
            }

            .nav-links li {
                margin: 12px 0;
                width: 100%;
                text-align: center;
            }

            .nav-links a {
                display: block;
                padding: 8px 0;
            }

            .mobile-menu-btn {
                display: block;
                font-size: 1.3rem;
            }

            .timing-grid,
            .roles-grid,
            .benefits-grid {
                grid-template-columns: 1fr;
                gap: 15px;
            }

            .role-card,
            .benefit-card {
                padding: 20px;
            }

            .badge {
                font-size: 0.7rem;
                padding: 4px 8px;
                margin-right: 5px;
                margin-bottom: 8px;
            }

            .btn {
                padding: 10px 18px;
                font-size: 0.9rem;
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 1.6rem;
                margin-bottom: 15px;
            }

            h2 {
                font-size: 1.4rem;
                margin-bottom: 25px;
            }

            h3 {
                font-size: 1.2rem;
            }

            .container {
                padding: 0 15px;
            }

            section {
                padding: 40px 0;
            }

            .contact-form {
                padding: 25px 15px;
            }

            .form-group input,
            .form-group select,
            .form-group textarea {
                padding: 10px;
                font-size: 0.9rem;
            }

            .info-card {
                padding: 15px;
            }

            .role-card p,
            .benefit-card p,
            .timing-card p {
                font-size: 0.9rem;
                line-height: 1.5;
            }
        }

        @media (max-width: 350px) {
            .logo img {
                height: 30px;
            }

            .hero-text h1 {
                font-size: 1.4rem;
            }

            .btn {
                padding: 8px 15px;
                font-size: 0.8rem;
            }

            .nav-links {
                top: 60px;
                height: calc(100vh - 60px);
            }

            .footer-column {
                margin-bottom: 20px;
            }
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <a href="#" class="logo">
                    <img src="logohightech.PNG" alt="High Tech Software House & Training Center">
                </a>
                <button class="mobile-menu-btn">
                    <i class="fas fa-bars"></i>
                </button>
                <ul class="nav-links">
                    <li><a href="#hero">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#roles">Roles</a></li>
                    <li><a href="#benefits">Benefits</a></li>
                    <li><a href="#contact">Apply Now</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <span class="badge">PSEB Registered</span>
                    <span class="badge">Ministry of IT, Pakistan</span>
                    <h1>1-Month Summer Internship Program July 2025</h1>
                    <p>Gain hands-on experience in a real-world, project-based environment with High Tech Software House
                        & Training Center. Earn a PSEB-recognized certificate and kickstart your tech career.</p>
                    <div style="display: flex; gap: 15px;">
                        <a href="#contact" class="btn">Apply Now</a>
                        <a href="#about" class="btn btn-secondary">Learn More</a>
                    </div>
                </div>
                <div class="hero-image">
                    <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80"
                        alt="Internship Program">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About The Internship</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>This 1-month intensive internship program is designed to provide practical, hands-on experience
                        in a real-world, project-based environment. Participants will work on actual client projects and
                        receive mentorship from experienced professionals.</p>

                    <h3 style="margin-top: 30px;">Internship Timings</h3>
                    <p>Choose a shift that works best for your schedule:</p>

                    <div class="timing-grid">
                        <div class="timing-card">
                            <h4>Morning Shift</h4>
                            <p>9:00 AM - 12:00 PM</p>
                        </div>
                        <div class="timing-card">
                            <h4>Afternoon Shift</h4>
                            <p>2:00 PM - 5:00 PM</p>
                        </div>
                        <div class="timing-card">
                            <h4>Evening Shift</h4>
                            <p>6:00 PM - 9:00 PM</p>
                        </div>
                        <div class="timing-card">
                            <h4>Night Shift</h4>
                            <p>10:00 PM - 12:00 AM</p>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80"
                        alt="Team working together">
                </div>
            </div>
        </div>
    </section>

    <!-- Roles Section -->
    <section id="roles">
        <div class="container">
            <h2>Available Internship Roles</h2>
            <div class="roles-grid">
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-paint-brush"></i>
                    </div>
                    <h3>Graphic Designer</h3>
                    <p>Create visual concepts using computer software to communicate ideas that inspire, inform, and
                        captivate consumers.</p>
                </div>
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3>Web Developer</h3>
                    <p>Build and maintain websites, ensuring they are visually appealing, easy to navigate, and
                        functional.</p>
                </div>
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-pen-fancy"></i>
                    </div>
                    <h3>Content Writer</h3>
                    <p>Create engaging content for websites, blogs, and marketing materials that attracts and retains
                        customers.</p>
                </div>
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3>Flutter Developer</h3>
                    <p>Develop cross-platform mobile applications using Flutter framework.</p>
                </div>
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>SEO & Digital Marketing</h3>
                    <p>Help businesses grow their online presence through search engine optimization and digital
                        marketing strategies.</p>
                </div>
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-video"></i>
                    </div>
                    <h3>Video Editor</h3>
                    <p>Edit and produce video content for various platforms, ensuring high-quality output.</p>
                </div>
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-hashtag"></i>
                    </div>
                    <h3>Social Media Manager</h3>
                    <p>Manage social media accounts, create content, and engage with audiences to build brand awareness.
                    </p>
                </div>
                <div class="role-card">
                    <div class="role-icon">
                        <i class="fas fa-pencil-ruler"></i>
                    </div>
                    <h3>UI/UX Designer</h3>
                    <p>Design user interfaces and experiences that are intuitive, accessible, and aesthetically
                        pleasing.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section id="benefits">
        <div class="container">
            <h2>What We Offer</h2>
            <div class="benefits-grid">
                <div class="benefit-card">
                    <div class="benefit-icon">
                        <i class="fas fa-handshake"></i>
                    </div>
                    <h3>Real-World Experience</h3>
                    <p>Work on actual client projects to build your portfolio and gain practical skills that employers
                        value.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">
                        <i class="fas fa-certificate"></i>
                    </div>
                    <h3>PSEB-Recognized Certificate</h3>
                    <p>Receive a certificate upon completion that is recognized by the Pakistan Software Export Board
                        and Ministry of IT.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">
                        <i class="fas fa-briefcase"></i>
                    </div>
                    <h3>Job Opportunities</h3>
                    <p>Top performers may receive job offers or recommendations for career advancement.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <h3>Professional Mentorship</h3>
                    <p>Learn from experienced professionals who will guide you through your projects and career
                        development.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Networking Opportunities</h3>
                    <p>Connect with peers and industry experts to expand your professional network.</p>
                </div>
                <div class="benefit-card">
                    <div class="benefit-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Skill Enhancement</h3>
                    <p>Develop in-demand skills through hands-on experience with real client projects.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Apply for Internship</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="info-card">
                        <h4>Key Information</h4>
                        <p><strong>Application Deadline:</strong> 3rd July 2025</p>
                        <p><strong>Internship Duration:</strong> 1 Month (July 2025)</p>
                        <p><strong>Location:</strong> Remote or On-Site (Nawabshah)</p>
                        <p><strong>Certificate:</strong> PSEB-recognized upon completion</p>
                    </div>
                    <div class="info-card">
                        <h4>Contact Details</h4>
                        <p><i class="fas fa-map-marker-alt"></i> <strong>New Address:</strong> Near Quaid-e-Awam
                            University, Infront of Aman Medical Complex, Airport Road, Nawabshah, Shaheed Benazirabad
                        </p>
                        <p><i class="fas fa-map-marker-alt"></i> <strong>Previous Address:</strong> Software Technology
                            Park, Software Engineering Department, Quaid-e-Awam University of Engineering, Science &
                            Technology, Nawabshah</p>
                        <p><i class="fas fa-phone"></i> <strong>Phone:</strong> 0309-8038363</p>
                        <p><i class="fas fa-envelope"></i> <strong>Email:</strong> hightechsba@gmail.com</p>
                        <p><i class="fas fa-globe"></i> <strong>Website:</strong> www.hightechsba.com</p>
                    </div>
                </div>
                <div class="contact-form">
                    <div class="success-message">
                        Thank you for your application! We'll contact you soon.
                    </div>
                    <form id="internshipForm">
                        <h3 style="margin-bottom: 20px;">Applicant Information</h3>

                        <div class="form-group">
                            <label for="name">Full Name *</label>
                            <input type="text" id="name" name="name" placeholder="Your full name">
                            <div class="error" id="nameError">Please enter your name</div>
                        </div>

                        <div class="form-group">
                            <label for="phone">Phone Number (WhatsApp) *</label>
                            <input type="tel" id="phone" name="phone" placeholder="03098038363">
                            <div class="error" id="phoneError">Please enter a valid phone number</div>
                        </div>

                        <div class="form-group">
                            <label for="email">Email Address *</label>
                            <input type="email" id="email" name="email" placeholder="your.email@example.com">
                            <div class="error" id="emailError">Please enter a valid email</div>
                        </div>

                        <div class="form-group">
                            <label for="gender">Gender *</label>
                            <select id="gender" name="gender">
                                <option value="">Select Gender</option>
                                <option value="Male">Male</option>
                                <option value="Female">Female</option>
                            </select>
                            <div class="error" id="genderError">Please select your gender</div>
                        </div>

                        <div class="form-group">
                            <label for="city">City & Province *</label>
                            <input type="text" id="city" name="city" placeholder="Nawabshah, Sindh">
                            <div class="error" id="cityError">Please enter your city and province</div>
                        </div>

                        <h3 style="margin: 30px 0 20px;">Education Information</h3>

                        <div class="form-group">
                            <label for="institute">Institute Name (College/University) *</label>
                            <input type="text" id="institute" name="institute" placeholder="Quaid-e-Awam University">
                            <div class="error" id="instituteError">Please enter your institute name</div>
                        </div>

                        <div class="form-group">
                            <label for="degree">Degree / Program *</label>
                            <input type="text" id="degree" name="degree" placeholder="e.g., BSCS, BBA, DIT">
                            <div class="error" id="degreeError">Please enter your degree program</div>
                        </div>

                        <div class="form-group">
                            <label for="year">Year of Study with Batch *</label>
                            <select id="year" name="year">
                                <option value="">Select Year</option>
                                <option value="1st Year">1st Year</option>
                                <option value="2nd Year">2nd Year</option>
                                <option value="3rd Year">3rd Year</option>
                                <option value="Final Year">Final Year</option>
                                <option value="Completed">Completed</option>
                            </select>
                            <div class="error" id="yearError">Please select your year of study</div>
                        </div>

                        <div class="form-group">
                            <label for="role">Preferred Internship Role *</label>
                            <select id="role" name="role">
                                <option value="">Select Role</option>
                                <option value="Graphic Designer">Graphic Designer</option>
                                <option value="Web Developer">Web Developer</option>
                                <option value="Content Writer">Content Writer</option>
                                <option value="Flutter Developer">Flutter Developer</option>
                                <option value="SEO & Digital Marketing">SEO & Digital Marketing</option>
                                <option value="Video Editor">Video Editor</option>
                                <option value="Social Media Manager">Social Media Manager</option>
                                <option value="UI/UX Designer">UI/UX Designer</option>
                                <option value="Android Developer">Android Developer</option>
                                <option value="WordPress Developer">WordPress Developer</option>
                            </select>
                            <div class="error" id="roleError">Please select your preferred role</div>
                        </div>

                        <div class="form-group">
                            <label for="shift">Preferred Shift *</label>
                            <select id="shift" name="shift">
                                <option value="">Select Shift</option>
                                <option value="Morning (9AM-12PM)">Morning (9AM-12PM)</option>
                                <option value="Afternoon (2PM-5PM)">Afternoon (2PM-5PM)</option>
                                <option value="Evening (6PM-9PM)">Evening (6PM-9PM)</option>
                                <option value="Night (10PM-12AM)">Night (10PM-12AM)</option>
                            </select>
                            <div class="error" id="shiftError">Please select your preferred shift</div>
                        </div>

                        <div class="form-group">
                            <label for="mode">Internship Mode *</label>
                            <select id="mode" name="mode">
                                <option value="">Select Mode</option>
                                <option value="Remote">Remote</option>
                                <option value="On-Site">On-Site (Nawabshah)</option>
                            </select>
                            <div class="error" id="modeError">Please select your preferred mode</div>
                        </div>

                        <div class="form-group">
                            <label for="message">Why are you interested in this internship? *</label>
                            <textarea id="message" name="message"
                                placeholder="Tell us about your skills and why you're interested in this opportunity"></textarea>
                            <div class="error" id="messageError">Please tell us why you're interested</div>
                        </div>

                        <button type="submit" class="btn">Submit Application</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>High Tech Software House</h3>
                    <p>Registered with PSEB, Ministry of IT, Government of Pakistan. Providing quality training and
                        internship programs to develop the next generation of tech professionals.</p>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#hero">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#roles">Internship Roles</a></li>
                        <li><a href="#benefits">Benefits</a></li>
                        <li><a href="#contact">Apply Now</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Us</h3>
                    <ul>
                        <li><i class="fas fa-map-marker-alt"></i> Nawabshah, Shaheed Benazirabad</li>
                        <li><i class="fas fa-phone"></i> 0309-8038363</li>
                        <li><i class="fas fa-envelope"></i> hightechsba@gmail.com</li>
                        <li><i class="fas fa-globe"></i> www.hightechsba.com</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 High Tech Software House & Training Center. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Scroll to top button -->
    <div class="scroll-top">
        <i class="fas fa-arrow-up"></i>
    </div>

    <script>
        // Mobile menu toggle
        const mobileMenuBtn = document.querySelector('.mobile-menu-btn');
        const navLinks = document.querySelector('.nav-links');

        mobileMenuBtn.addEventListener('click', () => {
            navLinks.classList.toggle('active');
            mobileMenuBtn.innerHTML = navLinks.classList.contains('active')
                ? '<i class="fas fa-times"></i>'
                : '<i class="fas fa-bars"></i>';
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                // Close mobile menu if open
                if (navLinks.classList.contains('active')) {
                    navLinks.classList.remove('active');
                    mobileMenuBtn.innerHTML = '<i class="fas fa-bars"></i>';
                }

                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Scroll to top button
        const scrollTopBtn = document.querySelector('.scroll-top');

        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                scrollTopBtn.classList.add('active');
            } else {
                scrollTopBtn.classList.remove('active');
            }
        });

        scrollTopBtn.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Form validation
        const form = document.getElementById('internshipForm');
        const successMessage = document.querySelector('.success-message');

        // Get all form fields and error elements
        const nameInput = document.getElementById('name');
        const phoneInput = document.getElementById('phone');
        const emailInput = document.getElementById('email');
        const genderInput = document.getElementById('gender');
        const cityInput = document.getElementById('city');
        const instituteInput = document.getElementById('institute');
        const degreeInput = document.getElementById('degree');
        const yearInput = document.getElementById('year');
        const roleInput = document.getElementById('role');
        const shiftInput = document.getElementById('shift');
        const modeInput = document.getElementById('mode');
        const messageInput = document.getElementById('message');

        const nameError = document.getElementById('nameError');
        const phoneError = document.getElementById('phoneError');
        const emailError = document.getElementById('emailError');
        const genderError = document.getElementById('genderError');
        const cityError = document.getElementById('cityError');
        const instituteError = document.getElementById('instituteError');
        const degreeError = document.getElementById('degreeError');
        const yearError = document.getElementById('yearError');
        const roleError = document.getElementById('roleError');
        const shiftError = document.getElementById('shiftError');
        const modeError = document.getElementById('modeError');
        const messageError = document.getElementById('messageError');

        form.addEventListener('submit', (e) => {
            e.preventDefault();

            let isValid = true;

            // Reset errors
            nameError.style.display = 'none';
            phoneError.style.display = 'none';
            emailError.style.display = 'none';
            genderError.style.display = 'none';
            cityError.style.display = 'none';
            instituteError.style.display = 'none';
            degreeError.style.display = 'none';
            yearError.style.display = 'none';
            roleError.style.display = 'none';
            shiftError.style.display = 'none';
            modeError.style.display = 'none';
            messageError.style.display = 'none';

            // Validate name
            if (nameInput.value.trim() === '') {
                nameError.style.display = 'block';
                isValid = false;
            }

            // Validate phone
            const phoneRegex = /^[0-9]{11}$/;
            if (!phoneRegex.test(phoneInput.value.trim())) {
                phoneError.style.display = 'block';
                isValid = false;
            }

            // Validate email
            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!emailRegex.test(emailInput.value.trim())) {
                emailError.style.display = 'block';
                isValid = false;
            }

            // Validate gender
            if (genderInput.value === '') {
                genderError.style.display = 'block';
                isValid = false;
            }

            // Validate city
            if (cityInput.value.trim() === '') {
                cityError.style.display = 'block';
                isValid = false;
            }

            // Validate institute
            if (instituteInput.value.trim() === '') {
                instituteError.style.display = 'block';
                isValid = false;
            }

            // Validate degree
            if (degreeInput.value.trim() === '') {
                degreeError.style.display = 'block';
                isValid = false;
            }

            // Validate year
            if (yearInput.value === '') {
                yearError.style.display = 'block';
                isValid = false;
            }

            // Validate role
            if (roleInput.value === '') {
                roleError.style.display = 'block';
                isValid = false;
            }

            // Validate shift
            if (shiftInput.value === '') {
                shiftError.style.display = 'block';
                isValid = false;
            }

            // Validate mode
            if (modeInput.value === '') {
                modeError.style.display = 'block';
                isValid = false;
            }

            // Validate message
            if (messageInput.value.trim() === '') {
                messageError.style.display = 'block';
                isValid = false;
            }

            if (isValid) {
                // Form is valid - show success message
                successMessage.style.display = 'block';
                form.reset();

                // Scroll to success message
                successMessage.scrollIntoView({ behavior: 'smooth' });

                // Hide success message after 5 seconds
                setTimeout(() => {
                    successMessage.style.display = 'none';
                }, 5000);
            }
        });
    </script>
</body>

</html>
