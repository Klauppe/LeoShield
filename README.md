<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leo Shield Law Enforcement Training</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1 class="logo">Leo Shield Law Enforcement Training</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Courses</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a href="#">Login</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Banner Section -->
    <section class="banner">
        <div class="container">
            <h2>Professional Law Enforcement Training</h2>
            <p>Develop the skills you need to succeed in modern law enforcement.</p>
            <a href="#" class="cta-button">Explore Courses</a>
        </div>
    </section>

    <!-- Courses Section -->
    <section class="courses" id="courses">
        <div class="container">
            <h2>Available Courses</h2>
            <div class="course-list">
                <!-- Course 1 -->
                <div class="course-card">
                    <img src="course1.jpg" alt="Course 1">
                    <h3>Crime Scene Investigation</h3>
                    <p>Learn the fundamentals of crime scene analysis and evidence collection.</p>
                    <a href="#" class="course-button">Learn More</a>
                </div>
                <!-- Course 2 -->
                <div class="course-card">
                    <img src="course2.jpg" alt="Course 2">
                    <h3>Defensive Tactics</h3>
                    <p>Master self-defense and control tactics essential for law enforcement.</p>
                    <a href="#" class="course-button">Learn More</a>
                </div>
                <!-- Course 3 -->
                <div class="course-card">
                    <img src="course3.jpg" alt="Course 3">
                    <h3>Community Policing</h3>
                    <p>Build positive relationships with the community you serve.</p>
                    <a href="#" class="course-button">Learn More</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <div class="container">
            <h2>What Our Customers Say</h2>
            <div class="testimonial-list">
                <div class="testimonial">
                    <p>"The best law enforcement training I've ever attended. Highly recommend!"</p>
                    <span>- John D.</span>
                </div>
                <div class="testimonial">
                    <p>"Great instructors and hands-on experience."</p>
                    <span>- Sarah P.</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Law Enforcement Training Institute. All rights reserved.</p>
            <ul>
                <li><a href="#">Privacy Policy</a></li>
                <li><a href="#">Terms of Service</a></li>
            </ul>
        </div>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>

/* Global Styles */
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
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Banner */
.banner {
    background: url('banner.jpg') no-repeat center center/cover;
    color: #fff;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.banner h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.banner .cta-button {
    background-color: #007BFF;
    padding: 15px 30px;
    color: white;
    border: none;
    text-decoration: none;
    font-size: 18px;
    border-radius: 5px;
}

.banner .cta-button:hover {
    background-color: #0056b3;
}

/* Courses Section */
.courses {
    padding: 40px 0;
    background-color: #f9f9f9;
}

.courses .container h2 {
    text-align: center;
    margin-bottom: 40px;
}

.course-list {
    display: flex;
    justify-content: space-between;
}

.course-card {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 30%;
    padding: 20px;
    text-align: center;
}

.course-card img {
    width: 100%;
    border-radius: 8px;
}

.course-card h3 {
    margin: 20px 0;
}

.course-card p {
    color: #666;
}

.course-button {
    background-color: #007BFF;
    padding: 10px 20px;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.course-button:hover {
    background-color: #0056b3;
}

/* Testimonials Section */
.testimonials {
    background-color: #007BFF;
    color: white;
    padding: 40px 0;
    text-align: center;
}

.testimonials h2 {
    margin-bottom: 30px;
}

.testimonial-list {
    display: flex;
    justify-content: space-around;
}

.testimonial {
    width: 45%;
}

.testimonial p {
    font-size: 18px;
}

.testimonial span {
    display: block;
    margin-top: 10px;
    font-style: italic;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

footer ul li {
    margin-left: 20px;
}

footer ul li a {
    color: white;
    text-decoration: none;
}
// scripts.js

// For future functionality (e.g., form validation, interactivity)
document.addEventListener("DOMContentLoaded", function() {
    // Code for interactions, animations, etc.
});
