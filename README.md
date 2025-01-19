# Micjeal.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Software Engineer</title>
    <link rel="stylesheet" href="style.css">
    <head>
        <link rel="stylesheet" type="text/css" href="style.css">
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
/* General Reset */
body, h1, h2, p {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Times New Roman', Times, sans-serif;
    line-height: 1.6;
    background-color: #050305; /* Very dark, almost black */
    color: #fff;
}

/* Header Section */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background: #36123F; /* Deep purple */
    color: #fff;
}

header a.logo {
    display: flex;
    align-items: center;
    font-size: 1.5rem;
    font-weight: bold;
    color: #8F37B1; /* Vibrant purple */
    text-decoration: none;
}
header a.logo img {
    margin-right: 10px;
    border-radius: 10px;
    height: 100px; /* Adjust the height as needed */
}

header ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

header ul li a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s;
}

header ul li a:hover {
    color: #8F37B1; /* Vibrant purple */
}

header ul li a.active {
    text-decoration: underline;
}

header .container h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

header .buttons {
    margin-top: 20px;
}

header .btn {
    text-decoration: none;
    color: #8F37B1;
    background: #fff;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 5px;
    transition: 0.3s;
}

header .btn:hover {
    background: #eee;
}

/* Navigation */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background: #050305; /* Very dark color */
    color: #fff;
}

nav a.logo {
    font-size: 1.8rem;
    font-weight: bold;
    color: #8F37B1; /* Vibrant purple */
    text-decoration: none;
    transition: color 0.3s ease;
}

nav a.logo:hover {
    color: #624343; /* Muted brownish color */
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li {
    position: relative;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
    padding: 5px 10px;
    border-radius: 4px;
    transition: all 0.3s ease;
}

nav ul li a:hover,
nav ul li a.active {
    background: #1d1221; /* Vibrant purple */
    color: #fff;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3); /* Subtle shadow effect */
}

/* Button Styling */
.btn {
    display: inline-block;
    padding: 12px 25px; /* Adjust padding for a well-defined shape */
    font-size: 1rem;
    font-weight: bold;
    color: #fff;
    background: #8F37B1; /* Vibrant purple color */
    text-decoration: none;
    border-radius: 15px; /* Rounded corners for a pill-shaped button */
    transition: all 0.3s ease;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Subtle shadow for depth */
}

.btn:hover {
    background: #624343; /* Muted brownish color for hover effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3); /* Enhance shadow on hover */
    transform: translateY(-2px); /* Slight lift effect */
}

.btn:active {
    background: #36123F; /* Deep purple for active state */
    box-shadow: 0 3px 6px rgba(0, 0, 0, 0.2); /* Reduced shadow for active state */
    transform: translateY(2px); /* Slight press effect */
}

/* About Section */
#about {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 40px 20px;
    text-align: center;
    background: #624343; /* Muted brownish */
}

#about img {
    width: 150px;
    border-radius: 50%;
    margin-right: 20px;
    border: 3px solid #8F37B1; /* Vibrant purple */
}

#about h2 {
    margin-bottom: 10px;
    color: #fff;
}

/* Projects Section */
#projects {
    padding: 40px 20px;
    text-align: center;
    background: #36123F; /* Deep purple */
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.project-card {
    padding: 20px;
    background: #624343; /* Muted brownish */
    border: 1px solid #8F37B1; /* Vibrant purple */
    border-radius: 5px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
    text-align: center;
}

.project-card h2 {
    font-size: 1.5rem;
    margin-bottom: 10px;
    color: #fff;
}

.project-card p {
    margin-bottom: 15px;
    color: #f0f0f0;
}

.project-card .btn {
    padding: 10px 15px;
    background: #8F37B1; /* Vibrant purple */
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s;
}

.project-card .btn:hover {
    background: #36123F; /* Deep purple */
}

.hover-content {
    display: none;
    text-align: left;
    margin-top: 10px;
    opacity: 0;
    transition: opacity 0.5s ease-in-out;
}

.project-card:hover .hover-content {
    display: block;
    opacity: 1;
}

.project-card:not(:hover) .hover-content {
    transition-delay: 0.5s;
    opacity: 0;
}

.hover-content img {
    max-width: 100%;
    border-radius: 5px;
    margin-bottom: 10px;
}

.hover-content p {
    color: #fff;
    margin-bottom: 10px;
}

/* Work Experience Section */
#experience {
    padding: 40px 20px;
    background: #050305; /* Very dark, almost black */
    text-align: center;
}

#experience h2 {
    margin-bottom: 20px;
    color: #8F37B1; /* Vibrant purple */
}

.experience-grid {
    display: flex;
    gap: 20px;
    justify-content: center;
    flex-wrap: wrap;
}

.experience-card {
    background: #624343; /* Muted brownish */
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    flex: 1;
    max-width: 300px;
    text-align: left;
}

.experience-card h3 {
    color: #fff; /* Vibrant purple */
    margin-bottom: 10px;
}

.experience-card p {
    color: #f0f0f0;
}

/* Contact Section */
#contact {
    padding: 40px 20px;
    background: #36123F; /* Deep purple */
    color: #fff;
    text-align: center;
}

#contact h2 {
    margin-bottom: 20px;
    font-size: 2rem;
    color: #8F37B1; /* Vibrant purple */
}

.contact-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 20px;
    margin-bottom: 30px;
}

/* Form Styling */
#contactForm {
    flex: 1 1 400px;
    max-width: 600px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

#contactForm input,
#contactForm textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #624343; /* Muted brownish */
    border-radius: 5px;
    background: #050305; /* Very dark */
    color: #fff;
}

#contactForm button {
    padding: 10px 20px;
    background-color: #8F37B1; /* Vibrant purple */
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    color: #fff;
}

#contactForm button:hover {
    background-color: #624343; /* Muted brownish */
}

/* Developer Image Styling */
.contact-image {
    flex: 1 1 300px;
    text-align: center;
}

.contact-image img {
    width: 100%;
    max-width: 250px;
    border-radius: 50%;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

/* Contact Table */
#contactTable {
    margin-top: 20px;
    width: 100%;
    border-collapse: collapse;
    background: #050305; /* Dark table background */
}

#contactTable th,
#contactTable td {
    padding: 10px;
    border: 1px solid #624343;
    text-align: left;
}

#contactTable th {
    background: #8F37B1; /* Vibrant purple */
    color: #fff;
}

/* Responsive Design */
@media (max-width: 768px) {
    .header {
        flex-direction: column;
        align-items: flex-start;
    }

    header ul {
        flex-direction: column;
        align-items: flex-start;
        gap: 10px;
    }

    .project-grid {
        grid-template-columns: 1fr;
    }

    .experience-grid {
        flex-direction: column;
    }

    .contact-container {
        flex-direction: column;
    }

    .contact-image {
        order: -1; /* Move image above the form on small screens */
    }
}

/* Testimonials Section */
#testimonials {
    padding: 40px 20px;
    background: #624343; /* Muted brownish */
    color: #fff;
    text-align: center;
}

#testimonials h2 {
    margin-bottom: 10px;
    color: #fff; /* Vibrant purple */
}

.testimonial-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.testimonial {
    background: #36123F; /* Deep purple */
    color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    max-width: 300px;
    flex: 1 1 300px;
    text-align: left;
}

.testimonial .quote {
    font-style: italic;
    margin-bottom: 10px;
}

.testimonial .author {
    font-weight: bold;
    text-align: right;
}

/* Footer */
footer {
    background: black; /* Very dark, almost black */
    color: #fff;
    text-align: center;
    padding: 20px 0;
    position: relative;
}

.social-icons {
    margin-bottom: 10px;
}

.social-icons a {
    color: #fff;
    margin: 0 10px;
    font-size: 20px;
    transition: color 0.3s;
}

.social-icons a:hover {
    color: #8F37B1; /* Vibrant purple */
}

/* Footer Water Drop Effect */
/* Footer Water Drop Effect */
.water-container {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 50px;
    overflow: hidden;
    background: transparent;
    z-index: 1;
}

.drop {
    position: absolute;
    top: -10px;
    width: 15px; 
    height: 10px;
    background: #00bfff; /* Water color */
    border-radius: 50%;
    animation: drop 2s infinite;
}

.drop::after {
    content: '';
    position: absolute;
    top: 5px;
    left: 10px;
    width: 10px;
    height: 5px;
    background: #00bfff; /* Water color */
    border-radius: 50%;
}

.drop1 {
    left: 20%;
    animation-delay: 0.5s;
}

.drop2 {
    left: 40%;
    animation-delay: 1s;
}

.drop3 {
    left: 60%;
    animation-delay: 1.5s;
}

.drop4 {
    left: 80%;
    animation-delay: 2s;
}

.drop5 {
    left: 90%;
    animation-delay: 2.5s;
}

@keyframes drop {
    0% {
        top: -10px;
        opacity: 0;
    }
    50% {
        top: 20px;
        opacity: 1;
    }
    100% {
        top: 50px;
        opacity: 0;
    }
}





