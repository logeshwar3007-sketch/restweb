# Ex.07 Restaurant Website
## Date:16/12/2025
## Ref.no:25014493

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
~~~
home.html

<!DOCTYPE html>
<html>
<head>
    <title>Cassandra Restaurant</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Cassandra Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="Screenshot 2025-10-08 132427.png" alt="Restaurant Banner" style="width:80%; max-width:900px; border-radius:10px;">
    <h2>Welcome to Cassandra</h2>
    <p>Authentic flavors, fresh ingredients, and a cozy dining experience.</p>
</section>

<footer>
    © Designed by logan s.
</footer>
</body>
</html>
menu.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Cassandra - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Cassandra Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <div class="card"><img src="1..png"-₹660</p></div>
        <div class="card"><img src="2..png" - ₹360</p></div>
        <div class="card"><img src="3..png" - ₹320</p></div>
        <div class="card"><img src="4..png" - ₹250</p></div>
        <div class="card"><img src="5..png" - ₹200</p></div>
        <div class="card"><img src="6..png" - ₹90</p></div>
        <div class="card"><img src="7..png" - ₹320</p></div>
        <div class="card"><img src="8..png"><p>Prawn Fry - ₹350</p></div>
        <div class="card"><img src="9..png"><p>chicken Biriyani - ₹170</p></div>
        <div class="card"><img src="10..png"><p>Club Sandwich - ₹140</p></div>
        <div class="card"><img src="11.png"><p>Fresh Juice - ₹100</p></div>
        <div class="card"><img src="12..png"><p>Coffee - ₹70</p></div>
    </div>
</section>

<footer>
    © Designed by logan s.
</footer>
</body>
</html>
admin.html

<!DOCTYPE html>
<html>
<head>
    <title>cassandra - Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>cassandra  Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Meet Our Team</h2>
    <div class="team-grid">
        <div class="card"><img src="Screenshot 2025-10-08 171505.png" ><p>Person 1 - Head Chef</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 171723.png"><p>Person 2 - Manager</p></div>
    </div>
</section>

<footer>
    © Designed by logan s
</footer>
</body>
</html>
contact.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Thalapakkatti - Contact Us</title>
    <link rel="stylesheet" href="index.css">
    
        
        
</head>
<body>

<header>
    <h1>cassandra Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <p><b>Address:</b> No. 83, Anna Salai,Mount Road, Chennai,Tamil Nadu 600002</p>
        <p><b>Phone:</b> +91 9345819747</p>
        <p><b>Email:</b> contact@lamesa.com</p>
        <p><b>Opening Hours:</b> Mon-Sun: 10:00 AM - 10:00 PM</p>
    </div>
</section>

<footer>
    © Designed by logan s.
</footer>

</body>
</html>
index.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #fff7f5;
    color: #333;
}
header {
    background-color: #b33a3a; /* Primary color */
    color: white;
    padding: 20px;
    text-align: center;
}
nav {
    background-color: #333;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 8px;
    display: inline-block;
}
nav a:hover {
    background-color: #f2c57c; /* Accent color */
    color: #333;
}
section {
    padding: 40px;
    text-align: center;
}
h2 {
    color: #b33a3a;
    font-style:oblique;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 1000px;
    margin: 20px auto;
    text-align: center;
}
.card {
    background-color: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    font-style: italic;
    color:#b33a3a;
    text-shadow:#f2c57c;
}
.card img {
    width: 80px;
    height: 100px;
    object-fit: cover;
    border-radius: 25px;
    align-items: center;
    border: #f2c57c;
    
}
footer {
    background-color:#333;
    color: white;
    
    text-align: center;
    padding: 15px;
}
contact-container {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            padding: 20px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .contact-container h2 {
            text-align: center;
            color: #b33a3a;
        }
        .contact-container p {
            font-size: 18px;
            margin: 10px 0;
        }
        .contact-container b {
            color: #b33a3a;
        }
~~~

## OUTPUT:
<img width="1912" height="971" alt="image" src="https://github.com/user-attachments/assets/4a997d53-c110-491a-b0d6-ac804f7446a3" />
<img width="1900" height="967" alt="image" src="https://github.com/user-attachments/assets/60d97f35-85ad-4a43-8f00-d34302bca142" />
<img width="1890" height="965" alt="image" src="https://github.com/user-attachments/assets/2f83fd21-23d7-485e-b579-44ace63df046" />
<img width="1912" height="965" alt="image" src="https://github.com/user-attachments/assets/fa7196c1-c268-4a00-9f46-98f251327d6c" />




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
