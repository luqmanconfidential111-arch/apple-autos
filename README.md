<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Apple Autos: Quality car accessories & spare parts in Uganda. Buy online or visit us in Kampala.">
    <title>Apple Autos | Car Accessories & Spare Parts Uganda</title>
    <style>
        /* General Styles */
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f5f6fa;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header & Navigation */
        header {
            background: linear-gradient(90deg, #3b1c5a, #0a1f44);
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            font-weight: bold;
            font-size: 16px;
        }

        /* Sections */
        section {
            padding: 40px 20px;
            max-width: 1100px;
            margin: auto;
        }

        h2 {
            color: #3b1c5a;
            text-align: center;
            margin-bottom: 30px;
        }

        /* Cards & Grid */
        .services, .gallery, .testimonials {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            text-align: center;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
        }

        /* Buttons */
        .btn {
            display: inline-block;
            background: #3b1c5a;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            margin-top: 10px;
        }

        /* Footer */
        footer {
            background: #0a1f44;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        /* WhatsApp Button */
        .whatsapp {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25D366;
            color: white;
            padding: 15px;
            border-radius: 50px;
            font-size: 24px;
            text-align: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.2);
        }

        iframe {
            width: 100%;
            border: 0;
            border-radius: 10px;
            height: 300px;
        }

        /* Responsive */
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Apple Autos</h1>
        <p>Car Accessories & Spare Parts | Uganda</p>
        <nav>
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#gallery">Gallery</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to Apple Autos</h2>
        <p style="text-align:center; max-width:700px; margin:auto;">
            Apple Autos is your trusted supplier of quality car accessories and spare parts in Uganda. We serve individuals, garages, and businesses with reliable automotive products at competitive prices.
        </p>
        <div style="text-align:center; margin-top:20px;">
            <a href="#contact" class="btn">Get in Touch</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products">
        <h2>Our Products & Services</h2>
        <div class="services">
            <div class="card">
                <h3>Car Accessories</h3>
                <p>Audio systems, mats, lights, covers</p>
            </div>
            <div class="card">
                <h3>Genuine & Aftermarket Parts</h3>
                <p>Quality spare parts for all car models</p>
            </div>
            <div class="card">
                <h3>Installation & Fitment</h3>
                <p>Professional installation of all accessories</p>
            </div>
            <div class="card">
                <h3>Wholesale Supply</h3>
                <p>Dealers and garages supported with bulk orders</p>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2>Product Gallery</h2>
        <div class="gallery">
            <div class="card"><img src="images/car-audio.jpg" alt="Car Audio Systems"></div>
            <div class="card"><img src="images/car-mats.jpg" alt="Car Mats"></div>
            <div class="card"><img src="images/car-lights.jpg" alt="Car Lights"></div>
            <div class="card"><img src="images/spare-parts.jpg" alt="Spare Parts"></div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <h2>Testimonials</h2>
        <div class="testimonials">
            <div class="card">
                <p>“Great parts and fast service. Highly recommended!”</p>
                <strong>- Garage Owner, Kampala</strong>
            </div>
            <div class="card">
                <p>“Affordable prices and quality products. Very happy!”</p>
                <strong>- Customer, Mukono</strong>
            </div>
            <div class="card">
                <p>“Installation was professional and quick.”</p>
                <strong>- Car Owner, Entebbe</strong>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p style="text-align:center;">
            Phone: <a href="tel:+256740388468">0740388468</a> / <a href="tel:+256766380468">0766380468</a><br>
            Email: <a href="mailto:luqmanconfidential111@gmail.com">luqmanconfidential111@gmail.com</a><br>
            Location: Kampala, Uganda
        </p>
        <iframe 
            src="https://maps.google.com/maps?q=kampala%20uganda&t=&z=13&ie=UTF8&iwloc=&output=embed"
            allowfullscreen>
        </iframe>
    </section>

    <!-- Footer -->
    <footer>
        © 2025 Apple Autos | All Rights Reserved.
    </footer>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/256740388468" class="whatsapp" target="_blank">💬</a>

</body>
</html>
