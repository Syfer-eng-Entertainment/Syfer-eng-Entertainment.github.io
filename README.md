<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cool Hub</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #111;
            color: white;
            overflow-x: hidden;
            font-size: 18px;
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 50px;
            background-color: #333;
        }

        .navbar a {
            text-decoration: none;
            color: white;
            font-size: 18px;
            padding: 10px 20px;
            transition: background-color 0.3s ease;
        }

        .navbar a:hover {
            background-color: #777;
            border-radius: 5px;
        }

        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: white;
            font-size: 2rem;
            padding: 50px;
        }

        .hero h1 {
            font-size: 4rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.5rem;
            max-width: 600px;
            margin: 10px auto;
        }

        .cta-button {
            background-color: #ff7e5f;
            color: white;
            font-size: 18px;
            padding: 15px 30px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: background-color 0.3s ease;
            margin-top: 20px;
        }

        .cta-button:hover {
            background-color: #feb47b;
        }

        .section {
            padding: 50px;
            text-align: center;
        }

        .cards-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .card {
            background-color: #222;
            width: 250px;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.3);
        }

        .card h3 {
            font-size: 1.6rem;
            margin-bottom: 15px;
        }

        .card p {
            font-size: 1rem;
            margin-bottom: 20px;
        }

        .footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 30px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .footer a {
            color: #ff7e5f;
            text-decoration: none;
            font-size: 18px;
            padding: 5px;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </div>

    <!-- Hero Section -->
    <div class="hero">
        <h1>Welcome to Your Cool Hub</h1>
        <p>Your one-stop destination for everything cool and exciting. Explore, learn, and stay inspired!</p>
        <button class="cta-button">Explore Now</button>
    </div>

    <!-- Main Hub Sections -->
    <div class="section">
        <h2>Featured Sections</h2>
        <div class="cards-container">
            <div class="card">
                <h3>Technology</h3>
                <p>Latest trends in tech, gadgets, and innovations.</p>
                <a href="#">Learn More</a>
            </div>
            <div class="card">
                <h3>Design</h3>
                <p>Inspiring designs, architecture, and creative work.</p>
                <a href="#">Learn More</a>
            </div>
            <div class="card">
                <h3>Travel</h3>
                <p>Destinations, tips, and travel hacks for the wanderlust in you.</p>
                <a href="#">Learn More</a>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        <p>&copy; 2025 Cool Hub | Designed by Your Name</p>
        <p><a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
    </div>

</body>
</html>
