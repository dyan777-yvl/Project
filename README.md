# Project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <header class="hero">
        <div class="hero-content">
            <div class="hero-text">
                <h1 class="animate-text">John Doe</h1>
                <p class="animate-text delay-1">Full Stack Developer</p>
                <p class="animate-text delay-2">Passionate about creating beautiful & functional web experiences</p>
                <div class="hero-cta animate-text delay-3">
                    <a href="#projects" class="cta-button">View My Work</a>
                    <a href="#contact" class="cta-button outline">Contact Me</a>
                </div>
            </div>
            <div class="hero-image">
                <img src="your-photo.jpg" alt="John Doe" class="profile-img">
            </div>
        </div>
    </header>

    <div class="container">
        <section id="about">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <p>I specialize in building modern web applications using cutting-edge technologies. With 5 years of experience in web development, I focus on creating responsive and user-friendly interfaces.</p>
                <div class="skills">
                    <div class="skill">React</div>
                    <div class="skill">Node.js</div>
                    <div class="skill">TypeScript</div>
                    <div class="skill">MongoDB</div>
                </div>
            </div>
        </section>

        <section id="projects" class="projects">
            <h2 class="section-title">Featured Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <div class="project-image">
                        <img src="project1.jpg" alt="Project 1">
                    </div>
                    <div class="project-content">
                        <h3>E-Commerce Platform</h3>
                        <p>A full-stack e-commerce solution with React and Node.js</p>
                        <div class="project-tags">
                            <span>React</span>
                            <span>Node.js</span>
                            <span>MongoDB</span>
                        </div>
                        <button class="view-more">View Project</button>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <img src="project2.jpg" alt="Project 2">
                    </div>
                    <div class="project-content">
                        <h3>Task Management App</h3>
                        <p>Real-time task management application with collaborative features</p>
                        <div class="project-tags">
                            <span>Vue.js</span>
                            <span>Firebase</span>
                            <span>Tailwind</span>
                        </div>
                        <button class="view-more">View Project</button>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <img src="project3.jpg" alt="Project 3">
                    </div>
                    <div class="project-content">
                        <h3>AI Chat Interface</h3>
                        <p>Modern chat interface with AI integration</p>
                        <div class="project-tags">
                            <span>Next.js</span>
                            <span>OpenAI</span>
                            <span>WebSocket</span>
                        </div>
                        <button class="view-more">View Project</button>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2 class="section-title">Get In Touch</h2>
            <form id="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit" class="submit-btn">Send Message</button>
            </form>
            <div class="social-links">
                <a href="#" class="social-link">LinkedIn</a>
                <a href="#" class="social-link">GitHub</a>
                <a href="#" class="social-link">Twitter</a>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
