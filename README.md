<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Prince Arya</title>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <style>
        /* Global Styles */
        
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #fff;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
        
        header h1 {
            font-size: 1.8rem;
            color: #64ffda;
        }
        
        nav {
            display: flex;
            gap: 1rem;
        }
        
        nav a {
            text-decoration: none;
            color: #bbb;
            font-size: 1rem;
            transition: color 0.3s;
        }
        
        nav a:hover {
            color: #64ffda;
        }
        
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-top: 3rem;
            padding: 2rem;
            background: #1a1a2e;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
        
        .hero-text {
            max-width: 600px;
        }
        
        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            color: #aaa;
        }
        
        .hero-buttons a {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            margin: 0.5rem;
            border: 2px solid #64ffda;
            border-radius: 25px;
            text-decoration: none;
            color: #fff;
            font-size: 1rem;
            transition: all 0.3s;
        }
        
        .hero-buttons a.primary {
            background: #64ffda;
            color: #1a1a2e;
        }
        
        .hero-buttons a:hover {
            background: #1a1a2e;
            color: #64ffda;
        }
        
        .hero-image {
            position: relative;
            width: 300px;
            height: 300px;
            background: #203a43;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
        
        .hero-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .services {
            margin-top: 3rem;
            padding: 2rem;
            background: #1a1a2e;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }
        
        .services h3 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        
        .services-grid {
            display: flex;
            gap: 2rem;
            justify-content: space-between;
        }
        
        .service {
            flex: 1;
            background: #0f2027;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
        }
        
        .service h4 {
            font-size: 1.5rem;
            color: #64ffda;
            margin-bottom: 1rem;
        }
        
        .service p {
            color: #aaa;
            font-size: 1rem;
        }
        
        .socials {
            margin-top: 3rem;
            display: flex;
            justify-content: center;
            gap: 1rem;
        }
        
        .socials a {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 50px;
            height: 50px;
            background: transparent;
            border: 2px solid #64ffda;
            border-radius: 50%;
            font-size: 1.5rem;
            color: #64ffda;
            text-decoration: none;
            transition: all 0.3s;
        }
        
        .socials a:hover {
            background: #64ffda;
            color: #1a1a2e;
        }
    </style>
</head>

<body>
    <div class="container">
        <!-- Header Section -->
        <header>
            <h1>Prince Arya</h1>
            <nav>
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Services</a>
                <a href="#">Portfolio</a>
                <a href="#">Contact</a>
            </nav>
        </header>

        <!-- Hero Section -->
        <section class="hero">
            <div class="hero-text">
                <h2>Hello, It's Me <br> <span style="color:#64ffda;">Prince Arya</span></h2>
                <p>I'm a Frontend Developer specializing in creating beautiful and functional websites. Let’s bring your ideas to life!</p>
                <div class="hero-buttons">
                    <a href="#" class="primary">Download CV</a>
                    <a href="#">Hire Me</a>
                </div>
            </div>
            <div class="hero-image">
                <img src="images/WhatsApp Image 2024-09-13 at 21.18.24_a57a5d3f.jpg" alt="Profile Picture">
            </div>
        </section>

        <!-- Services Section -->
        <section class="services">
            <h3>My Services</h3>
            <div class="services-grid">
                <div class="service">
                    <h4>Web Development</h4>
                    <p>Crafting responsive and engaging websites tailored to your needs.</p>
                </div>
                <div class="service">
                    <h4>UI/UX Design</h4>
                    <p>Designing seamless user experiences that captivate and delight.</p>
                </div>
                <div class="service">
                    <h4>SEO Optimization</h4>
                    <p>Improving your website’s visibility and driving organic traffic.</p>
                </div>
            </div>
        </section>

        <!-- Social Links -->
        <div class="socials">
            <a href="#"><i class='bx bxl-facebook'></i></a>
            <a href="#"><i class='bx bxl-linkedin'></i></a>
            <a href="#"><i class='bx bxl-twitter'></i></a>
        </div>
    </div>
</body>

</html>
