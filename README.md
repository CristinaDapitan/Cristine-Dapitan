<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
          content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" 
          href=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
          integrity=
"sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
             crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="responsive.css">
</head>

<body>
    <!-- Navbar header section -->
    <header class="header">
        <nav class="navbar">
            <div class="logo">
                <h2 class="logo-heading">Cristine Dapitan</h2>
            </div>
            <div class="hamburger" id="hamburger">
                <i class="fas fa-bars hamburger-icon"></i>
                <i class="fas fa-times cross-icon"></i>
            </div>
            <div class="menu">
                <ul class="menu-list">
                    <li class="menu-list-items">
                        <a class="links" href="#home">
                              Home
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#portfolio">
                              Portfolio
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#about">
                              About
                          </a>
                    </li>
                   
                    
                    <li class="menu-list-items">
                        <a class="links" href="#contact">
                              Contact Me
                          </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- Main hero banner -->
    <section id="home" class="hero">
        <div class="intro">
            <div class="headings">
                <bold><h3 class="greet-heading">Hello, I'm</h3></bold>
                <h1 class="my-heading">Cristine Dapitan</h1>
                <h1>A WEB DESIGNER</h1>
               <bold> <p>
                    From Northwestern Mindanao State College of Science and Technology.
                </p></bold>
            </div>
            <div class="intro-buttons">
                <button class="btn common-btn">Hire Me</button>
                <button class="btn ghost-btn">Download CV</button>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section class="portfolio" id="portfolio">
        <div class="portfolio-heading">
            <h1 class="my-heading text-center">Portfolio</h1>
        </div>
        <div class="portfolio-content">
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="image 1.jpg" 
                                 alt="Web Design Image">
                        </div>
                        <h3 class="greet-heading blue-text">Web Design</h3>
                        <p class="small-para blue-text">Designing</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="image 2.jpg" 
                                 alt="Web Development Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              Web Development
                          </h3>
                        <p class="small-para blue-text">Development</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="IMAGE 3.jpg" alt="SEO Image">
                        </div>
                        <h3 class="greet-heading blue-text">SEO</h3>
                        <p class="small-para blue-text">Optimization</p>
                    </div>
                </div>
            </div>
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="image 4.jpg" 
                                 alt="Content Writting Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              Content Writing
                          </h3>
                        <p class="small-para blue-text">Writing</p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="IMAGE 5.jpg" 
                                 alt="Wordpress Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              WordPress Dev
                          </h3>
                        <p class="small-para blue-text">
                              Content Management System
                          </p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card port-card">
                        <div class="image">
                            <img src="image 6.jpg" 
                                 alt="Video Editing Image">
                        </div>
                        <h3 class="greet-heading blue-text">
                              Video Editing
                          </h3>
                        <p class="small-para blue-text">Editing</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="about-text">
            <h1 class="my-heading">About Me</h1>
            
            <p class="lead-para">
                I am Cristine Prieto Dapitan, 19 years old from Purok 2 Bitoon Clarin Misamis Occidental.
                I graduated from The Uiversity of Northwestern Mindanao (UNM) with the course of Bachelor
                of Science and Information Technology-major in Information Technology.
            </p>
            <p>
                I am a hardworking student and actually I am also a working student. I have good performance in School,
                that reflect in my grades. I belive I am suitable for the work and desrve to be hired. 
            </p>
        
        </div>
        <div class="about-image">
            <img src="CRISTINA.jpg" alt="About Image">
        </div>
    </section>
  
    <!-- Contact me section -->
    <section class="contact" id="contact">
        <div class="contact-heading">
            <h1 class="my-heading text-center">Contact Me</h1>
       
                <h1 class="greet-heading">My Contact Details</h1>
                <div class="details">
                    <h5 class="contact-heading">EMAIL</h5>
                    <p class="contact-text">cristine.dapitan@nmsc.edu.ph</p>
                </div>
                <div class="details">
                    <h5 class="contact-heading">PHONE</h5>
                    <p class="contact-text">+639639631231</p>
                </div>
                
                <div class="details">
                    <h5 class="contact-heading">ADDRESS</h5>
                    <p class="contact-text">Bitoon, Clarin Misamis Occidental </p>
                    <p>Purok-2</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer section -->
    <footer class="footer">
        <div class="footer-content text-center">
            
            <div class="social-links">
                <div class="footer-menu">
                    <ul class="footer-menu-list">
                        <li class="footer-list-items">
                            <a class="footer-links" href="https://www.facebook.com/cristine.dapitan.12">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                        
                        
                        </li>
                        <li class="footer-list-items">
                            <a class="footer-links" href="https://www.instagram.com/cristinadapitan/profilecard/?igsh=MW05ZW91NmVjenZ5dg==">
                                <i class="fab fa-instagram"></i>
                            </a>
                        </li>
                        
                    
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <script src=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/js/all.min.js"
        integrity=
"sha512-uKQ39gEGiyUJl4AI6L+ekBdGKpGw4xJ55+xyJG7YFlJokPNYegn9KwQ3P8A7aFQAUtUsAQHep+d/lrGqrbPIDQ=="
        crossorigin="anonymous" referrerpolicy="no-referrer">
      </script>
    <script src="script.js"></script>
</body>

</html>
