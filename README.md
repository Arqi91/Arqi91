
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alrahman Online Shopping Center</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Alrahman Online Shopping Center</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#shop">Shop</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Affordable Prices. Unmatched Quality.</h2>
            <p>Shop now for the best deals on electronics, shoes, clothes, household items, and more.</p>
            <a href="#shop" class="cta-button">Shop Now</a>
        </div>
    </section>

    <section id="shop" class="featured">
        <div class="container">
            <h2>Featured Categories</h2>
            <div class="category">
                <h3>Electronics</h3>
                <p>Discover the latest in tech.</p>
            </div>
            <div class="category">
                <h3>Shoes</h3>
                <p>Find your perfect fit.</p>
            </div>
            <div class="category">
                <h3>Clothes</h3>
                <p>Stay stylish with our collection.</p>
            </div>
            <div class="category">
                <h3>Household Items</h3>
                <p>Essentials for your home.</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>At Alrahman Online Shopping Center, our mission is to provide an easy and affordable online shopping experience with the best quality products.</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:alrahmanshoppingcenter184@gmail.com">alrahmanshoppingcenter184@gmail.com</a></p>
            <p>Phone: <a href="tel:+923288875960">03288875960</a></p>
            <p>WhatsApp: <a href="https://whatsapp.com/channel/0029VaKBfvjEAKWHtc0zl73U">Chat with us on WhatsApp</a></p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Alrahman Online Shopping Center. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
/* Reset some default styles */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Basic styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.container {
    width: 80%;
    margin: 0 auto;
}

/* Header styles */
header {
    background: #fff;
    padding: 20px 0;
    border-bottom: 2px solid #e0e0e0;
}

header h1 {
    margin: 0;
    color: #d32f2f; /* Red color */
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 15px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

/* Hero section styles */
.hero {
    background: #f5f5f5;
    padding: 50px 0;
    text-align: center;
}

.hero h2 {
    color: #d32f2f; /* Red color */
}

.cta-button {
    background: #d32f2f; /* Red color */
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

/* Featured section styles */
.featured {
    padding: 20px 0;
    text-align: center;
}

.category {
    display: inline-block;
    width: 22%;
    margin: 10px 1%;
    background: #fff;
    padding: 20px;
    border: 1px solid #e0e0e0;
    border-radius: 5px;
}

/* About section styles */
.about {
    background: #f5f5f5;
    padding: 20px 0;
    text-align: center;
}

/* Contact section styles */
.contact {
    padding: 20px 0;
    text-align: center;
}

.contact a {
    color: #d32f2f; /* Red color */
}

/* Footer styles */
footer {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}
