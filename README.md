# Ex.07 Restaurant Website
# Date:08/11/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
Html code

about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>About Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contactus.html">Contact us</a></li>
                <li><a href="administration.html">Administration</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="images/chef.jpeg" alt="Our Chef" class="image">
        <p>At Burger Hut, we believe that a great burger is more than just a meal; it’s an experience.</p>
    </main>
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>


index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Burger Hut</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Restaurant </h1>
        <h2>THE BURGER HUT</h2>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contactus.html">Contact us</a></li>
                <li><a href="administration.html">Administration</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="images/restaurant.jpeg" alt="Restaurant" class="banner">
        <p>At Burger Hut, we believe that a great burger is more than just a meal; it’s an experience. Nestled in the heart of City, we’re dedicated to crafting mouthwatering burgers made from the freshest, locally-sourced ingredients. Whether you’re a meat lover, a veggie enthusiast, or a health-conscious eater, we have something for everyone!</p>
    </main>
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Menu</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contactus.html">Contact us</a></li>
                <li><a href="administration.html">Administration</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="menu-item">
            <img src="images/Dish 1.jpeg" alt="Dish 1" class="image">
            <h1>Classic Cheeseburger</h1>
            <p>Juicy beef patty with melted cheese, lettuce, and tomato.</p>
        </div>
        <div class="menu-item">
            <img src="images/Dish 2.jpeg" alt="Dish 2" class="image">
            <h1>Spicy Jalapeño Crunch</h1>
            <p>Spicy beef patty topped with jalapeños, pepper jack cheese, and aioli.</p>
        </div>
        <div class="menu-item">
            <img src="images/Dish 3.jpeg" alt="Dish 3" class="image">
            <h1>Black Bean Burger</h1>
            <p>Delicious plant-based burger with avocado and salsa.</p>
        </div>
        <div class="menu-item">
            <img src="images/Dish 4.jpeg" alt="Dish 4" class="image">
            <h1>Hand-Spun Milkshake</h1>
            <p>Rich and creamy shakes in various flavors.</p>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>

Administration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Administration</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contactus.html">Contact us</a></li>
                <li><a href="administration.html">Administration</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="BURGER.png" alt="Administration" class="image">
        <p>Welcome to the Burger Hut Administration Page. Our mission is to provide high-quality burgers and excellent customer service in a friendly atmosphere. The administration team manages various aspects of the restaurant, including staffing, inventory, and customer relations. We efficiently handle scheduling, employee training, and performance reviews to maintain a skilled team. Our inventory management system ensures that ingredients are tracked and reordered as needed, while waste control measures help optimize costs. We streamline both in-house and online orders for accuracy and timeliness, and actively monitor customer feedback to maintain quality service. Additionally, we plan promotions, manage social media, and engage in local events to boost brand visibility. Our team also oversees financial reporting, tracking sales and expenses to support growth. For any inquiries, feel free to contact us at admin@burgerhut.com or call (555) 123-4567. Thank you for supporting Burger Hut!.</p>
    </main>
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>

Contact us.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Burger Hut</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Restaurant </h1>
        <h2>THE BURGER HUT</h2>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contactus.html">Contact us</a></li>
                <li><a href="administration.html">Administration</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <img src="images/restaurant.jpeg" alt="Restaurant" class="banner">
        <p>Adress: Burger Hut , Sagas Vaihav Enclave,Injambakkam,Chennai</p>
        <p>Phone no: 9500056615</p>
        <p>Email:burgerhut@gmail.com</p>
    </main>
    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>
</body>
</html>



style.css

body {
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: brown;
}

header {
    background-color: burlywood;
    color: black;
    padding: 10px 0;
}

header nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    background:brown;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    text-decoration: none;
    color: yellow;
    font-weight: bold;
}

.banner, .image {
    max-width: 100%;
    height: 100%;
    width: 100%;
}

main {
    padding: 20px;
}

.menu-item {
    margin: 20px 0;
}

footer {
    background-color: burlywood;
    color: black;
    padding: 10px 0;
}






```
# OUTPUT:

![Screenshot 2024-12-13 202205](https://github.com/user-attachments/assets/865f480f-caf6-4bbc-8dd6-4f8e1a0ac51c)

![about us 1](https://github.com/user-attachments/assets/be19aa3c-3cb0-46d6-830a-33e6229bbb75)
![About us 2](https://github.com/user-attachments/assets/3d8b2e28-d64a-4d1c-a3ed-e02cd05157ba)
![Menu 2](https://github.com/user-attachments/assets/707fde1f-20eb-4e47-a1f9-1e1e32dd6779)
![Menu 3](https://github.com/user-attachments/assets/29d8e32b-fe12-4709-adb7-63a9387bcfae)

![menu 4](https://github.com/user-attachments/assets/aced0d83-3f3d-45bf-b7fe-e1ac5da99dfb)

![Menu 5](https://github.com/user-attachments/assets/462de236-7f80-46f1-8b6b-4ced7378db0e)

![Contact us](https://github.com/user-attachments/assets/ec252997-c25c-4a91-9514-45ce76016ff4)


![Administration](https://github.com/user-attachments/assets/44540a9c-bb2c-4f6c-ab74-8babaeeb7718)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
