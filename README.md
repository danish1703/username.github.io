<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danish Ali Portfolio</title>
    <style>
        /* Reset styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #F4F4F9;
            color: #333;
            line-height: 1.6;
        }

        /* Navbar styles */
        nav {  
            background-color: #333;
            padding: 10px 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #00bcd4;
        }

        /* Hero section */
        .hero {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        .hero h2 {
            font-size: 48px;
        }

        .hero p {
            font-size: 20px;
            margin: 20px 0;
        }

        .hero button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: #00bcd4;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        .hero button:hover {
            background-color: #008c9e;
        }

        /* Section container styling */
        .section {
            padding: 40px 20px;
            margin: 20px;
            border: 2px solid #ddd;
            border-radius: 10px;
            background-color: white;
        }

        /* Section headings */
        h2 {
            text-align: center;
            font-size: 32px;
            text-decoration: underline;
            margin-bottom: 20px;
        }

        /* About section */
        .about p {
            font-size: 18px;
            line-height: 1.8;
            text-align: center;
        }

        /* Projects section */
        .projects .project-item {
            margin: 20px 0;
        }

        .projects .project-item h3 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #003366;
        }

        .projects .project-item p {
            font-size: 16px;
            line-height: 1.5;
            margin-bottom: 10px;
        }

        .projects .project-item a {
            color: #00bcd4;
            text-decoration: none;
            font-weight: bold;
        }

        .projects .project-item a:hover {
            text-decoration: underline;
        }

        /* Contact section */
        .contact form {
            max-width: 600px;
            margin: 0 auto;
            text-align: center;
        }

        .contact input,
        .contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact button {
            padding: 10px 20px;
            background-color: #003366;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        .contact button:hover {
            background-color: #00bcd4;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        footer p {
            font-size: 14px;
        }
        /* Download CV Section */
        .download-cv {
            padding: 40px 20px;
            text-align: center;
            background-color: #e9f7fc;
        }
        .download-cv button {
            padding: 10px 20px;
            background-color: #00bcd4;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 18px;
            border-radius: 5px;
        }
        .download-cv button:hover {
            background-color: #008c9e;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h2>Hi, I'm Danish Ali</h2>
        <p>A passionate Software Engineer building innovative solutions.</p>
        <button onclick="window.location.href='#contact';">Get in Touch</button>
    </section>

    <!-- About Section -->
    <section class="section about" id="about">
        <h2>About Me</h2>
        <p>
            I am a software engineering student with a strong foundation in web development, problem-solving, and creativity.
            My goal is to create impactful applications that improve lives and businesses.
        </p>
    </section>

    <!-- Projects Section -->
    <section class="section projects" id="projects">
        <h2>Projects</h2>
        <div class="project-item">
          <img src="https://i.postimg.cc/DZvmFBNq/freepik-candid-image-photography-natural-textures-highly-r-1481.jpg" alt="Image Description" width="270" height="180">

            <h3>Task Management App</h3>
            <p>
                A web application designed to help users efficiently organize their tasks and track progress. This project
                integrates features like adding tasks, setting deadlines, and progress tracking. Visit the project 
                <a href="https://example.com" target="_blank">here</a>.
            </p>
        </div>
        <div class="project-item">
                     <img src="https://i.postimg.cc/brdJSdpr/images-16.jpg" alt="Image Description" width="270" height="180">

            <h3>Portfolio Website</h3>
            <p>
                A personal portfolio showcasing my skills, experiences, and projects in software development. This site
                demonstrates my expertise in responsive design and web development. Visit the project 
                <a href="https://example.com" target="_blank">here</a>.
            </p>
        </div>
    </section>
    <!-- Download CV Section -->
    <section class="download-cv">
        <h2>Download My CV</h2>
        <p>Click the button below to download my CV.</p>
        <button onclick="window.open('https://drive.google.com/uc?export=download&id=18mWczLih0KewWG0NSUH5vTzuF8qgEfWb')">Download CV</button>
    </section>

    <!-- Contact Section -->
    <section class="section contact" id="contact">
        <h2>Contact Me</h2>
        <form action="https://formsubmit.co/your-email@example.com" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Danish Ali. All rights reserved.</p>
    </footer>

</body>
</html>

