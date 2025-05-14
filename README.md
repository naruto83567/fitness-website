<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Working with AI</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        h1, h2 {
            color: #333;
        }

        /* Navigation Bar */
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #555;
        }

        /* Main Section Styles */
        section {
            padding: 20px;
            margin: 20px 0;
        }

        /* Benefits Section */
        .benefits, .non-benefits {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .card {
            background-color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            width: 45%;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .card img {
            width: 50px;
            margin-bottom: 10px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .card {
                width: 80%;
            }

            nav {
                text-align: left;
                padding: 15px;
            }
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        /* Inspirational Quote Styles */
        .quote {
            font-style: italic;
            color: #555;
            text-align: center;
            margin-top: 20px;
            font-size: 1.2em;
        }

        .quote p {
            font-size: 1.3em;
        }
    </style>
</head>
<body>

    <nav>
        <a href="#home">Home</a>
        <a href="#benefits">Health Benefits</a>
        <a href="#non-benefits">Non-Benefits</a>
        <a href="#quotes">Quotes</a>
    </nav>

    <!-- Homepage Section -->
    <section id="home">
        <h1>Welcome to Working with AI</h1>
        <p>Your journey with fitness starts here. Learn how working out impacts your health, how to avoid the risks, and get inspired with motivational quotes from famous figures!</p>
        <p><em>"The hardest part is doing it every day. It gets easier with time." – Unknown</em></p>
    </section>

    <!-- Health Benefits Section -->
    <section id="benefits">
        <h2>Health Benefits of Working Out</h2>
        <div class="benefits">
            <div class="card">
                <img src="https://via.placeholder.com/50" alt="Heart icon">
                <h3>Physical Health</h3>
                <p>Improve your cardiovascular health, strengthen muscles, and increase flexibility.</p>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/50" alt="Brain icon">
                <h3>Mental Health</h3>
                <p>Exercise can reduce anxiety, depression, and improve overall mood.</p>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/50" alt="Sleep icon">
                <h3>Better Sleep</h3>
                <p>Regular workouts help regulate your sleep cycle for deeper rest.</p>
            </div>
        </div>
    </section>

    <!-- Non-Benefits Section -->
    <section id="non-benefits">
        <h2>Non-Benefits of Over-Exercising</h2>
        <div class="non-benefits">
            <div class="card">
                <img src="https://via.placeholder.com/50" alt="Injury icon">
                <h3>Risk of Injury</h3>
                <p>Overtraining or improper form can lead to serious injuries.</p>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/50" alt="Fatigue icon">
                <h3>Fatigue</h3>
                <p>Too much exercise can lead to exhaustion and burnout.</p>
            </div>
        </div>
    </section>

    <!-- Quotes Section -->
    <section id="quotes">
        <h2>Inspiring Workout Quotes</h2>
        <div class="quote">
            <p>"The hard part isn't lifting the weights; it's lifting yourself to do it every day." – Unknown</p>
            <p>"It does not matter how slowly you go, as long as you do not stop." – Confucius</p>
            <p>"Success is the sum of small efforts, repeated day in and day out." – Robert Collier</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>© 2025 Working with AI. All rights reserved.</p>
    </footer>

</body>
</html>
# fitness-website
