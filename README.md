<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Learning Website</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
        integrity="sha512-Ijmfekeas02rAf+4P4sV5PmFdm5+4GrF3B9Vz1A1k/AbpMv65wVWiLO1T4KxEMBPc0k5jKZTj8cPRp+Q6v8i2Q=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="container">
            <h1 class="logo">E-Learning</h1>
            <ul class="nav-links">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">Courses</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
                <!-- Add more links as needed -->
            </ul>
            <div class="search-box">
                <input type="text" placeholder="Search courses...">
                <button><i class="fas fa-search"></i></button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-text">
                <h1>Welcome to E-Learning Platform</h1>
                <p>Learn anything, anywhere, anytime.</p>
                <a href="#" class="btn">Get Started</a>
            </div>
        </div>
    </section>

    <!-- Courses Section -->
    <section class="courses">
        <div class="container">
            <h2 class="section-title">Popular Courses</h2>
            <div class="course-card">
                <div class="card">
                    <img src="course1.jpg" alt="Course 1">
                    <div class="card-content">
                        <h3>Course Title</h3>
                        <p>Course description goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        <a href="#" class="btn">Enroll Now</a>
                    </div>
                </div>
                <!-- Repeat for more courses -->
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section about">
                    <h1 class="logo">E-Learning</h1>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla placerat, nisl sit amet
                        tincidunt interdum, leo velit lobortis ligula, vel posuere turpis ipsum eu augue.</p>
                    <div class="contact">
                        <span><i class="fas fa-phone"></i> +123 456 789</span>
                        <span><i class="fas fa-envelope"></i> info@elearning.com</span>
                    </div>
                    <div class="socials">
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                    </div>
                </div>
                <div class="footer-section links">
                    <h2>Quick Links</h2>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Courses</a></li>
                        <li><a href="#">About</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-section contact-form">
                    <h2>Contact Us</h2>
                    <form action="#">
                        <input type="email" name="email" class="text-input contact-input" placeholder="Your email address">
                        <textarea rows="4" name="message" class="text-input contact-input"
                            placeholder="Your message"></textarea>
                        <button type="submit" class="btn btn-big">
                            <i class="fas fa-envelope"></i>
                            Send
                        </button>
                    </form>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            &copy; eLearning 2024. All rights reserved.
        </div>
    </footer>

    <!-- Optional JavaScript -->
    <script src="scripts.js"></script>
</body>

</html>
