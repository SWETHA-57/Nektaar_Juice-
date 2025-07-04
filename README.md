# Nektaar_Juice-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Nektaar – The Juice with Personality! 🧃✨</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #fff5e6, #ffe0f0);
            color: #333;
        }
        header {
            background-color: #ff7f50;
            color: white;
            text-align: center;
            padding: 6rem 1rem;
        }
        header h1 {
            font-size: 3.5rem;
            font-weight: bold;
        }
        header p {
            font-size: 1.5rem;
            margin-top: 1rem;
        }
        nav {
            background: #ff7f50;
            display: flex;
            justify-content: center;
            gap: 2rem;
            padding: 1rem;
            font-size: 1.1rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #f1c40f;
        }
        section {
            padding: 3rem 2rem;
        }
        .juice-info {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .juice-card {
            flex: 1 1 300px;
            background: #ffffff;
            border-radius: 15px;
            padding: 1.5rem;
            box-shadow: 0 8px 15px rgba(0,0,0,0.15);
            transition: transform 0.3s;
        }
        .juice-card:hover {
            transform: translateY(-5px);
        }
        .juice-card h2 {
            color: #e67e22;
            margin-top: 0.5rem;
        }
        .juice-card ul {
            list-style-type: square;
            padding-left: 1.2rem;
        }
        .juice-card img.main-image {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 1rem;
            object-fit: cover;
            height: 200px;
        }
        .fruit-icons {
            display: flex;
            gap: 10px;
            margin-bottom: 1rem;
            justify-content: center;
        }
        .fruit-icons img {
            width: 40px;
            height: 40px;
            object-fit: cover;
            border-radius: 50%;
            box-shadow: 0 2px 6px rgba(0,0,0,0.15);
        }
        #about, #contact {
            background: #fef9e7;
            border-top: 5px solid #f39c12;
        }
        #about h2, #contact h2 {
            color: #d35400;
            text-align: center;
        }
        #about p, #contact p {
            font-size: 1.1rem;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background: #ff7f50;
            color: white;
            text-align: center;
            padding: 1.5rem;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Nektaar 🍹</h1>
        <p>The juice that’s not just a drink, but a vibe! 🎉</p>
    </header>

    <nav>
        <a href="#home">Home 🏠</a>
        <a href="#about">About Us 👋</a>
        <a href="#contact">Contact Us 📞</a>
    </nav>

    <section id="home">
        <div class="juice-info">
            <!-- Lemon + Ginger + Amla -->
            <div class="juice-card">
                <img class="main-image" src="https://cdn.pixabay.com/photo/2017/01/20/00/30/lemonade-1994973_1280.jpg" alt="Lemon Juice" />
                <div class="fruit-icons">
                    <img src="https://cdn.pixabay.com/photo/2016/11/29/03/10/lemon-1869537_1280.jpg" alt="Lemon" title="Lemon" />
                    <img src="https://cdn.pixabay.com/photo/2018/05/17/15/04/ginger-3409258_1280.jpg" alt="Ginger" title="Ginger" />
                    <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Indian_gooseberry_aka_Amla_fruit.JPG" alt="Amla" title="Amla" />
                </div>
                <h2>🍋 Lemon + Ginger + Amla</h2>
                <ul>
                    <li>Rich in Vitamin C – Boosts immunity and promotes glowing skin. ✨</li>
                    <li>Powerful Antioxidants – Fights free radicals and reduces cell damage. 💪</li>
                    <li>Aids Digestion – Supports gut health and relieves bloating. 😌</li>
                    <li>Regulates Blood Sugar – Helps control sugar levels naturally. 🩺</li>
                    <li>Detoxifies the Body – Flushes out toxins and improves liver function. 🚿</li>
                </ul>
            </div>

            <!-- Pineapple -->
            <div class="juice-card">
                <img class="main-image" src="https://cdn.pixabay.com/photo/2017/04/04/19/45/pineapple-2203564_1280.jpg" alt="Pineapple Juice" />
                <div class="fruit-icons">
                    <img src="https://cdn.pixabay.com/photo/2016/11/18/16/04/pineapple-1837431_1280.jpg" alt="Pineapple" title="Pineapple" />
                </div>
                <h2>🍍 Pineapple</h2>
                <ul>
                    <li>Rich in Vitamin C – Strengthens immunity and promotes healthy skin. 🌟</li>
                    <li>Aids Digestion – Contains bromelain, which helps break down proteins. 🍽</li>
                    <li>Supports Hydration – High water content keeps the body refreshed. 💧</li>
                    <li>Boosts Eye Health – Contains beta-carotene and antioxidants for vision. 👁</li>
                    <li>Anti-Inflammatory Properties – Helps reduce swelling and joint pain. 🧘</li>
                </ul>
            </div>

            <!-- Mixed Berries -->
            <div class="juice-card">
                <img class="main-image" src="https://cdn.pixabay.com/photo/2017/01/20/00/30/strawberry-smoothie-1994974_1280.jpg" alt="Mixed Berries Juice" />
                <div class="fruit-icons">
                    <img src="https://cdn.pixabay.com/photo/2016/03/05/19/02/strawberry-1238253_1280.jpg" alt="Strawberry" title="Strawberry" />
                    <img src="https://cdn.pixabay.com/photo/2018/08/07/23/03/blueberries-3593380_1280.jpg" alt="Blueberry" title="Blueberry" />
                    <img src="https://cdn.pixabay.com/photo/2016/07/14/08/53/raspberry-1516864_1280.jpg" alt="Raspberry" title="Raspberry" />
                </div>
                <h2>🍓 Mixed Berries</h2>
                <ul>
                    <li>High in Antioxidants – Protects against cell damage and aging. 🍇</li>
                    <li>Boosts Brain Health – Improves memory and cognitive function. 🧠</li>
                    <li>Heart Healthy – Lowers cholesterol and supports circulation. ❤</li>
                    <li>Natural Sweetness – Deliciously fruity with no added sugars. 🍒</li>
                    <li>Vitamin-Packed – Loaded with C, K, and folate. 🥝</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us 🙌</h2>
        <p>Nektaar is more than just a juice supplier. We’re about creating refreshing moments that connect with your soul. 🧡 Made with pure, natural ingredients and no artificial additives, each sip is a celebration of flavor and wellness. 🍹 Our mission is to make drinks that are as vibrant and unforgettable as you are! 🎯</p>
    </section>

    <section id="contact">
        <h2>Contact Us 📬</h2>
        <p>Email: 📧 hello@nektaar.com</p>
        <p>Phone: 📱 +91-9876543210</p>
        <p>Address: 📍 Nektaar Beverages, Hyderabad, India</p>
    </section>

    <footer>
        <p>&copy; 2025 Nektaar. All rights reserved. 🧃🌟</p>
    </footer>
</body>
</html>
