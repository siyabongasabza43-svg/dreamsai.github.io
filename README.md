# pgls clothing.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PGLS Clothing | Stance Junkies</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            background: #111;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 32px;
            letter-spacing: 2px;
        }

        nav {
            background: #222;
            display: flex;
            justify-content: center;
            padding: 10px;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff0055;
        }

        .hero {
            background: #111;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        .hero h2 {
            font-size: 40px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 18px;
        }

        .section {
            padding: 50px 20px;
            max-width: 900px;
            margin: auto;
        }

        .section h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .product-card {
            background: white;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }

        .product-card img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            margin-top: 50px;
            background: #111;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <header>
        <h1>PGLS Clothing</h1>
        <p>Stance Junkies</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h2>Born in Mhluzi. Designed for the Stance Junkies.</h2>
        <p>Fashion for women & girls who own their style.</p>
    </section>

    <section id="about" class="section">
        <h2>About PGLS Clothing</h2>
        <p>
            PGLS Clothing is a street-born fashion brand from Mhluzi, created for women and girls 
            who express themselves through bold stance, originality and street confidence.  
            What started in the local streets is now growing into a brand with the mission 
            to scale nationwide and beyond.
        </p>
        <p>
            Our slogan “Stance Junkies” represents the energy, attitude and culture behind 
            every piece we create.
        </p>
    </section>

    <section id="products" class="section">
        <h2>Featured Products</h2>
        <p style="text-align:center;">Images coming soon...</p>

        <div class="products">
            <!-- Example product card (replace with your real images later) -->
            <div class="product-card">
                <img src="placeholder.jpg" alt="Product Image" />
                <h3>Product Name</h3>
                <p>Short description...</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact</h2>
        <p style="text-align:center;">
            Email: <strong>info@pglsclothing.com</strong><br>
            Instagram: <strong>@pgls_clothing</strong><br>
            WhatsApp Business: <strong>+27 ___ ___ ___</strong>
        </p>
    </section>

    <footer>
        © 2025 PGLS Clothing — Stance Junkies. All Rights Reserved.
    </footer>

</body>
</html>
