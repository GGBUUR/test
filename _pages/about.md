---
layout: default
title: About Me
permalink: /test/about/
---

<!-- Navigation -->
<nav class="navbar">
    <div class="navbar-container">
        <div class="logo">
            <a href="{{ '/test/' | relative_url }}">Rasul Huseynli</a>
        </div>
        <div class="nav-menu">
            <a href="{{ '/test/' | relative_url }}" class="nav-link">Home</a>
            <a href="{{ '/about/' | relative_url }}" class="nav-link">About</a>
            <a href="{{ '/projects/' | relative_url }}" class="nav-link">Projects</a>
            <a href="{{ '/contact/' | relative_url }}" class="nav-link">Contact</a>
        </div>
        <div class="hamburger">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </div>
</nav>

<!-- About Section -->
<section class="about-section">
    <div class="container">
        <h1>About Me</h1>
        
        <div class="about-content">
            <div class="about-text">
                <h2>Who I Am</h2>
                <p>
                    Hello! I am a student at ADA University, studying Information Technologies. I am passionate about technology, programming, and problem-solving. I enjoy writing code and learning how software systems work. In my free time, I play chess, which helps me improve my logical thinking and focus. I am constantly developing my skills and aiming to become a strong software developer.
                </p>
                
                <h2>Background</h2>
                <p>
                    I am a junior IT student with a strong interest in web development and technology. I have been interested in programming since 2019 and received my first Python certificate in 2020. My most recent certification was in JavaScript in 2025. I enjoy building websites and working on practical projects that strengthen my skills. As part of my learning journey, I have completed several projects, including a website for lawyer services (lawyer rental/booking platform) and a simple game inspired by Tetris, which I called "Go Go Snake." I am continuously improving my technical abilities through both academic and personal development.
                </p>
                
                <h2>Qualifications</h2>
                <ul class="qualifications-list">
                    <li><strong>Web Development:</strong> HTML, CSS, JavaScript, React, Node.js</li>
                    <li><strong>Full Stack:</strong> Frontend and Backend Development</li>
                    <li><strong>Tools & Platforms:</strong> Git, GitHub, VS Code, Docker</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="footer">
    <div class="footer-container">
        <div class="footer-content">
            <div class="footer-section">
                <h4>Portfolio</h4>
                <p>A collection of my work and passion projects.</p>
            </div>
            <div class="footer-section">
                <h4>Links</h4>
                <ul>
                    <li><a href="{{ '/' | relative_url }}">Home</a></li>
                    <li><a href="{{ '/about/' | relative_url }}">About</a></li>
                    <li><a href="{{ '/projects/' | relative_url }}">Projects</a></li>
                    <li><a href="{{ '/contact/' | relative_url }}">Contact</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>Connect</h4>
                <div class="footer-social">
                    <a href="https://github.com/GGBUUR" target="_blank" title="GitHub">
                        <i class="fab fa-github"></i>
                    </a>
                    <a href="https://codecademy.com/profiles/rhuseynli25808" target="_blank" title="Codecademy">
                        <i class="fab fa-code"></i>
                    </a>
                </div>
            </div>
            <div class="footer-section">
                <h4>Repository</h4>
                <p><a href="https://github.com/GGBUUR/test" target="_blank" class="repo-link">
                    View on GitHub <i class="fas fa-external-link-alt"></i>
                </a></p>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2025 My Portfolio. All rights reserved.</p>
        </div>
    </div>
</footer>
