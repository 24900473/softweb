[# Ex.06 Restuarant Website
## Date:22-05-2026

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
```html

index.html

<!DOCTYPE html>
<html>
<head>
    <title>Little Lemon Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="logo">
        <h1>LITTLE LEMON</h1>
    </div>

    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </div>

    <div class="banner">
        <h1>30% Off This Weekend</h1>
        <p>Enjoy delicious foods with special offers.</p>
    </div>

    <div class="container">

        <div class="card">
            <h2>Our New Menu</h2>
            <img src="images/food1.jpg">
            <p>Check our tasty dishes and special recipes.</p>
            <a href="menu.html">See our menu</a>
        </div>

        <div class="card">
            <h2>Book a Table</h2>
            <img src="images/food2.jpg">
            <p>Reserve your table now for family dinner.</p>
            <a href="#">Book now</a>
        </div>

        <div class="card">
            <h2>Opening Hours</h2>
            <img src="images/chef.jpg">
            <p>Mon-Fri : 2pm - 10pm</p>
            <p>Sat-Sun : 2pm - 11pm</p>
        </div>

    </div>

    <footer>
        <p>Designed by JINITH KUMAR V </p>
    </footer>

</body>
</html>

menu.html

<!DOCTYPE html>
<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="navbar">
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</div>

<h1 align="center">OUR MENU</h1>

<div class="container">

    <div class="card">
        <img src="images/biryani.jpg">
        <h2>Chicken Biryani</h2>
    </div>

    <div class="card">
        <img src="images/pizza.jpg">
        <h2>Pizza</h2>
    </div>

    <div class="card">
        <img src="images/burger.jpg">
        <h2>Burger</h2>
    </div>

    <div class="card">
        <img src="images/pasta.jpg">
        <h2>Pasta</h2>
    </div>

    <div class="card">
        <img src="images/friedrice.jpg">
        <h2>Fried Rice</h2>
    </div>

    <div class="card">
        <img src="images/noodles.jpg">
        <h2>Noodles</h2>
    </div>

    <div class="card">
        <img src="images/cake.jpg">
        <h2>Cake</h2>
    </div>

    <div class="card">
        <img src="images/icecream.jpg">
        <h2>Ice Cream</h2>
    </div>

    <div class="card">
        <img src="images/shawarma.jpg">
        <h2>Shawarma</h2>
    </div>

    <div class="card">
        <img src="images/dosa.jpg">
        <h2>Dosa</h2>
    </div>

    <div class="card">
        <img src="images/idli.jpg">
        <h2>Idli</h2>
    </div>

    <div class="card">
        <img src="images/parotta.jpg">
        <h2>Parotta</h2>
    </div>

</div>

<footer>
    <p>Designed by JINITH KUMAR V </p>
</footer>

</body>
</html>

admin.html

<!DOCTYPE html>
<html>
<head>
    <title>Administration</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="navbar">
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</div>

<h1 align="center">ADMINISTRATION</h1>

<div class="container">

    <div class="card">
        <img src="images/admin1.jpg">
        <h2>John</h2>
        <p>Manager</p>
    </div>

    <div class="card">
        <img src="images/admin2.jpg">
        <h2>David</h2>
        <p>Head Chef</p>
    </div>

    <div class="card">
        <img src="images/admin3.jpg">
        <h2>Priya</h2>
        <p>Assistant Chef</p>
    </div>

    <div class="card">
        <img src="images/admin4.jpg">
        <h2>Ravi</h2>
        <p>Cashier</p>
    </div>

    <div class="card">
        <img src="images/admin5.jpg">
        <h2>Anu</h2>
        <p>Receptionist</p>
    </div>

    <div class="card">
        <img src="images/admin6.jpg">
        <h2>Kumar</h2>
        <p>Supervisor</p>
    </div>

</div>

<footer>
    <p>Designed by JINITH KUMAR V </p>
</footer>

</body>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="navbar">
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</div>

<div class="card" style="margin:auto; margin-top:50px;">

    <h1>Contact Us</h1>

    <p><b>Address:</b> Chennai, Tamil Nadu</p>

    <p><b>Phone:</b> +91 9876543210</p>

    <p><b>Email:</b> littlelemon@gmail.com</p>

</div>

<footer>
    <p>Designed by JINITH KUMAR V </p>
</footer>

</body>
</html>


```

## OUTPUT:
Home:
<img width="1391" height="540" alt="image" src="https://github.com/user-attachments/assets/2e4bc9f3-62aa-4c67-b950-f7cc6c19dd3c" />


Menu:

<img width="1265" height="481" alt="image" src="https://github.com/user-attachments/assets/a8e165b8-5a07-4e54-88d3-303c77f560e7" />

Admin:
<img width="1344" height="561" alt="image" src="https://github.com/user-attachments/assets/76f67933-32f4-4a7d-8bfd-13b0c0535497" />


Contact:
<img width="1290" height="389" alt="image" src="https://github.com/user-attachments/assets/7123072e-d7dc-450f-b978-bd1be4c8eb02" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
](https://github.com/24900473/cover/blob/main/README.md)
