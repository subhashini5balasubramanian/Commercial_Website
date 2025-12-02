# Ex02 Commercial Website


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
## HTML:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HomeEase - Home Appliances</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">HomeEase</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">Categories</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h1>Upgrade Your Home</h1>
      <p>Discover premium home appliances to make your life easier.</p>
      <a href="#" class="btn">Shop Now</a>
  </section>

  <section class="features">
    <div class="feature">
      <h3>Free Delivery</h3>
      <p>Fast and free delivery on all appliances.</p>
    </div>
    <div class="feature">
      <h3>Easy Returns</h3>
      <p>30-day hassle-free return policy.</p>
    </div>
    <div class="feature">
      <h3>24/7 Support</h3>
      <p>Dedicated customer service anytime.</p>
    </div>
  </section>

  <section class="categories">
    <h2>Shop by Category</h2>
    <div class="category-grid">
      <div class="category">
        <img src="c:\Users\admin\OneDrive\Documents\ex-2 web\kitchen_.png" alt="Kitchen Appliances">
        <h4>Kitchen</h4>
      </div>
      <div class="category">
        <img src="c:\Users\admin\OneDrive\Documents\ex-2 web\licensed-image.jpg" alt="Living Room">
        <h4>Living Room</h4>
      </div>
      <div class="category">
        <img src="c:\Users\admin\OneDrive\Documents\ex-2 web\cleaner.jpg" alt="Cleaning Appliances">
        <h4>Cleaning</h4>
      </div>
    </div>
  </section>

  <section class="products">
    <h2>Featured Products</h2>
    <div class="product-grid">
      <div class="product">
        <img src="c:\Users\admin\OneDrive\Documents\ex-2 web\mixcer.jpg" alt="Mixer">
        <h4>Smart Mixer</h4>
        <p>$120</p>
      </div>
      <div class="product">
        <img src="c:\Users\admin\OneDrive\Documents\ex-2 web\vaccum.jpg" alt="Vacuum Cleaner">
        <h4>Vacuum Cleaner</h4>
        <p>$150</p>
      </div>
      <div class="product">
        <img src="c:\Users\admin\OneDrive\Documents\ex-2 web\air.jpg" alt="Air Fryer">
        <h4>Air Fryer</h4>
        <p>$99</p>
      </div>
    </div>
  </section>

  <footer>
    <div class="footer-content">
      <p>&copy; 2025 HomeEase. All rights reserved.</p>
      <p>Designed by <strong>Nalini</strong> - Reg No: <strong>212223220063</strong></p>
    </div>
  </footer>
</body>
</html>
```
## CSS:
```
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f8f8f8;
  color: #333;
}

header {
  background: #2c3e50;
  color: white;
  display: flex;
  justify-content: space-between;
  padding: 15px 50px;
  align-items: center;
}

header .logo {
  font-size: 1.8rem;
  font-weight: bold;
}

header nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #eaf6f6;
  padding: 50px;
}

.hero-text h1 {
  font-size: 2.5rem;
}

.hero-text p {
  margin: 10px 0 20px;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background: #27ae60;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

.features {
  display: flex;
  justify-content: space-around;
  padding: 30px 50px;
  background: #fff;
}

.categories {
  padding: 40px 50px;
  background: #f4f4f4;
}

.category-grid {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}

.category img {
  width: 200px;
  height: 150px;
  border-radius: 8px;
}

.products {
  padding: 40px 50px;
}

.product-grid {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}

.product img {
  width: 200px;
  height: 180px;
  border-radius: 8px;
}

footer {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}
```

## OUTPUT

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b2060398-968a-4661-a968-e9af037d9f29" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d1eb754e-48a8-45ca-9811-c6a9bffb1faa" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
