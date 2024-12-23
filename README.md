# Project Responsive Web Design using Bootstrap
# Date: 5/12/2024
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
                                /homepage/
                            <!DOCTYPE html>
                        <html lang="en">
                        
                        <head>
                            <meta charset="UTF-8">
                            <meta name="viewport" content="width=device-width, initial-scale=1.0">
                            <title>Dribbble Clone</title>
                            <!-- Bootstrap CSS -->
                            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
                            <!-- Font Awesome Icons -->
                            <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
                            <!-- Custom CSS -->
                            <link rel="stylesheet" href="styles.css">
                        </head>
                        
                        <body>
                        
                            <!-- Navigation Bar -->
                            <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-sm">
                                <div class="container">
                                    <a class="navbar-brand" href="#">Dribbble</a>
                                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                                        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                                        <span class="navbar-toggler-icon"></span>
                                    </button>
                                    <div class="collapse navbar-collapse" id="navbarNav">
                                        <ul class="navbar-nav ms-auto">
                                            <li class="nav-item">
                                                <a class="nav-link" href="#"><i class="fas fa-home"></i> Home</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="#"><i class="fas fa-search"></i> Explore</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="#"><i class="fas fa-images"></i> Shots</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="#"><i class="fas fa-sign-in-alt"></i> Sign In</a>
                                            </li>
                                            <li class="nav-item">
                                                <a class="nav-link" href="#"><i class="fas fa-user-plus"></i> Sign Up</a>
                                            </li>
                                        </ul>
                                        <!-- Search Form -->
                                        <form class="d-flex ms-3" role="search">
                                            <input class="form-control me-2" type="search" placeholder="Search shots" aria-label="Search">
                                            <button class="btn btn-outline-light" type="submit"><i class="fas fa-search"></i> Search</button>
                                        </form>
                                    </div>
                                </div>
                            </nav>
                        
                            <!-- Featured Categories Section -->
                            <div class="container mt-5">
                                <h2 class="text-center bg-dark text-light mb-4">Featured Categories</h2>
                                <div class="row">
                                    <div class="col-lg-3 col-md-4 mb-4">
                                        <div class="card">
                                            <img src="webdesign.jpeg" class="card-img-top" alt="Category 1">
                                            <div class="card-body">
                                                <h5 class="card-title"><i class="fas fa-desktop"></i> Web Design</h5>
                                                <p class="card-text">Explore the best web design shots from creatives around the world.</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                                        <div class="card">
                                            <img src="images.jpeg" class="card-img-top" alt="Category 2">
                                            <div class="card-body">
                                                <h5 class="card-title"><i class="fas fa-paint-brush"></i> Illustration</h5>
                                                <p class="card-text">Discover stunning illustrations for inspiration.</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                                        <div class="card">
                                            <img src="animation.jpeg" class="card-img-top" alt="Category 2">
                                            <div class="card-body">
                                                <h5 class="card-title"><i class="fas fa-paint-brush"></i> Animation & Motion Graphics</h5>
                                                <p class="card-text">Dynamic visual elements, including GIFs, animations, and videos.</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="col-lg-3 col-md-4 col-sm-6 mb-4">
                                        <div class="card">
                                            <img src="infographic.avif" class="card-img-top" alt="Category 2">
                                            <div class="card-body">
                                                <h5 class="card-title"><i class="fas fa-paint-brush"></i> Infographic Design</h5>
                                                <p class="card-text">Visual representation of data and statistics.</p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        
                            <!-- Shots Section -->
                            <div class="container mt-5">
                                <div class="row">
                                    <!-- Shot 1 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot1.html">
                                                <img src="landingpage.jpeg" class="card-img-top shot-img" alt="Shot 1">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Landing Page Design <i class="fas fa-heart"></i></h5>
                                                <p class="card-text">A modern, clean landing page design for a fictional product launch.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 2 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot2.html">
                                                <img src="mobiledesign.png" class="card-img-top shot-img" alt="Shot 2">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Mobile App UI <i class="fas fa-thumbs-up"></i></h5>
                                                <p class="card-text">A sleek and user-friendly mobile app interface for a social media platform.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 3 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot3.html">
                                                <img src="logobusiness.jpg" class="card-img-top shot-img" alt="Shot 3">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Logo Design Concept <i class="fas fa-pencil-alt"></i></h5>
                                                <p class="card-text">A fresh and modern logo design for a tech startup.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 4 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot4.html">
                                                <img src="dashboard.jpeg" class="card-img-top shot-img" alt="Shot 4">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Dashboard UI <i class="fas fa-tachometer-alt"></i></h5>
                                                <p class="card-text">A clean and intuitive dashboard design for a project management tool.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 5 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot5.html">
                                                <img src="flatdesign.jpg" class="card-img-top shot-img" alt="Shot 5">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Flat Design Illustration <i class="fas fa-palette"></i></h5>
                                                <p class="card-text">A simple and colorful flat design of a character and environment.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 6 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot6.html">
                                                <img src="e commerce.jpeg" class="card-img-top shot-img" alt="Shot 6">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">E-commerce Website <i class="fas fa-shopping-cart"></i></h5>
                                                <p class="card-text">A fully responsive e-commerce website design showcasing product listings and shopping cart.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 7 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot7.html">
                                                <img src="fitness.avif" class="card-img-top shot-img" alt="Shot 7">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Fitness Tracker App <i class="fas fa-running"></i></h5>
                                                <p class="card-text">A health and fitness tracking app with vibrant charts and workout plans.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 8 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot8.html">
                                                <img src="social media app.jpeg" class="card-img-top shot-img" alt="Shot 8">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Social Media App UI <i class="fas fa-comments"></i></h5>
                                                <p class="card-text">A trendy, minimalist design for a new social media app.</p>
                                            </div>
                                        </div>
                                    </div>
                        
                                    <!-- Shot 9 -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot9.html">
                                                <img src="eventposter.jpeg" class="card-img-top shot-img" alt="Shot 9">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Event Poster Design <i class="fas fa-poster"></i></h5>
                                                <p class="card-text">A vibrant, attention-grabbing poster design for a fictional event.</p>
                                            </div>
                                        </div>    
                                    </div>
                        
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot1.html">
                                                <img src="minimalist.jpeg" class="card-img-top shot-img" alt="Shot 1">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">Minimalist Design<i class="fas fa-heart"></i></h5>
                                                <p class="card-text">Minimalist design is a timeless design philosophy that emphasizes simplicity, clarity, and functionality.</p>
                                            </div>
                                        </div>
                                    </div>
                            
                                    <!-- New Shot 2: UI/UX Wireframes & Prototypes -->
                                    <div class="col-md-4 mb-4">
                                        <div class="card shot-card">
                                            <a href="shot1.html">
                                                <img src="ux.jpg" class="card-img-top shot-img" alt="Shot 1">
                                            </a>
                                            <div class="card-body">
                                                <h5 class="card-title">UI/UX Wireframes & Prototypes<i class="fas fa-heart"></i></h5>
                                                <p class="card-text">UI/UX wireframes and prototypes are essential tools in the design process, serving as blueprints for creating intuitive and user-friendly digital experiences.</p>
                                            </div>
                                         </div>
                                    </div>    
                        
                                     <div class="col-md-4 mb-4">
                                         <div class="card shot-card">
                                             <a href="shot10.html">
                                                <img src="businesscard.jpg" class="card-img-top shot-img" alt="Shot 10">
                                             </a>
                                             <div class="card-body">
                                                <h5 class="card-title">Business Card Design <i class="fas fa-id-card"></i></h5>
                                                 <p class="card-text">A sleek and professional business card design for a modern brand.</p>
                                            </div>
                                         </div>
                                    </div>
                                </div> 
                            </div>
                        
                            <!-- Pagination -->
                            <div class="d-flex justify-content-center">
                                <nav aria-label="Page navigation">
                                    <ul class="pagination">
                                        <li class="page-item"><a class="page-link" href="#">Previous</a></li>
                                        <li class="page-item"><a class="page-link" href="#">1</a></li>
                                        <li class="page-item"><a class="page-link" href="#">2</a></li>
                                        <li class="page-item"><a class="page-link" href="#">3</a></li>
                                        <li class="page-item"><a class="page-link" href="#">Next</a></li>
                                    </ul>
                                </nav>
                            </div>
                        
                            <!-- Footer Section -->
                            <footer class="bg-dark py-4 mt-5">
                                <div class="container text-center">
                                    <p>&copy; 2024 Dribbble Clone | Built by J.Pavitra</p>
                                    <div>
                                        <a href="#" class="me-3"><i class="fab fa-facebook-f"></i></a>
                                        <a href="#" class="me-3"><i class="fab fa-twitter"></i></a>
                                        <a href="#" class="me-3"><i class="fab fa-instagram"></i></a>
                                        <a href="#" class="me-3"><i class="fab fa-linkedin-in"></i></a>
                                    </div>
                                </div>
                            </footer>
                        
                            <!-- Bootstrap JS and Popper.js -->
                            <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
                            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
                        </body>
                        
                        </html>
                        
                                /illustration/
                                <!DOCTYPE html>
                                <html lang="en">
                                <head>
                                    <meta charset="UTF-8">
                                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                                    <title>Landing Page Design</title>
                                    <!-- Bootstrap CSS -->
                                    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
                                    <!-- Font Awesome Icons -->
                                    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
                                    <!-- Google Fonts -->
                                    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
                                    <style>
                                        body {
                                            font-family: 'Roboto', sans-serif;
                                            line-height: 1.6;
                                            background-color: #f8f9fa;
                                        }
                                        .navbar {
                                            background-color: black;
                                        }
                                        .navbar-brand {
                                            font-weight: bold;
                                            color:white;
                                        }
                                        .navbar-brand:hover {
                                            color: #007bff;
                                        }
                                        h2 {
                                            font-weight: 700;
                                            color: whitesmoke;
                                        }
                                        .img-fluid {
                                            border-radius: 8px;
                                            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
                                        }
                                        .btn-primary {
                                            background-color: #007bff;
                                            border-color: #007bff;
                                            transition: all 0.3s ease;
                                        }
                                        .btn-primary:hover {
                                            background-color: #0056b3;
                                            border-color: #0056b3;
                                        }
                                        footer {
                                            background-color: #333;
                                            color: #fff;
                                        }
                                        footer a {
                                            color: #007bff;
                                        }
                                        footer a:hover {
                                            color: #0056b3;
                                        }
                                        .social-icons a {
                                            color: #fff;
                                            margin: 0 10px;
                                            transition: color 0.3s ease;
                                        }
                                        .social-icons a:hover {
                                            color: #007bff;
                                        }
                                    </style>
                                </head>
                                <body>
                                    <!-- Navbar -->
                                    <nav class="navbar navbar-expand-lg navbar-light shadow-sm">
                                        <div class="container">
                                            <a class="navbar-brand" href="index.html">Dribbble</a>
                                        </div>
                                    </nav>
                                
                                    <!-- Main Content -->
                                    <div class="container mt-5">
                                        <div class="text-center text-dark">
                                            <h2>illustrations</h2>
                                            <p class="text-muted">"Bringing creativity to life through vibrant colors and imaginative designs."</p>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <img src="images.jpeg" class="img-fluid" alt="illustrations">
                                            </div>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <p>
                                                    Illustrations are powerful visual representations that blend creativity and storytelling to communicate ideas, evoke emotions, and inspire audiences. From detailed artwork to simple sketches, illustrations add depth and personality to various mediums.
                                                </p>
                                                <div class="d-flex justify-content-between mt-4">
                                                    <a href="index.html" class="btn btn-primary"><i class="fas fa-arrow-left"></i> Back to Home</a>
                                                    <a href="contact.html" class="btn btn-outline-secondary">Contact Designer <i class="fas fa-envelope"></i></a>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                
                                    <!-- Footer -->
                                    <footer class="py-4 mt-5">
                                        <div class="container text-center">
                                            <p>&copy; 2024 Dribbble Clone | Designed with ❤️ and Bootstrap</p>
                                            <div class="social-icons">
                                                <a href="#"><i class="fab fa-facebook-f"></i></a>
                                                <a href="#"><i class="fab fa-twitter"></i></a>
                                                <a href="#"><i class="fab fa-instagram"></i></a>
                                                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                                            </div>
                                        </div>
                                    </footer>
                                
                                    <!-- Bootstrap JS and Popper.js -->
                                    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
                                    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
                                </body>
                                </html>
                                /moblieappdesign/
                                <!DOCTYPE html>
                                <html lang="en">
                                <head>
                                    <meta charset="UTF-8">
                                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                                    <title>Landing Page Design</title>
                                    <!-- Bootstrap CSS -->
                                    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
                                    <!-- Font Awesome Icons -->
                                    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
                                    <!-- Google Fonts -->
                                    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
                                    <style>
                                        body {
                                            font-family: 'Roboto', sans-serif;
                                            line-height: 1.6;
                                            background-color: #f8f9fa;
                                        }
                                        .navbar {
                                            background-color: black;
                                        }
                                        .navbar-brand {
                                            font-weight: bold;
                                            color: white;
                                        }
                                        .navbar-brand:hover {
                                            color: #007bff;
                                        }
                                        h2 {
                                            font-weight: 700;
                                            color: #333;
                                        }
                                        .img-fluid {
                                            border-radius: 8px;
                                            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
                                        }
                                        .btn-primary {
                                            background-color: #007bff;
                                            border-color: #007bff;
                                            transition: all 0.3s ease;
                                        }
                                        .btn-primary:hover {
                                            background-color: #0056b3;
                                            border-color: #0056b3;
                                        }
                                        footer {
                                            background-color: #333;
                                            color: #fff;
                                        }
                                        footer a {
                                            color: #007bff;
                                        }
                                        footer a:hover {
                                            color: #0056b3;
                                        }
                                        .social-icons a {
                                            color: #fff;
                                            margin: 0 10px;
                                            transition: color 0.3s ease;
                                        }
                                        .social-icons a:hover {
                                            color: #007bff;
                                        }
                                    </style>
                                </head>
                                <body>
                                    <!-- Navbar -->
                                    <nav class="navbar navbar-expand-lg navbar-light shadow-sm">
                                        <div class="container">
                                            <a class="navbar-brand" href="index.html">Dribbble</a>
                                        </div>
                                    </nav>
                                
                                    <!-- Main Content -->
                                    <div class="container mt-5">
                                        <div class="text-center">
                                            <h2>mobile app design</h2>
                                            <p class="text-muted">A Showcase of Modern Web Design</p>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <img src="mobiledesign.png" class="img-fluid" alt="mobile app design">
                                            </div>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <p>
                                                    A sleek and user-friendly mobile app interface for a social media platform.
                                                </p>
                                                <div class="d-flex justify-content-between mt-4">
                                                    <a href="index.html" class="btn btn-primary"><i class="fas fa-arrow-left"></i> Back to Home</a>
                                                    <a href="contact.html" class="btn btn-outline-secondary">Contact Designer <i class="fas fa-envelope"></i></a>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                
                                    <!-- Footer -->
                                    <footer class="py-4 mt-5">
                                        <div class="container text-center">
                                            <p>&copy; 2024 Dribbble Clone | Designed with ❤️ and Bootstrap</p>
                                            <div class="social-icons">
                                                <a href="#"><i class="fab fa-facebook-f"></i></a>
                                                <a href="#"><i class="fab fa-twitter"></i></a>
                                                <a href="#"><i class="fab fa-instagram"></i></a>
                                                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                                            </div>
                                        </div>
                                    </footer>
                                
                                    <!-- Bootstrap JS and Popper.js -->
                                    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
                                    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
                                </body>
                                </html>
                                /web design/
                                <!DOCTYPE html>
                                <html lang="en">
                                <head>
                                    <meta charset="UTF-8">
                                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                                    <title>Landing Page Design</title>
                                    <!-- Bootstrap CSS -->
                                    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
                                    <!-- Font Awesome Icons -->
                                    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
                                    <!-- Google Fonts -->
                                    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
                                    <style>
                                        body {
                                            font-family: 'Roboto', sans-serif;
                                            line-height: 1.6;
                                            background-color: #f8f9fa;
                                        }
                                        .navbar {
                                            background-color: black;
                                        }
                                        .navbar-brand {
                                            font-weight: bold;
                                            color: white;
                                        }
                                        .navbar-brand:hover {
                                            color: #007bff;
                                        }
                                        h2 {
                                            font-weight: 700;
                                            color: #333;
                                        }
                                        .img-fluid {
                                            border-radius: 8px;
                                            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
                                        }
                                        .btn-primary {
                                            background-color: #007bff;
                                            border-color: #007bff;
                                            transition: all 0.3s ease;
                                        }
                                        .btn-primary:hover {
                                            background-color: #0056b3;
                                            border-color: #0056b3;
                                        }
                                        footer {
                                            background-color: #333;
                                            color: #fff;
                                        }
                                        footer a {
                                            color: #007bff;
                                        }
                                        footer a:hover {
                                            color: #0056b3;
                                        }
                                        .social-icons a {
                                            color: #fff;
                                            margin: 0 10px;
                                            transition: color 0.3s ease;
                                        }
                                        .social-icons a:hover {
                                            color: #007bff;
                                        }
                                    </style>
                                </head>
                                <body>
                                    <!-- Navbar -->
                                    <nav class="navbar navbar-expand-lg navbar-light shadow-sm">
                                        <div class="container">
                                            <a class="navbar-brand" href="index.html">Dribbble</a>
                                        </div>
                                    </nav>
                                
                                    <!-- Main Content -->
                                    <div class="container mt-5">
                                        <div class="text-center">
                                            <h2>webdesign
                                
                                            </h2>
                                            <p class="text-muted">A Showcase of Modern Web Design</p>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <img src="webdesign.jpeg" class="img-fluid" alt="mobile app design">
                                            </div>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <p>
                                                  Web design is the art of creating visually appealing, user-friendly, and functional websites that cater to diverse audiences. From clean layouts to intuitive navigation, a well-designed website ensures users can easily access the information or services they need.
                                                </p>
                                                <div class="d-flex justify-content-between mt-4">
                                                    <a href="index.html" class="btn btn-primary"><i class="fas fa-arrow-left"></i> Back to Home</a>
                                                    <a href="contact.html" class="btn btn-outline-secondary">Contact Designer <i class="fas fa-envelope"></i></a>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                
                                    <!-- Footer -->
                                    <footer class="py-4 mt-5">
                                        <div class="container text-center">
                                            <p>&copy; 2024 Dribbble Clone | Designed with ❤️ and Bootstrap</p>
                                            <div class="social-icons">
                                                <a href="#"><i class="fab fa-facebook-f"></i></a>
                                                <a href="#"><i class="fab fa-twitter"></i></a>
                                                <a href="#"><i class="fab fa-instagram"></i></a>
                                                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                                            </div>
                                        </div>
                                    </footer>
                                
                                    <!-- Bootstrap JS and Popper.js -->
                                    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
                                    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
                                </body>
                                </html>
                                /ui/ux design /
                                <!DOCTYPE html>
                                <html lang="en">
                                <head>
                                    <meta charset="UTF-8">
                                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                                    <title>Landing Page Design</title>
                                    <!-- Bootstrap CSS -->
                                    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
                                    <!-- Font Awesome Icons -->
                                    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
                                    <!-- Google Fonts -->
                                    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
                                    <style>
                                        body {
                                            font-family: 'Roboto', sans-serif;
                                            line-height: 1.6;
                                            background-color: #f8f9fa;
                                        }
                                        .navbar {
                                            background-color: black;
                                        }
                                        .navbar-brand {
                                            font-weight: bold;
                                            color: white;
                                        }
                                        .navbar-brand:hover {
                                            color: #007bff;
                                        }
                                        h2 {
                                            font-weight: 700;
                                            color: #333;
                                        }
                                        .img-fluid {
                                            border-radius: 8px;
                                            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
                                        }
                                        .btn-primary {
                                            background-color: #007bff;
                                            border-color: #007bff;
                                            transition: all 0.3s ease;
                                        }
                                        .btn-primary:hover {
                                            background-color: #0056b3;
                                            border-color: #0056b3;
                                        }
                                        footer {
                                            background-color: #333;
                                            color: #fff;
                                        }
                                        footer a {
                                            color: #007bff;
                                        }
                                        footer a:hover {
                                            color: #0056b3;
                                        }
                                        .social-icons a {
                                            color: #fff;
                                            margin: 0 10px;
                                            transition: color 0.3s ease;
                                        }
                                        .social-icons a:hover {
                                            color: #007bff;
                                        }
                                    </style>
                                </head>
                                <body>
                                    <!-- Navbar -->
                                    <nav class="navbar navbar-expand-lg navbar-light shadow-sm">
                                        <div class="container">
                                            <a class="navbar-brand" href="index.html">Dribbble</a>
                                        </div>
                                    </nav>
                                
                                    <!-- Main Content -->
                                    <div class="container mt-5">
                                        <div class="text-center">
                                            <h2>UI/UX Wireframes & Prototypes
                                
                                            </h2>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <img src="webdesign.jpeg" class="img-fluid" alt="mobile app design">
                                            </div>
                                        </div>
                                        <div class="row justify-content-center mt-4">
                                            <div class="col-lg-8">
                                                <p>
                                                    UI/UX wireframes and prototypes are essential tools in the design process, serving as blueprints for creating intuitive and user-friendly digital experiences. They help visualize the structure, functionality, and flow of a product before it is fully developed.
                                                </p>
                                                <div class="d-flex justify-content-between mt-4">
                                                    <a href="index.html" class="btn btn-primary"><i class="fas fa-arrow-left"></i> Back to Home</a>
                                                    <a href="contact.html" class="btn btn-outline-secondary">Contact Designer <i class="fas fa-envelope"></i></a>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                
                                    <!-- Footer -->
                                    <footer class="py-4 mt-5">
                                        <div class="container text-center">
                                            <p>&copy; 2024 Dribbble Clone | Designed with ❤️ and Bootstrap</p>
                                            <div class="social-icons">
                                                <a href="#"><i class="fab fa-facebook-f"></i></a>
                                                <a href="#"><i class="fab fa-twitter"></i></a>
                                                <a href="#"><i class="fab fa-instagram"></i></a>
                                                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                                            </div>
                                        </div>
                                    </footer>
                                
                                    <!-- Bootstrap JS and Popper.js -->
                                    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
                                    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
                                </body>
                                </html>
                        

# OUTPUT:
![Screenshot 2024-12-23 202037](https://github.com/user-attachments/assets/ad2c43ff-8d4c-45ea-bd83-1d572194a731)

![Screenshot 2024-12-23 200434](https://github.com/user-attachments/assets/28d609ff-adbd-46e1-bf74-ff1fded2c9b1)
![Screenshot 2024-12-23 200456](https://github.com/user-attachments/assets/4694d093-a906-44e5-bd87-8b4107e93710)
![Screenshot 2024-12-23 200521](https://github.com/user-attachments/assets/6ef9e80c-800b-4314-b8a3-f40a63dac12f)
![Screenshot 2024-12-23 200543](https://github.com/user-attachments/assets/f042cd0e-7429-4519-ae59-7f1b8a5a6f4c)
![Screenshot 2024-12-23 200743](https://github.com/user-attachments/assets/145deea0-cf84-4db3-90b1-90ba308250b0)





# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
