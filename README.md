.doctor-card p {
            margin-bottom: 15px;
            color: gray;
        }

        /* ===== CTA ===== */
        .cta {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        .cta h2 {
            margin-bottom: 20px;
        }

        /* ===== FOOTER ===== */
        footer {
            background: #f5f5f5;
            padding: 30px 0;
            text-align: center;
            font-size: 14px;
        }

        /* ===== RESPONSIVE ===== */
        @media(max-width: 768px) {
            .hero h1 {
                font-size: 32px;
            }
        }
    </style>
</head>
<body>

<!-- HEADER -->
<header>
    <div class="container navbar">
        <div class="logo">CityCare Hospital</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Services</a>
            <a href="#">Doctors</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </div>
</header>

<!-- HERO -->
<section class="hero">
    <div class="container hero-content">
        <h1>Quality Healthcare For Everyone</h1>
        <p>We provide trusted medical services with advanced technology and compassionate care.</p>
        <a href="#" class="btn">Book Appointment</a>
        <a href="#" class="btn btn-outline">Learn More</a>
    </div>
</section>

<!-- SERVICES -->
<section class="section">
    <div class="container">
        <div class="section-title">
            <h2>Our Services</h2>
        </div>
        <div class="services">
            <div class="service-box">
                <h3>Emergency Care</h3>
                <p>24/7 emergency medical services with expert doctors.</p>
            </div>
            <div class="service-box">
                <h3>Cardiology</h3>
                <p>Advanced heart care with modern diagnostic tools.</p>
            </div>
            <div class="service-box">
                <h3>Neurology</h3>
                <p>Comprehensive brain and nervous system treatment.</p>
            </div>
            <div class="service-box">
                <h3>Diagnostics</h3>
                <p>Accurate lab tests and imaging services.</p>
            </div>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section class="section">
    <div class="container about">
        <div>
            <h2>About Our Hospital</h2>
            <p>
                CityCare Hospital is committed to providing high-quality healthcare services.
                Our experienced doctors, modern facilities, and patient-first approach ensure
                the best medical care for you and your family.
            </p>
        </div>
        <img src="https://images.unsplash.com/photo-1576765607924-3f7b8a9b54d4" alt="Hospital">
    </div>
</section>

<!-- DOCTORS -->
<section class="section">
    <div class="container">
        <div class="section-title">
            <h2>Our Doctors</h2>
        </div>
        <div class="doctors">
            <div class="doctor-card">
                <img src="https://images.unsplash.com/photo-1606813902788-5c6b47f98cfa" alt="">
                <h3>Dr. John Smith</h3>
                <p>Cardiologist</p>
            </div>
            <div class="doctor-card">
                <img src="https://images.unsplash.com/photo-1550831107-1553da8c8464" alt="">
                <h3>Dr. Sarah Lee</h3>
                <p>Neurologist</p>
            </div>
            <div class="doctor-card">
                <img src="https://images.unsplash.com/photo-1612349317150-e413f6a5b16d" alt="">
                <h3>Dr. Michael Brown</h3>
                <p>General Physician</p>
            </div>
        </div>
    </div>
</section>

<!-- CTA -->
<section class="cta">
    <h2>Need Medical Help?</h2>
    <p>Book your appointment with our specialists today.</p><br>
    <a href="#" class="btn">Book Appointment</a>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 CityCare Hospital. All Rights Reserved.</p>
</footer>

</body>
</html>
