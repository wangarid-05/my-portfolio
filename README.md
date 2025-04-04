index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body>

    <header>
        <h1>DAISY WANGARI</h1>
        <p>Interior Designer | Aspiring Software Engineer</p>
    </header>

    <section id="about">
        <h2><i class="fas fa-user"></i> About Me</h2>
        <p>I am Daisy Wangari, an interior designer with a keen eye for aesthetics and spatial harmony, now channeling that same creativity into the world of software engineering. With nearly three years of experience designing beautiful, functional spaces, I've developed a deep appreciation for structure, design thinking, and user-centered solutions—skills that naturally translate into front-end development and problem-solving in tech. My journey into software engineering is fueled by a love for building, learning, and adapting. Just like designing a space, I enjoy crafting digital experiences that are both elegant and practical.</p>
    </section>

    <section id="education">
        <h2><i class="fas fa-university"></i> Educational Background</h2>
        <ul>
            <li>I hold a Bachelor of Technology in Design, Environmental Design from the Technical University of Kenya.</li>
            <li>Currently pursuing Software Engineering at PLP.</li>
            <li>My academic background has equipped me with strong design, UX, and problem-solving skills.</li>
        </ul>
        <a href="WANGARI DAISY CV.pdf" download class="btn">📄 Download My CV</a>
    </section>

    <section id="interests">
        <h2><i class="fas fa-palette"></i> Interests</h2>
        <ul>
            <li><strong>Interior Design:</strong> Blending aesthetics with functionality.</li>
            <li><strong>3D Modeling & Visualization:</strong> Experimenting with 3D software and coding to bring designs to life.</li>
            <li><strong>UX/UI Design:</strong> Applying design principles to create intuitive interfaces.</li>
            <li><strong>Software Engineering:</strong> Passionate about coding and problem-solving.</li>
            <li><strong>Web Development:</strong> Learning modern frameworks and tools.</li>
            <li><strong>Tech Innovations:</strong> Exploring AI, smart homes, and AR for interiors.</li>
        </ul>
    </section>

    <section id="projects">
        <h2><i class="fas fa-check-circle"></i> Projects</h2>
        <p>Here are some of my projects:</p>
        <div class="project-item">
            <a href="https://sites.google.com/view/wangaridaisy/home" target="_blank">
                <strong>Interior Design Portfolio Website</strong>
            </a>
            <p>Showcasing my design projects, including 3D visualizations and concepts. I'm also working on a web app merging design and software engineering.</p>
        </div>
    </section>

    <section id="contact">
        <h2><i class="fas fa-mail-bulk"></i> Contact Me</h2>
        <p>Feel free to reach out!</p>
        <div class="contact-icons">
            <a href="mailto:wangarid768@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
            <a href="https://linkedin.com/in/wangarid768" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/wangarid-05" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
            <a href="tel:+254743798476" title="Phone"><i class="fas fa-phone"></i></a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Daisy Wangari. All rights reserved.</p>
    </footer>

</body>

syles.css
</ht/* Base Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    background-color: #f9f5ff;
    color: #333;
    padding: 20px;
}

/* Color Palette */
:root {
    --primary-color: #9B59B6;
    --accent-color: #59B69B;
    --light-bg: #fff;
    --dark-text: #333;
}

/* Header */
header {
    text-align: center;
    padding: 40px 10px;
    background-color: var(--primary-color);
    color: white;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2rem;
}

/* Section Styling */
section {
    margin: 40px 0;
    background-color: var(--light-bg);
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 0 10px rgba(155, 89, 182, 0.1);
}

section h2 {
    color: var(--primary-color);
    font-size: 1.8rem;
    margin-bottom: 15px;
}

section ul {
    list-style-type: disc;
    padding-left: 20px;
}

section li {
    margin-bottom: 10px;
}

/* CV Button */
.btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background-color: var(--primary-color);
    color: white;
    text-decoration: none;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.15);
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #884ea0;
}

/* Contact Icons */
.contact-icons {
    margin-top: 15px;
}

.contact-icons a {
    margin-right: 15px;
    font-size: 1.8rem;
    color: var(--primary-color);
    text-decoration: none;
    transition: transform 0.3s, color 0.3s;
}

.contact-icons a:hover {
    color: var(--accent-color);
    transform: scale(1.2);
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    font-size: 0.9rem;
    color: #666;
    border-top: 1px solid #ddd;
    margin-top: 40px;
}

/* Project Link */
.project-item {
    margin-top: 10px;
}

.project-item a {
    color: var(--primary-color);
    font-weight: bold;
    text-decoration: none;
}

.project-item a:hover {
    text-decoration: underline;
}
ml>
