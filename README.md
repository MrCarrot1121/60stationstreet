# 60stationstreet
FOOD
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>60 Station Street</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            font-family: 'Georgia', serif;
            background-color: #fafafa;
            color: #000000;
            line-height: 1.75;               /* tightened for mobile */
            font-size: 0.75rem;              /* smaller base on mobile */
            letter-spacing: 0.02em;
            font-weight: 300;
        }
        header {
            background-color: #000000;
            color: #f5f5f5;
            text-align: center;
            padding: 9rem 1.5rem 6rem;
        }
        header h1 {
            font-size: 1.7rem;
            margin-bottom: 1.2rem;
            letter-spacing: 0.10em;
            font-weight: 400;
        }
        header p {
            font-size: 0.8rem;
            opacity: 0.85;
            max-width: 480px;
            margin: 0 auto;
            letter-spacing: 0.05em;
        }
        .hero {
            position: relative;
            height: 65vh;
            min-height: 480px;
            overflow: hidden;
        }
        .hero img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: grayscale(100%) contrast(1.1) brightness(0.9);
            display: block;
        }
        .hero-overlay {
            position: absolute;
            inset: 0;
            background: rgba(0, 0, 0, 0.5);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: #ffffff;
            text-align: center;
            padding: 2rem;
        }
        .hero h2 {
            font-size: 1.6rem;
            margin-bottom: 1.2rem;
            letter-spacing: 0.07em;
            max-width: 720px;
        }
        .hero p {
            font-size: 0.95rem;
            max-width: 680px;
            font-style: italic;
            opacity: 0.95;
        }
        section {
            padding: 9rem 2.5rem;
            max-width: 960px;
            margin: 0 auto;
        }
        #story { background-color: #111111; color: #ffffff; }
        #menu   { background-color: #ffffff; color: #000000; }
        #reservations { background-color: #f2f2f2; color: #0d0d0d; }
        h2 {
            font-size: 1.25rem;
            color: inherit;
            border-bottom: 1px solid #cccccc;
            padding-bottom: 1.4rem;
            margin-bottom: 4rem;
            letter-spacing: 0.07em;
            font-weight: 500;
        }
        h3 {
            font-size: 0.95rem;
            margin: 5rem 0 2rem;
            color: inherit;
            letter-spacing: 0.08em;
            font-weight: 600;
            text-transform: uppercase;
        }
        .menu-category {
            max-width: 720px;
            margin: 0 auto 6rem auto;
            text-align: left;
        }
        .menu-item {
            margin-bottom: 3.2rem;
            padding-bottom: 2.2rem;
            border-bottom: 1px solid #dddddd;
        }
        .menu-item:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }
        .menu-item h4 {
            font-size: 0.92rem;
            font-weight: 600;
            letter-spacing: 0.06em;
            margin-bottom: 0.6rem;
            color: inherit;
        }
        .menu-item p {
            font-size: 0.75rem;
            font-style: italic;
            color: #444444;
            margin: 0;
            line-height: 1.9;
        }
        form {
            background: #ffffff;
            padding: 3.5rem 2.5rem;
            border-radius: 6px;
            box-shadow: 0 10px 60px rgba(0,0,0,0.05);
            max-width: 640px;
            margin: 5rem auto 0;
        }
        label {
            display: block;
            font-weight: 500;
            margin: 2rem 0 0.9rem;
            font-size: 0.88rem;
            letter-spacing: 0.03em;
            color: inherit;
        }
        input, select, textarea {
            width: 100%;
            padding: 1.1rem;
            font-size: 0.88rem;
            border: 1px solid #bbbbbb;
            border-radius: 4px;
            background: #fcfcfc;
            font-weight: 300;
            color: #000000;
        }
        textarea { min-height: 140px; resize: vertical; }
        button {
            width: 100%;
            background: #000000;
            color: #f5f5f5;
            border: none;
            padding: 1.4rem;
            font-size: 0.95rem;
            border-radius: 4px;
            margin-top: 3.5rem;
            cursor: pointer;
            letter-spacing: 0.06em;
            font-weight: 500;
        }
        button:hover { background: #222222; }
        footer {
            background: #000000;
            color: #999999;
            text-align: center;
            padding: 5rem 1rem;
            margin-top: 10rem;
            font-size: 0.78rem;
            letter-spacing: 0.05em;
        }

        @media (min-width: 768px) {
            body { font-size: 0.825rem; }
            header h1 { font-size: 2.6rem; }
            .hero h2 { font-size: 2.2rem; }
            .hero p { font-size: 1.15rem; }
            h2 { font-size: 1.65rem; }
            h3 { font-size: 1.15rem; }
            .menu-item h4 { font-size: 1.05rem; }
            .menu-item p { font-size: 0.825rem; }
            .menu-category { max-width: 900px; }
            section { padding: 12rem 6rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>60 Station Street</h1>
        <p>Private house dinners • Reservations only</p>
    </header>

    <div class="hero">
        <img src="YOUR_GROUP_PHOTO_DIRECT_URL_HERE.jpg" alt="Friends gathering at 60 Station Street">
        <div class="hero-overlay">
            <h2>We create a home-like friend gathering experience through amazing food</h2>
            <p>As a university student who loves food, I believe food is one of my love languages. I hope everyone who comes here feels at home — like a warm gathering of friends, not just a place to eat and leave.</p>
        </div>
    </div>

    <section id="story">
        <h2>Our Background</h2>
        <p>Welcome to 60 Station Street — an intimate private house restaurant where every detail is considered, and every meal unfolds quietly and with care.</p>
        <p>Reservations only. What began as private family gatherings has become a discreet space for a few guests to share thoughtful food in an unhurried atmosphere.</p>
        <p>Join us for an evening of understated elegance.</p>
    </section>

    <section id="menu">
        <h2>Our Food</h2>
        <p>A considered selection of dishes, drawn from Korean traditions, Italian restraint, Taiwanese comfort, French technique, and daily inspiration.</p>

        <div class="menu-category">
            <h3>Appetizers</h3>
            <div class="menu-item">
                <h4>Charcuterie & Cheese</h4>
                <p>Selected cured meats, farmhouse cheeses, seasonal fruits</p>
            </div>
            <div class="menu-item">
                <h4>Tomato Soup with Grilled Cheese</h4>
                <p>Slow-roasted tomatoes, aged cheddar, crisp sourdough</p>
            </div>
            <div class="menu-item">
                <h4>Creamy Vegetable Broth</h4>
                <p>Root vegetables, gentle herbs, toasted garlic</p>
            </div>
            <div class="menu-item">
                <h4>Chinese Steamed Eggs</h4>
                <p>Silky custard, shrimp, scallion, light soy</p>
            </div>
        </div>

        <div class="menu-category">
            <h3>Mains</h3>
            <div class="menu-item">
                <h4>Stir-Fried Glass Noodles</h4>
                <p>Seasonal vegetables, tender beef, toasted sesame</p>
            </div>
            <div class="menu-item">
                <h4>Beef & Radish Noodle Soup</h4>
                <p>Slow-simmered broth, braised short rib, daikon</p>
            </div>
            <div class="menu-item">
                <h4>Creamy Pancetta Pasta</h4>
                <p>Guanciale, black pepper, aged pecorino</p>
            </div>
            <div class="menu-item">
                <h4>Creamy Chicken Mushroom Pasta</h4>
                <p>Free-range chicken, wild mushrooms, thyme cream</p>
            </div>
            <div class="menu-item">
                <h4>Chinese Aubergine with Minced Pork</h4>
                <p>Eggplant, house-ground pork, garlic & chili</p>
            </div>
            <div class="menu-item">
                <h4>Taiwanese Braised Pork</h4>
                <p>Pork belly, five-spice, soft-boiled egg, rice</p>
            </div>
            <div class="menu-item">
                <h4>Duck Confit with Smashed Potato</h4>
                <p>Slow-confit leg, crispy skin, herb-infused potato</p>
            </div>
            <div class="menu-item">
                <h4>Tteokbokki</h4>
                <p>Rice cakes, gochujang, fish cake, sesame</p>
            </div>
        </div>

        <div class="menu-category">
            <h3>Desserts</h3>
            <div class="menu-item">
                <h4>Strawberry Cream Cake</h4>
                <p>Light genoise, fresh strawberries, chantilly</p>
            </div>
            <div class="menu-item">
                <h4>Tiramisu</h4>
                <p>Coffee-soaked ladyfingers, mascarpone, cocoa</p>
            </div>
            <div class="menu-item">
                <h4>Matcha Tarta de Queso</h4>
                <p>Burnt Basque cheesecake, ceremonial-grade matcha</p>
            </div>
        </div>

        <div class="menu-category">
            <h3>Beverage Pairings</h3>
            <p>Curated wines and loose-leaf teas — green, oolong, herbal, black — selected to complement the courses. Preferences noted upon reservation.</p>
        </div>
    </section>

    <section id="reservations">
        <h2>Reservations</h2>
        <p>Share your preferred date, time, number of guests, and any thoughts on food or beverage pairings. We will confirm promptly.</p>

        <form action="https://formspree.io/your-email@example.com" method="POST">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required placeholder="">

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required placeholder="">

            <label for="date">Preferred Date</label>
            <input type="date" id="date" name="date" required>

            <label for="time">Preferred Time</label>
            <input type="time" id="time" name="time" required>

            <label for="guests">Number of Guests</label>
            <select id="guests" name="guests" required>
                <option value=""></option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5+">5+</option>
            </select>

            <label for="food-request">Food Thoughts</label>
            <textarea id="food-request" name="food-request" rows="3" placeholder=""></textarea>

            <label for="pairing">Pairing Interest</label>
            <select id="pairing" name="pairing">
                <option value="None">None</option>
                <option value="Wine">Wine</option>
                <option value="Tea">Tea</option>
                <option value="Both">Both</option>
                <option value="Surprise">Surprise me</option>
            </select>

            <label for="allergies">Notes / Preferences</label>
            <textarea id="allergies" name="allergies" rows="3" placeholder=""></textarea>

            <button type="submit">Request Reservation</button>
        </form>
    </section>

    <footer>
        <p>© 2026 60 Station Street</p>
    </footer>

</body>
</html>
