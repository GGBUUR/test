---
layout: default
title: About Me
permalink: /about/
---

<!-- Navigation -->
<nav class="navbar">
    <div class="navbar-container">
        <div class="logo">
            <a href="{{ '/' | relative_url }}">Rasul Huseynli</a>
        </div>
        <div class="nav-menu">
            <a href="{{ '/' | relative_url }}" class="nav-link">Home</a>
            <a href="{{ '/about/' | relative_url }}" class="nav-link active">About</a>
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
                    Hello! I'm a dedicated developer with a passion for creating beautiful and functional web applications. 
                    My journey in tech started with curiosity and has evolved into a career focused on solving real-world problems 
                    through innovative solutions.
                </p>
                
                <h2>Background</h2>
                <p>
                    With a strong foundation in computer science and web development, I've worked on diverse projects ranging from 
                    personal portfolios to complex web applications. I believe in continuous learning and staying updated with the 
                    latest technologies and best practices in the industry.
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
