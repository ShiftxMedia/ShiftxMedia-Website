<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShiftxMedia | Automotive Marketing Experts</title>
    <script>
        console.log("Page is loading...");
    </script>
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            color: #F5F5F5;
            text-align: center;
            background: url('background-car.jpg') no-repeat center center/cover;
        }
        header {
            background-color: rgba(192, 163, 110, 0.9);
            padding: 20px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        .logo {
            margin: 20px auto;
            width: 200px;
            display: block;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 50px 0;
        }
        .cta-button {
            background-color: #B08D57;
            color: #1E2A38;
            padding: 15px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            font-size: 18px;
            display: inline-block;
            margin-top: 20px;
            cursor: pointer;
        }
        .services {
            display: flex;
            justify-content: space-around;
            margin-top: 40px;
        }
        .service-box {
            background-color: rgba(45, 45, 45, 0.9);
            padding: 20px;
            border-radius: 10px;
            width: 30%;
        }
        footer {
            background-color: rgba(45, 45, 45, 0.9);
            text-align: center;
            padding: 20px;
            margin-top: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        .footer-logo {
            width: 50px;
            height: auto;
        }
    </style>
</head>
<body>
    <header>ShiftxMedia | Automotive Marketing Experts</header>
    
    <img src="ShiftxMedia.png" alt="ShiftxMedia Logo" class="logo">
    
    <script>
        console.log("Header and logo have been loaded.");
    </script>
    
    <div class="container">
        <h1>Fueling Your Auto Business with Digital Marketing</h1>
        <p>We manage social media for dealerships, film protection installers, and more!</p>
        <a href="#contact" class="cta-button" id="get-started">Get Started</a>
        
        <div class="services">
            <div class="service-box">
                <h2>Social Media Management</h2>
                <p>We create and manage content that engages and converts.</p>
            </div>
            <div class="service-box">
                <h2>Paid Advertising</h2>
                <p>Boost your brand with targeted automotive ads.</p>
            </div>
            <div class="service-box">
                <h2>Brand Growth</h2>
                <p>We help auto businesses stand out online.</p>
            </div>
        </div>
    </div>
    
    <script>
        console.log("Services section loaded.");
    
        document.getElementById("get-started").addEventListener("click", function(event) {
            event.preventDefault();
            console.log("Get Started button clicked. Redirecting...");
            window.location.href = "#contact";
        });
    </script>
    
    <footer>
        <img src="ShiftxMedia.png" alt="ShiftxMedia Logo" class="footer-logo">
        <p>© 2025 ShiftxMedia | All Rights Reserved</p>
    </footer>
    
    <script>
        console.log("Footer loaded. Page setup complete.");
    </script>
</body>
</html>
