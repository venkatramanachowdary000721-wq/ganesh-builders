# ganesh-builders
Builds buildings according to your plans
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ram Babu Builders</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}

/* Header */
header {
    background: #111;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
}

header h1 {
    color: #00c3ff;
}

nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
}

/* Hero */
.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1503387762-592deb58ef4e') no-repeat center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

.btn {
    background: #00c3ff;
    padding: 10px 20px;
    text-decoration: none;
    color: black;
}

/* Sections */
section {
    padding: 50px;
    text-align: center;
}

/* Services */
.services {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.card {
    background: #f4f4f4;
    margin: 10px;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
}

/* Gallery */
.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.gallery img {
    width: 200px;
    margin: 10px;
    border-radius: 10px;
}

/* Pricing */
.pricing {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.plan {
    background: #f4f4f4;
    margin: 10px;
    padding: 20px;
    width: 220px;
    border-radius: 10px;
}

/* Booking */
.booking input, .booking button {
    padding: 10px;
    margin: 10px;
    width: 250px;
}

/* Footer */
footer {
    background: #111;
    color: white;
    padding: 15px;
}

/* WhatsApp Button */
.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25D366;
    color: white;
    padding: 15px;
    border-radius: 50%;
    text-decoration: none;
    font-size: 20px;
}
</style>
</head>

<body>

<header>
    <h1>Ram Babu Builders</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#pricing">Pricing</a>
        <a href="#booking">Book</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">
    <div>
        <h2>Building Your Dream Spaces</h2>
        <p>Houses | Apartments | Commercial Buildings</p>
        <a href="#booking" class="btn">Book Consultation</a>
    </div>
</section>

<section id="services">
    <h2>Our Services</h2>
    <p>Serving across Andhra Pradesh & Telangana</p>
    <div class="services">
        <div class="card">House Construction</div>
        <div class="card">Apartments</div>
        <div class="card">Commercial Buildings</div>
    </div>
</section>

<section id="gallery">
    <h2>Our Projects</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/200">
        <img src="https://via.placeholder.com/200">
        <img src="https://via.placeholder.com/200">
    </div>
</section>

<section id="pricing">
    <h2>Pricing Plans</h2>
    <div class="pricing">
        <div class="plan">
            <h3>Basic</h3>
            <p>₹3,000</p>
        </div>
        <div class="plan">
            <h3>Standard</h3>
            <p>₹7,000</p>
        </div>
        <div class="plan">
            <h3>Premium</h3>
            <p>₹15,000</p>
        </div>
    </div>
</section>

<section id="booking" class="booking">
    <h2>Book 1-Hour Consultation</h2>
    <p>Available: 11 AM – 1 PM</p>
    <form>
        <input type="text" placeholder="Your Name"><br>
        <input type="tel" placeholder="Phone Number"><br>
        <input type="date"><br>
        <input type="time"><br>
        <button>Book Now</button>
    </form>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>📞 +91 78423 34392</p>
    <p>📍 Parvath Nagar</p>
    <p>⏰ 8 AM – 8 PM</p>
    <p>📷 Instagram: @they_call_me_karna</p>

    <h3>Location Map</h3>
    <iframe src="https://www.google.com/maps?q=Hyderabad&output=embed"
    width="100%" height="300"></iframe>
</section>

<footer>
    <p>© 2026 Ram Babu Builders</p>
</footer>

<a href="https://wa.me/917842334392" class="whatsapp">💬</a>

</body>
</html>
