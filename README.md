# Micjeal.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Software Engineer</title>
    <link rel="stylesheet" href="style.css">
    <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    </head>
    
</head>
<body>
    <header>
        <div class="container">
            <h1>Transform Your Ideas Into Reality</h1>
            <p>Welcome to my software engineering portfolio. Explore my projects, skills, and achievements in building scalable and efficient solutions.</p>
            <div class="buttons">
                <a href="#projects.html" class="btn">Explore Projects</a>
                <a href="#contact" class="btn">Get in Touch</a>
            </div>
        </div>
    </header>
    
    <section id="projects">
        <h2>Top Picks</h2>
        <div class="project-grid">
            <div class="project-card">Web Development</div>
            <div class="project-card">Machine Learning</div>
            <div class="project-card">Database Management</div>
        </div>
    </section>
    
    <section id="about">
        <div class="about-content">
            <img src="IMAGES/IMG-20250101-WA0002.jpg" alt="Profile Picture">
            <div>
                <h2>About Me</h2>
                <p>I am a software engineer passionate about creating impactful solutions. With expertise in various programming languages and tools, I help businesses achieve their goals.</p>
            </div>
        </div>
        <a href="projects.html" class="btn">Explore Projects</a>
    </section>

    <section id="experience">
        <h2>Work Experience</h2>
        <div class="experience-grid">
            <div class="experience-card">
                <h3>HTML</h3>
                <p>Proficient in creating responsive and modern web layouts using semantic HTML and best practices.</p>
            </div>
            <div class="experience-card">
                <h3>SQL</h3>
                <p>Experienced in designing and managing databases, writing optimized queries, and ensuring data integrity.</p>
            </div>
            <div class="experience-card">
                <h3>Java</h3>
                <p>Skilled in developing scalable applications using object-oriented programming and frameworks like Spring.</p>
            </div>
            <div class="experience-card">
                <h3>C#</h3>
                <p>Expertise in building desktop and web applications using .NET, Windows Forms, and WPF frameworks.</p>
            </div>
        </div>
    </section>

    
    
    
    <section id="testimonials">
        <h2>Testimonials</h2>
        <p>Here's what people are saying about me and my work:</p>
        <div class="testimonial-container">
            <div class="testimonial">
                <p class="quote">"Makumbi Kevin is an exceptional software engineer! His attention to detail and dedication to his work is unparalleled."</p>
                <p class="author">- , Senior Developer</p>
            </div>
            <div class="testimonial">
                <p class="quote">"I highly recommend Makumbi Kevin! He delivered top-notch results on our project and exceeded expectations."</p>
                <p class="author">- Mugisha Micheal, WorkMate</p>
            </div>
            <div class="testimonial">
                <p class="quote">"Makumbi's expertise in software engineering is truly impressive. He’s a great problem-solver and team player."</p>
                <p class="author">- Adrodri savi, Tech Lead</p>
            </div>
        </div>
    </section>
  
    <section id="contact">
        <h2>Contact Me</h2>
        <div class="contact-container">
            <!-- Form Section -->
            <form id="contactForm">
                <input type="text" id="name" placeholder="Your Name" required />
                <input type="email" id="email" placeholder="Your Email" required />
                <input type="tel" id="phone" placeholder="Your Phone Number" required />
                <textarea id="message" placeholder="Your Message" rows="4" required></textarea>
                <button type="submit" id="sendButton">Send</button>
            </form>
    
            <!-- Developer Image -->
            <div class="contact-image">
                <img src="IMAGES/IMG-20250101-WA0003.jpg" alt="Developer Image">
            </div>
        </div>
    
        <!-- Submitted Contacts Table -->
        <h3>Submitted Contacts</h3>
        <table id="contactTable">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Email</th>
                    <th>Phone</th>
                    <th>Message</th>
                </tr>
            </thead>
            <tbody>
                <!-- Dynamic entries will populate here -->
            </tbody>
        </table>
    </section>
    
    

    <footer>
        <div class="water-container">
            <div class="drop drop1"></div>
            <div class="drop drop2"></div>
             <div class="drop drop3"></div> 
             <div class="drop drop4"></div> 
             <div class="drop drop5"></div>
       </div>
        <div class="social-icons">
            <a href="https://www.facebook.com/yourprofile" target="_blank" rel="noopener noreferrer"><i class="fab fa-facebook-f"></i></a>
            <a href="https://www.twitter.com/yourprofile" target="_blank" rel="noopener noreferrer"><i class="fab fa-twitter"></i></a>
            <a href="https://www.instagram.com/yourprofile" target="_blank" rel="noopener noreferrer"><i class="fab fa-instagram"></i></a>
            <a href="https://www.linkedin.com/in/yourprofile" target="_blank" rel="noopener noreferrer"><i class="fab fa-linkedin-in"></i></a>
        </div>
        <p>© 2025 Makumbi Kevin. All Rights Reserved.</p>
    </footer>
    
    

    <script src="script.js"></script>
</body>
</html>
