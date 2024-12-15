# Ex.07 Restaurant Website
## Date:14/12/2024

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
```
restweb.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Namma Kadai</title>
    <link rel="stylesheet" href="restweb.css">
</head>
<body>

    <header>
        <div class="header-content">
            <h1>Namma Kadai</h1>
            <p>Welcome to Namma Kadai, where every dish is made with love!</p>
        </div>
    </header>

    <div class="offer-section">
        <h2>Christmas Special Offer!</h2>
        <p>Get 30% off on all orders this Christmas!</p>
    </div>

    <section class="about">
        <h2>About Namma Kadai</h2>
        <p>At Namma Kadai, we bring you fresh, delicious meals with a twist of sweetness. Come and enjoy a delightful dining experience.</p>
    </section>

    <section class="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="dish">
                <img src="briyani.jpg" alt="Dish 1">
                <h3>Briyani</h3>
                <h4>price: ₹250</h4>
            </div>
            <div class="dish">
                <img src="butter naan.jpg" alt="Dish 2">
                <h3>Butter Naan</h3>
                <h4>price: ₹60</h4>
            </div>
            <div class="dish">
                <img src="fried rice.jpg" alt="Dish 3">
                <h3>Fried Rice</h3>
                <h4>price: ₹130</h4>
            </div>
            <div class="dish">
                <img src="grilled chicken.jpg" alt="Dish 4">
                <h3>Grilled Chicken</h3>
                <h4>price: ₹480</h4>
            </div>
            <div class="dish">
                <img src="ice cream.webp" alt="Dish 5">
                <h3>Ice Cream</h3>
                <h4>price: ₹40</h4>
            </div>
            <div class="dish">
                <img src="mutton curry.jpg" alt="Dish 6">
                <h3>Mutton Curry</h3>
                <h4>price: ₹180</h4>
            </div>
            <div class="dish">
                <img src="palkova.jpg" alt="Dish 7">
                <h3>Paalkova</h3>
                <h4>price: ₹60</h4>
            </div>
            <div class="dish">
                <img src="parrota.avif" alt="Dish 8">
                <h3>Parrota</h3>
                <h4>price: ₹20</h4>
            </div>
            <div class="dish">
                <img src="shawarma.jpg" alt="Dish 9">
                <h3>Shawarma</h3>
                <h4>price: ₹110</h4>
            </div>
        </div>
    </section>

    <section class="team">
        <h2>Our Team</h2>
        <div class="team-members">
            <div class="member">
                <img src="aadhav.jpg" alt="CEO">
                <h2>AADHAV</h2>
                <h3>CEO</h3>
            </div>
            <div class="member">
                <img src="simbu.jpg" alt="Team Member 2">
                <h2>STR</h2>
                <h3>MANAGER</h3>
            </div>
            <div class="member">
                <img src="vijay.jpg" alt="Team Member 3">
                <h2>JD</h2>
                <h3>ASSISTANT MANAGER</h3>
            </div>
            <div class="member">
                <img src="priyanka mohan.jpg" alt="Team Member 4">
                <h2>PRIYANKA</h2>
                <h3>CHIEF CHEF</h3>
            </div>
            <div class="member">
                <img src="sai pallavi.jpg" alt="Team Member 5">
                <h2>SAI PALLAVI</h2>
                <h3>HEAD COOK</h3>
            </div>
        </div>
    </section>

    <footer>
        <p>Contact Us:aadhavselvakumaresan@gmail.com</p>
        <p>Designed And Developer By Aadhav</p>
    </footer>

</body>
</html>

restweb.css


body {
    font-family: Arial, sans-serif;
    background-image: url('restaurant-background.jpg');
    background-size: cover;
    background-position: center;
    color: white;
}

header {
    text-align: center;
    padding: 50px;
    background-color: rgba(0, 0, 0, 0.5);
}

header h1 {
    font-size: 50px;
    margin-bottom: 10px;
}

header p {
    font-size: 20px;
    margin-bottom: 20px;
}

.offer-section {
    background-color: rgba(255, 0, 0, 0.7);
    text-align: center;
    padding: 20px;
}

.offer-section h2 {
    font-size: 30px;
    margin-bottom: 10px;
}

.offer-section p {
    font-size: 20px;
}

.about {
    padding: 50px;
    text-align: center;
    background-color: rgba(0, 0, 0, 0.5);
}

.about h2 {
    font-size: 30px;
    margin-bottom: 20px;
}

.menu {
    padding: 50px;
    text-align: center;
    margin: 0 auto;
    color: black;
}

.menu h2 {
    font-size: 30px;
    margin-bottom: 30px;
}

.menu-items {
    display: flex;
    gap: 30px;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

.dish img {
    width: 100%;
    height: 480px;
    border-radius: 18px;
}

.dish h3 {
    margin-top: 10px;
    font-size: 20px;
    color: black;
}

.dish {
    width: 400px;
    height: auto;
}

.dish img {
    width: 100%;
}

.team {
    padding: 50px;
    text-align: center;
    background-color: rgba(0, 0, 0, 0.5);
}

.team h2 {
    font-size: 30px;
    margin-bottom: 30px;
}

.team-members {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 20px;
    border-radius: 18px;
}

.member img {
    width: 100%;
    height: auto;
    border-radius: 50%;
}

.member h3 {
    margin-top: 10px;
    font-size: 20px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: rgba(0, 0, 0, 0.7);
}

footer p {
    font-size: 16px;
}


```

## OUTPUT:
![alt text](<Screenshot (32).png>)
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
