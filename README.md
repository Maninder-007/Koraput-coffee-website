<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Koraput Coffee</title>
</head>
<body>
    <header class="header">
        <h1>Koraput Coffee</h1>
        <p>India's Tribal Heartland</p>
    </header>
    <section class="main-content">
        <div class="content-box">
            <h2>About Us</h2>
            <p>Koraput coffee comes from the Koraput district in the state of Odisha, India. This region, known for its lush greenery, moderate climate, and fertile soil, provides an ideal environment for coffee cultivation. Koraput coffee is primarily grown by tribal farmers in the hilly terrains of the Eastern Ghats.</p>
            <a href="#" class="button">READ MORE</a>
        </div>
        <div class="content-box">
            <h2>Our Mission</h2>
            <p>We improve the livelihoods of tribal farmers by paying them a fair price for the wild forest coffee they grow. With access to land, training, and the market, they break their reliance on podu farming, planting trees that restore the natural eco-system.</p>
            <a href="#" class="button">READ MORE</a>
        </div>
    </section>
    <section class="awards-section">
        <h2>Awards & Recognition</h2>
        <div class="award-card">
            <img src="award1.png" alt="Award 1">
            <p>Won 5th world coffee conference</p>
        </div>
        <div class="award-card">
            <img src="award2.png" alt="Award 2">
            <p>The Fine Cup Award 2023</p>
        </div>
        <div class="award-card">
            <img src="award3.png" alt="Award 3">
            <p>Certificate of appreciation for qualifying as one of the top five coffees in the shed Arabica category of Know Your Kaapi</p>
        </div>
    </section>
    <footer class="footer">
        <p>&copy; 2024 KoraputCoffee.org</p>
    </footer>
</body>
</html># Koraput-coffee-website

css 

 {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

.header h1 {
    margin-bottom: 0.5rem;
}

.main-content {
    display: flex;
    justify-content: space-around;
    padding: 2rem;
}

.content-box {
    background-color: #f4f4f4;
    border: 1px solid #ddd;
    padding: 1.5rem;
    width: 45%;
}

.content-box h2 {
    margin-bottom: 1rem;
}

.button {
    background-color: #4CAF50;
    border: none;
    border-radius: 5px;
    color: white;
    padding: 0.5rem 1rem;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 1rem;
    margin-top: 1rem;
    cursor: pointer;
}
