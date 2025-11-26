---
layout: home
title: "Portfolio - Home"
permalink: /test
---

<!-- Navigation -->
<nav class="navbar">
    <div class="navbar-container">
        <div class="logo">
            <a href="{{ '/' | relative_url }}">Rasul Huseynli</a>
        </div>
        <div class="nav-menu">
            <a href="{{ '/' | relative_url }}" class="nav-link active">Home</a>
            <a href="{{ '/about/' | relative_url }}" class="nav-link">About</a>
            <a href="{{ '/projects/' | relative_url }}" class="nav-link">Projects</a>
            <a href="{{ '/contact/' | relative_url }}" class="nav-link">Contact</a>
        </div>
    </div>
</nav>

<!-- Home Section -->
<section class="home-section">
    <div class="home-container">
        <div class="profile-photo">
            <img src="{{ '/assets/profile.jpg' | relative_url }}" alt="Profile Photo" class="profile-img">
        </div>
        <div class="home-content">
            <h1>Welcome to My Portfolio</h1>
            <p class="subtitle">Full Stack Developer | Creative Problem Solver | Tech Enthusiast</p>
            <p class="bio">
                I'm a passionate developer with expertise in building responsive web applications. 
                I love creating elegant solutions to complex problems and continuously learning new technologies.
            </p>
            <div class="social-links">
                <a href="https://github.com/GGBUUR" target="_blank" class="social-icon" title="GitHub">
                    <i class="fab fa-github"></i>
                </a>
                <a href="https://www.codecademy.com/profiles/rhuseynli25808" target="_blank" class="social-icon" title="Codecademy">
                    <i class="fab fa-code"></i>
                </a>
                <a href="https://www.linkedin.com/in/rasul-huseynli-4b4a70396/" target="_blank" class="social-icon" title="LinkedIn">
                    <i class="fab fa-linkedin"></i>
                </a>
            </div>
            <div class="cta-buttons">
                    <a href="{{ '/projects/' | relative_url }}" class="btn btn-primary">View My Work</a>
                    <a href="{{ '/contact/' | relative_url }}" class="btn btn-secondary">Get in Touch</a>
            </div>
        </div>
    </div>
</section>

<!-- Featured Section -->
<section class="featured-section">
    <div class="container">
        <h2>Featured Projects</h2>
        <div class="featured-grid">
            <div class="featured-card">
                <div class="card-image">
                    <img src="{{ '/assets/project1.jpg' | relative_url }}" alt="Project 1">
                </div>
                <div class="card-content">
                    <h3>Project 1</h3>
                    <p>A showcase of my development skills and creativity.</p>
                    <a href="{{ '/projects/' | relative_url }}" class="card-link">View Details →</a>
                </div>
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
