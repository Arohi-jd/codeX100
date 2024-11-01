<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>codeX100 - Learn Programming</title>

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body style="font-family: 'Poppins', sans-serif; background-color: #f8f9fa; color: #333; margin: 0;">

    <!-- Navigation Bar -->
    <nav style="display: flex; justify-content: space-between; align-items: center; background-color: #343a40; padding: 15px 30px;">
        <div class="logo">
            <a href="index.html">
                <img src="./Images/codex100-logo.png" alt="codeX100 logo" style="height: 40px;" />
            </a>
        </div>
        <div class="hamburger" id="hamburger" style="display: none; font-size: 24px; color: #ffffff;">
            <i class="fas fa-bars"></i>
        </div>
        <ul style="list-style: none; display: flex; margin: 0; padding: 0;">
            <li><a href="#" style="color: #ffffff; text-decoration: none; margin: 0 15px;">Home</a></li>
            <li><a href="course.html" style="color: #ffffff; text-decoration: none; margin: 0 15px;">Courses</a></li>
            <li><a href="#" style="color: #ffffff; text-decoration: none; margin: 0 15px;">Notes</a></li>
            <li><a href="IDE.html" style="color: #ffffff; text-decoration: none; margin: 0 15px;">IDE</a></li>
            <li><a href="contact.html" style="color: #ffffff; text-decoration: none; margin: 0 15px;">Contact Us</a></li>
            <li><a href="#" style="background-color: #f1c40f; color: #343a40; padding: 10px 15px; border-radius: 5px; text-decoration: none; font-weight: bold;">Sign Up</a></li>
            <li><a href="login.html" style="background-color: #f1c40f; color: #343a40; padding: 10px 15px; border-radius: 5px; text-decoration: none; font-weight: bold;">Login</a></li>
        </ul>
    </nav>

    <!-- Main Section -->
    <section style="background: linear-gradient(to right, #007bff, #6610f2); color: #ffffff; padding: 80px 20px; text-align: center;">
        <h2 style="font-size: 2.5rem; margin: 0;">Welcome to codeX100</h2>
        <p style="font-size: 1.25rem;">Master programming with live classes and curated content</p>
        <a href="#" style="background-color: #f1c40f; color: #343a40; padding: 15px 30px; border-radius: 5px; text-decoration: none; font-weight: bold;">Explore Courses</a>
    </section>

    <!-- Course Recommendations Section -->
    <section style="padding: 40px 20px; text-align: center;">
        <h2>Your Courses</h2>
        <div class="course-list">
            <p>You haven't bought any courses yet.</p>
        </div>

        <h3 style="margin-top: 40px;">Recommended Courses</h3>
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
            <!-- Example courses with thumbnails -->
            <div style="background: #ffffff; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; width: 250px; box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); transition: transform 0.2s;">
                <img src="./Images/c++-thumbnail.jpg" alt="Basics of C++" style="width: 100%; border-radius: 8px;" />
                <div style="text-align: left; margin-top: 10px;">
                    <h4 style="font-size: 1.5rem;">Basics of C++</h4>
                    <p>Learn the fundamentals of C++ programming.</p>
                    <button style="background-color: #007bff; color: white; border: none; padding: 10px; border-radius: 5px; cursor: pointer;">View Course</button>
                </div>
            </div>
            <div style="background: #ffffff; border: 1px solid #e0e0e0; border-radius: 8px; padding: 20px; width: 250px; box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); transition: transform 0.2s;">
                <img src="./Images/java-thumbnail.jpg" alt="Data Structures in Java" style="width: 100%; border-radius: 8px;" />
                <div style="text-align: left; margin-top: 10px;">
                    <h4 style="font-size: 1.5rem;">Data Structures in Java</h4>
                    <p>Master DSA with Java from basics to advanced.</p>
                    <button style="background-color: #007bff; color: white; border: none; padding: 10px; border-radius: 5px; cursor: pointer;">View Course</button>
                </div>
            </div>
            <!-- Additional Course Cards -->
        </div>
    </section>

    <!-- Contact Us Section -->
    <section style="background-color: #ffffff; padding: 40px 20px; text-align: center;">
        <h2>Contact Us</h2>
        <p>If you have any questions or need further assistance, feel free to reach out to us.</p>
        <form style="max-width: 500px; margin: 0 auto;">
            <input type="text" placeholder="Your Name" required style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;" />
            <input type="email" placeholder="Your Email" required style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;" />
            <textarea placeholder="Your Message" required style="width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px;"></textarea>
            <button type="submit" style="background-color: #007bff; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer;">Send Message</button>
        </form>
    </section>

    <footer style="background-color: #343a40; color: #ffffff; padding: 20px 0; text-align: center;">
        <div style="display: flex; justify-content: space-around; padding: 20px;">
            <div>
                <h3>Important Links</h3>
                <ul style="list-style: none; padding: 0;">
                    <li><a href="/about" style="color: #ffffff; text-decoration: none;">About Us</a></li>
                    <li><a href="/privacy" style="color: #ffffff; text-decoration: none;">Privacy Policy</a></li>
                    <li><a href="/terms" style="color: #ffffff; text-decoration: none;">Terms of Service</a></li>
                </ul>
            </div>
            <div>
                <h3>Connect With Us</h3>
                <div style="display: flex; justify-content: center;">
                    <a href="https://linkedin.com/" target="_blank" rel="noopener noreferrer" style="margin: 0 10px; color: #ffffff;">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="https://instagram.com/" target="_blank" rel="noopener noreferrer" style="margin: 0 10px; color: #ffffff;">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="https://youtube




