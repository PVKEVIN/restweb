# Ex.07 Restaurant Website
## Date:18/05/2024
## Developed by : P KEVIN (212224040159)

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

index.html
```

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - PVK Foods</title>
    <style>
        body {
            background-color: rgb(244, 76, 216);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(68, 231, 220);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(234, 83, 69);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(70, 242, 141);
        }
        .welcome {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px;
        }
        .welcome h1 {
            font-size: 2.5rem;
        }
        .welcome p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            text-align: center;
        }
        .feature {
            margin: 10px;
            padding: 20px;
            border: 1px solid silver;
            border-radius: 5px;
            width: 300px;
        }
        footer {
            background-color: rgb(242, 229, 91);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to PVK Foods</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="welcome">
        <h1>Your Destination for Exquisite Cuisine</h1>
        <p>PVK Foods offers a wide range of delicious dishes made from the freshest ingredients. Experience the taste of perfection with every bite!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Fresh Ingredients</h3>
            <p>We use only the freshest and highest-quality ingredients to prepare our dishes.</p>
        </div>
        <div class="feature">
            <h3>Family-Friendly</h3>
            <p>Enjoy a welcoming and comfortable atmosphere perfect for family gatherings.</p>
        </div>
        <div class="feature">
            <h3>Exceptional Service</h3>
            <p>Our friendly staff is here to make your dining experience unforgettable.</p>
        </div>
    </section>
    <footer>
        <p>&copy; PVK Foods. All Rights Reserved.</p>
        <p> designed and developed by: P KEVIN</p>
    </footer>
</body>
</html>
```

menu.html
```

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - PVK Foods</title>
    <style>
        body {
            background-color: rgb(245, 83, 220);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(92, 223, 225);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(85, 241, 90);
        }
        nav a {
            color: rgb(248, 97, 97);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(198, 224, 114);
        }
        section {
            padding: 20px;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .menu-item {
            border: 1px solid silver;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: rgb(205, 205, 87);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Explore Our Dishes</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="c:\Users\admin\Downloads\briyani.jpg" alt="briyani">
                <h3>briyani</h3>
                <p>A flavorful and spicy Indian appetizer made with juicy chicken , steamed to have a tasty perfection.</p>
            </div>
            <div class="menu-item">
                <img src="c:\Users\admin\Downloads\parotta 95.jpeg" alt="Parotta 95 Masala">
                <h3>Parotta 95 Masala</h3>
                <p>A rich and creamy North Indian curry with soft parotta in a buttery tomato-based gravy.</p>
            </div>
            <div class="menu-item">
                <img src="c:\Users\admin\Downloads\grill.jpg" alt="grill">
                <h3>grill</h3>
                <p>grill is an american based dish made of chicken fired to juicy flavour.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; PVK Foods. All Rights Reserved.</p>
        <p> designed and developed by: P KEVIN</p>
    </footer>
</body>
</html>
```
about.html
```
about.html 

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - PVK Foods</title>
    <style>
        body {
            background-color: rgb(244, 76, 216);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(68, 231, 220);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(234, 83, 69);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(70, 242, 141);
        }
        .welcome {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px;
        }
        .welcome h1 {
            font-size: 2.5rem;
        }
        .welcome p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            text-align: center;
        }
        .feature {
            margin: 10px;
            padding: 20px;
            border: 1px solid silver;
            border-radius: 5px;
            width: 300px;
        }
        footer {
            background-color: rgb(242, 229, 91);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to PVK Foods</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="welcome">
        <h1>Your Destination for Exquisite Cuisine</h1>
        <p>Rio Foods offers a wide range of delicious dishes made from the freshest ingredients. Experience the taste of perfection with every bite!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Fresh Ingredients</h3>
            <p>We use only the freshest and highest-quality ingredients to prepare our dishes.</p>
        </div>
        <div class="feature">
            <h3>Family-Friendly</h3>
            <p>Enjoy a welcoming and comfortable atmosphere perfect for family gatherings.</p>
        </div>
        <div class="feature">
            <h3>Exceptional Service</h3>
            <p>Our friendly staff is here to make your dining experience unforgettable.</p>
        </div>
    </section>
    <footer>
        <p>&copy; PVK Foods. All Rights Reserved.</p>
        <p> designed and developed by: P KEVIN</p>
    </footer>
</body>
</html>
```

contact.html
```
contact.html 

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - PVK Foods</title>
    <style>
        body {
            background-color: rgb(188, 94, 250);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(79, 253, 247);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(243, 77, 31);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(61, 230, 97);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .contact-info {
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: rgb(237, 240, 89);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>A warm welcome</h2>
        <div class="contact-info">
            <p><strong>Phone:</strong> 9884830986</p>
            <p><strong>Email:</strong> pvkfoods@gmail.com</p>
            <p><strong>Address:</strong> No.10 , PVK Street , Annanagar , Chennai</p>
            <p>we value your feedback</p>
    </section>
    <footer>
        <p>&copy; PVK Foods. All Rights Reserved.</p>
        <p> designed and developed by: P KEVIN</p>
    </footer>
</body>
</html>
```

## OUTPUT:

![Screenshot 2025-05-18 190722](https://github.com/user-attachments/assets/cfb62c33-78f9-4980-9e48-6d23fc50ff20)

![Screenshot 2025-05-20 235445](https://github.com/user-attachments/assets/812bc787-adb5-4096-9f46-e62252420800)

![Screenshot 2025-05-18 184417](https://github.com/user-attachments/assets/cd60e109-b19d-41f1-a43e-0f3b94e9b17c)

![Screenshot 2025-05-18 190650](https://github.com/user-attachments/assets/6eff821d-f95b-45f7-a75c-2594d7631907)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
