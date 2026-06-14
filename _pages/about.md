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
                    Hello! I'm an IT student and aspiring developer with a strong interest in web development and technology.
                    I enjoy building websites, learning new programming concepts, and improving my skills through academic and personal projects.
                    My goal is to gain practical experience, contribute to meaningful projects, and continue growing as a developer.
                </p>
                
                <h2>Background</h2>
                <p>
                    I am a junior IT student with an interest in web development and technology.
                    I have experience building academic and personal projects using modern web technologies and continuously work on improving my technical skills.
                    I enjoy learning new tools, solving problems, and gaining practical experience through projects and coursework.
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
