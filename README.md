<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0f7fa; /* Light background color */
            color: #333;
        }
        header {
            background-color: #00bfa5; /* Neon green */
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #004d40; /* Dark teal */
        }
        nav a {
            color: #00e5ff; /* Neon cyan */
            padding: 1rem;
            text-decoration: none;
            text-align: center;
            transition: all 0.3s ease-in-out; /* Animation transition */
        }
        nav a:hover {
            background-color: #00695c; /* Darker teal */
            color: #fff; /* Change text color on hover */
            transform: scale(1.1); /* Slightly increase size on hover */
        }
        section {
            padding: 2rem;
        }
        .container {
            max-width: 1200px;
            margin: auto;
        }
        footer {
            background-color: #004d40; /* Dark teal */
            color: #00e5ff; /* Neon cyan */
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .background {
            background-image: url('https://www.example.com/business-commerce-background.jpg'); /* Replace with your background image URL */
            background-size: cover;
            background-position: center;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.1;
        }
    </style>
</head>
<body>
    <div class="background"></div>
    <header>
        <h1>Pranat Khatri</h1>
        <p>Wanted to be ACCA</p>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
        <a href="#blog">Blog</a>
    </nav>
    <section id="about" class="container">
        <h2>About Me</h2>
        <p>Unlocking Financial Insights, One Byte at a Time</p>
        <p><strong>Introduction:</strong> Hey there! I’m Pranat, a curious explorer of the financial universe. By day, I crunch numbers, analyze market trends, and sip coffee while deciphering stock charts. By night, I’m either reading up on the latest marketing strategies or dreaming about disruptive business models. Welcome to my corner of the internet!</p>
        <p><strong>My Journey:</strong> 🎓 Armed with a Coursera certificate in Financial Markets, I’ve dived headfirst into the exciting world of stocks, bonds, and derivatives. The thrill of understanding market dynamics keeps me awake at night (in a good way, of course). Whether it’s a bull run or a bear hug, count me in!</p>
        <p><strong>Finance Geek:</strong> 📈 Numbers are my jam. I believe that behind every stock ticker lies a story—a tale of risk, reward, and investor psychology. If you catch me staring at Excel spreadsheets with a gleam in my eye, don’t worry—I’m just plotting my next investment move.</p>
        <p><strong>Marketing Enthusiast:</strong> 📣 Marketing isn’t just about catchy slogans and flashy ads (though those
    </section>
    <section id="portfolio" class="container">
        <h2>Portfolio</h2>
        <p>Currently a student 🫠</p>
    </section>
    <section id="contact" class="container">
        <h2>Contact</h2>
        <p>GMAIL:pranat993@gmail.com</p>
    </section>
    <section id="blog" class="container">
        <h2>Blog</h2>
        <p>Will be come soon</p>
    </section>
    <footer>
        <p>&copy; 2024 Pranat Khatri. All rights reserved.</p>
    </footer>
</body>
</html>
