# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

## c-website:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Website</title>
    <link rel="stylesheet" href="c-website.css">
</head>
<body>
    <header class="header">
        <div class="logo">
            <h1>Z3NO MOBIZONE</h1>
        </div>
        <nav class="navbar">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="9486517534">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <p>Welcome to Our Commercial Website Your gateway to amazing products and services!</p>
            
            <a href="#" class="btn">Today Deals!!</a>
        </div>
    </section>

    <section class="products">
        <h2>Our Featured Products</h2>
        <div class="product-container">
            <div class="product">
                <img src="iqoo12.jpg" alt="Product 1">
                <h3>Product 1</h3>
                <p>$600</p>
                <a href="https://www.amazon.in/iQOO-Storage-Snapdragon%C2%AE-Platform-Flagship/dp/B07WGMXVFK/ref=sr_1_1?crid=IN5TBM89VYFR&dib=eyJ2IjoiMSJ9.QofUDQABQ2JrTmRN-KNCZtRjqblCyBLn5dLoFu3TWF5xQb5_tPyCdekTbA89iDZjOyQfOZTDyIDpKtHtj4A8R-M8yOwARjCE5KIA3eNEAMp1ajCSM44F24qriI8o0dbgnIbjJxuDewoPwF7iRp0erWkfPDwZ7J9WdQYk6XxJngZZ4eNUt1FwTFR8LV9-pQXyJzbat8WsFXE_lrXpZMqV5-H-lpphoFLT_kjpxPqa62A.VeljeOYSUANfd3fukNXQu-DnGO2upUNtSrtow8ACS4E&dib_tag=se&keywords=iqoo+12&qid=1743237920&sprefix=iqoo12%2Caps%2C281&sr=8-1" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="iqoo.webp" alt="Product 2">
                <h3>Product 2</h3>
                <p>$375</p>
                <a href="https://www.amazon.in/iQOO-Snapdragon-Processor-Supercomputing-Flagship/dp/B07WGPJ82V/ref=sr_1_1?crid=36WRSFZFNOY0Y&dib=eyJ2IjoiMSJ9.2E2f1xD8XHQi4GbmE0lFGdqXcAvwzm75ayogq8uin2WWMGNWe4KV1YJfWjPmippuFNeTwxwzzPkDzhZQ_plsv2PSXlyBP8fseiG8jNyjBMC3di7KVz9sj9V3JV6FblJiukoeg7qX1SSZusEGDn7wBfmSD0BxlTLkQ71HysV1vIQu4Msn3fOOy4xNfEEb90FF4H7bME-nx_mglD3K2xapbVyAz0hYaryO8hBNrLNdnoc.i3xkgFRw0E1S06aFVu4QT6P6cqE9ZI9AmYRZm4FBRdk&dib_tag=se&keywords=iqoo%2Bneo%2B9pro&nsdOptOutParam=true&qid=1743237847&sprefix=iqoo%2Caps%2C227&sr=8-1&th=1" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="iqooz7.jpg" alt="Product 3">
                <h3>Product 3</h3>
                <p>$250</p>
                <a href="https://www.amazon.in/iQOO-MediaTek-Dimesity-Processor-Smartphone/dp/B07WGPJPR3/ref=sr_1_1?crid=ASUOUHXD0S0L&dib=eyJ2IjoiMSJ9.Lr0s-d26dDDz1sFeEMFX6VB5GGfN-LjsNJQEW3BN1JlqxW_pKJ3TgWS-tq3ZcPjc-0utbe3fxp20N_GgH5xUgdHQDOizE3uQn1cWxNOwLTHsKeABzEPOb9hzVjXQo3-7mgIyNhjhjzbgdkA2V3_FvOkK0yCCVElqMF0daRyzD9D0Ona4PmebgS5WyzI1ZYZrp0uCKBiZWVB85nmlzF79n37qVnnkIDh1lB_iJkTvHx4.O2IZooVbNhVz4q6zBMynjxFyu1wOpvrh0-IZpVZyaVc&dib_tag=se&keywords=iqoo+z7&qid=1743237947&sprefix=iqoo+z7%2Caps%2C267&sr=8-1" class="btn">Buy Now</a>
            </div>
            <div class="product">
                <img src="iqoo7.jpg" alt="Product 2">
                <h3>Product 4</h3>
                <p>$325</p>
                <a href="http://amazon.in/iQOO-Fearless-Snapdragon%C2%AE-Independent-Flagship/dp/B07WFPLL3C" class="btn">Buy Now</a>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="footer-content">
            <p>&copy; 2025 z3no mobizone  All rights reserved.</p>
            <div class="social-links">
                <a href="z3no_mobizone_91">Facebook</a>
                <a href="#">Twitter</a>
                <a href="@z3no_mobi_zone">Instagram</a>
            </div>
        </div>
    </footer>
</body>
</html>


```

## c-website.css:
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #333;
    color: white;
}

.logo h1 {
    font-size: 24px;
}

.navbar ul {
    display: flex;
    list-style: none;
}

.navbar ul li {
    margin-left: 20px;
}

.navbar ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 130px;
    background-color: #275a6f;
    color: white;
    text-align: center;
}

.hero-content {
    max-width: 600px;
}

.hero h2 {
    font-size: 36px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 18px;
    margin-bottom: 20px;
}

.btn {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.products {
    padding: 50px 20px;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

.product {
    flex: 1 1 calc(33.333% - 20px);
    max-width: 300px;
    background-color: #f4f4f4;
    padding: 20px;
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.product img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

.product h3 {
    font-size: 24px;
    margin: 10px 0;
}

.product p {
    font-size: 18px;
    margin: 10px 0;
}

.footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

.footer-content {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.social-links a {
    color: white;
    text-decoration: none;
    margin: 5px;
}

```

## OUTPUT:




![Screenshot 2025-03-29 142843](https://github.com/user-attachments/assets/38ced774-1257-48f4-9f9c-ed75e54f9054)
![Screenshot 2025-03-29 142906](https://github.com/user-attachments/assets/40e0cf5f-a9a3-46d4-b6c6-0076b15772a8)



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
