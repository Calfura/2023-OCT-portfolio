# Portfolio

## Overview
This is a portfolio website to display some services of the company "something something". This is currently under development. We will keep on adding those features in readme that we add on the website.


## Components

## Header
Header is the component at the top of the website. It contains logo, name and nav bar.
Here is the code for the header we have: 
```html
<header>
        <div class="logo-name">
            <a href="./index.html">
                <img src="https://nexted.com.au/wp-content/uploads/2023/07/CODR_Logo_Black-_-Green_RGB.png" alt="Coder Academy Logo">
            </a>
            <p class="name">
                <span class="coder-text">Coder</span>
                <span class="academy-text">Academy</span>
            </p>
        </div>

        <nav id="nav-items">
            <a href="./index.html">Home</a>
            <a href="./pages/about.html">About</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>
    </header>
```

### Footer
Footer has social media links, and some contact and address information.

```html
<footer>
    <div class="social-media">
        <a href="https://facebook.com" target="_blank">
            <i class="fa-brands fa-facebook" target=""></i>
        </a>
        <a href="https://www.github.com">
            <i class="fa-brands fa-github"></i>
        </a>
        <a href="https://www.linkedin.com">
            <i class="fa-brands fa-linkedin"></i>
        </a>
    </div>
    <div class="info">
        <p>Contact: 404040404</p>
        <p>Address: 0 Street, Country</p>
    </div>
</footer>
```