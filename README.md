# Project Responsive Web Design using Bootstrap
## Date:14.11.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Bootstrap Webpage</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">WebCraft Studio</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item"><a class="nav-link" href="#home">𝓗𝓞𝓜𝓔</a></li>
                <li class="nav-item"><a class="nav-link" href="#services">𝓢𝓔𝓡𝓥𝓘𝓒𝓔</a></li>
                <li class="nav-item"><a class="nav-link" href="#about">𝓐𝓑𝓞𝓤𝓣</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact"></a>CONTACT</li>
    
            </ul>
        </div>
    </div>
</nav>

<!-- HERO SECTION -->
<section id="home" class="bg-light text-center p-5">
    <div class="container">
        <h1 class="display-4 fw-bold">𝕎𝕖𝕝𝕔𝕠𝕞𝕖 𝕥𝕠 𝕆𝕦𝕣 𝕎𝕖𝕓ℂ𝕣𝕒𝕗𝕥 𝕊𝕥𝕦𝕕𝕚𝕠 𝕎𝕖𝕓𝕤𝕚𝕥𝕖</h1>
        <p class="lead">We create clean, modern, and responsive web designs.</p>
        <a href="#services" class="btn btn-primary btn-lg mt-3">Explore Services</a>
    </div>
</section>

<!-- SERVICES -->
<section id="services" class="py-5">
    <div class="container">
        <h2 class="text-center mb-4">Our Services</h2>

        <div class="row">
            <div class="col-md-4">
                <div class="card shadow-sm p-3">
                    <h4 class="mb-3">Web Development</h4>
                    <p>Building responsive websites using modern tools and frameworks.</p>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card shadow-sm p-3">
                    <h4 class="mb-3">UI/UX Design</h4>
                    <p>Crafting user-friendly interfaces and beautiful design layouts.</p>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card shadow-sm p-3">
                    <h4 class="mb-3">Branding</h4>
                    <p>Helping you create a strong and memorable brand identity.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section id="about" class="bg-light py-5">
    <div class="container">
        <h2 class="text-center mb-4">About Us</h2>
        <p class="text-center">
            We are a creative team passionate about building modern websites and digital experiences.
            Our goal is to help businesses grow through effective design and technology.
        </p>
    </div>
</section>

<!-- CONTACT -->
<section id="contact" class="py-5">
    <div class="container text-center">
        <h2 class="mb-4">Contact Us</h2>
        <p>Email: contact@example.com</p>
        <p>Phone: +91 98765 43210</p>
        <a href="mailto:contact@example.com" class="btn btn-dark mt-2">Send Email</a>
    </div>
</section>

<!-- FOOTER -->
<footer class="bg-dark text-white text-center p-3">
    © 2025 MyWebsite | All Rights Reserved
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
<img width="1906" height="1084" alt="Screenshot 2025-11-15 090859" src="https://github.com/user-attachments/assets/6acf7cda-4853-427b-aea8-cc409bc52635" />


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
