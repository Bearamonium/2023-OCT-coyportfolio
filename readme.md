# Portfolio

## Overview
This is a portfolio website for a company that will showcase their services "something something". 
This site is currently under development - we will keep on adding these features mentioned in the readme to the website over time. 

## Components

### Header
Header is the component at the top of the website. It contants logo, name and navigation bar. Here is the code for the header we have:

```html

<header>
        <div class="logo-name">
            <a href="index.html">
                <img src="imgs/professional logo.jpg" alt="coy logo">
            </a>
            <p class="name">
                <span class="feather-text">Feather</span>
                <span class="consulting-text">Consulting</span>
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
Here is the code that we have for the footer: 

```html
<footer>
    <div class="social-media">
        <a href="http://www.facebook.com" target="_blank">
            <i class="fa-brands fa-facebook"></i>
        </a>
        <a href="http://www.github.com" target="_blank">
            <i class="fa-brands fa-github"></i>
        </a>
        <a href="http://www.linkedin.com" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
    </div>
    <div class="info">
        <p>Contact: 0404040404</p>
        <p>42 Wallaby Way, Sydney Australia</p>
    </div>
</footer>
```

