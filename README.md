# Ex.07 Restaurant Website
## Date:27-04-2025

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
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to Zelaya Restaurant, where we serve delicious meals in a warm and friendly atmosphere.">
    <title>Zelaya Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #d8bfaa;
        }

        header {
            background-color: goldenrod;
            color: color-mix(in hs shorter hue, color percentage, color percentage);
            padding: 1em 0;
            text-align: center;
        }

        nav {
            background-color: #000000;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }

        section {
            padding: 20px;
        }

        .hero {
            background-image: url(firsts.jpg);
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .menu-item {
            background-color: rgba(128, 117, 117, 0.829);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .menu-img {
            width: 100%;
            max-width: 250px;  
            height: auto;
            border-radius: 30px;
            display: block;
            margin: 0 auto 15px; 
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>"Step into the world of Zelaya."</h1>
    <p>“Let every bite be an exploration of taste and refinement.”</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero">
    <h2></h2>
</section>

<section id="menu">
    <h2>Zelaya's feast</h2>
    <div class="menu">
        <div class="menu-item">
            <img src="momos.jpg" alt="Chicken Momos" class="menu-img">
            <h3>Chicken Momos</h3>
            <p>Tender dumplings filled with flavorful minced chicken, steamed to perfection and served with a spicy dipping sauce.</p>
            <p><strong>Price: ₹300</strong></p>
        </div>
        <div class="menu-item">
            <img src="img2.jpg" alt="Pepperoni Pizza" class="menu-img">
            <h3>Pepperoni Pizza</h3>
            <p>A classic favorite topped with zesty pepperoni slices, rich tomato sauce, and melted mozzarella cheese on a crispy crust.</p>
            <p><strong>Price: ₹380</strong></p>
        </div>
        <div class="menu-item">
            <img src="img3.jpg" alt="Spaghetti Bolognese" class="menu-img">
            <h3>Spaghetti Bolognese</h3>
            <p>Classic Italian pasta tossed in a hearty, slow-cooked meat sauce made with tomatoes, garlic, herbs, and a touch of red wine.</p>
            <p><strong>Price: ₹430</strong></p>
        </div>
        <div class="menu-item">
            <img src="img8.jpg" alt="Mutton Biryani" class="menu-img">
            <h3>Mutton Biryani</h3>
            <p>Fragrant basmati rice layered with tender, spiced mutton, slow-cooked with saffron, herbs, and caramelized onions for a rich and aromatic feast.</p>
            <p><strong>Price: ₹450</strong></p>
        </div>

        <div class="menu-item">
            <img src="img4.jpg" alt="Butter Chicken Lasagna" class="menu-img">
            <h3>Butter Chicken Lasagna</h3>
            <p>Layers of pasta sheets, rich meat or vegetable sauce, creamy béchamel, and melted cheese baked to golden perfection.</p>
            <p><strong>Price: ₹520</strong></p>
        </div>
        <div class="menu-item">
            <img src="img9.jpg" alt="Classic Zinger Burger" class="menu-img">
            <h3>Classic Zinger Burger</h3>
            <p>Crispy, spicy fried chicken fillet tucked in a soft bun with lettuce, mayo, and a bold, flavorful crunch in every bite.</p>
            <p><strong>Price: ₹340</strong></p>
        </div>
        <div class="menu-item">
            <img src="pasta.jpg" alt="White Sauce Pasta" class="menu-img">
            <h3>White Sauce Pasta</h3>
            <p>Creamy and rich, this pasta is coated in a velvety white sauce made with butter, flour, and cream, often enhanced with garlic, cheese, and a sprinkle of herbs for extra flavor.</p>
            <p><strong>Price: ₹590</strong></p>
        </div>
        <div class="menu-item">
            <img src="wrap.jpg" alt="Chicken Wrap" class="menu-img">
            <h3>Chicken Wrap</h3>
            <p>Tender grilled chicken, fresh veggies, and a zesty sauce wrapped in a soft tortilla for a delicious and portable meal.</p>
            <p><strong>Price: ₹460</strong></p>
        </div>

        <div class="menu-item">
            <img src="img11.jpg" alt="Tiramisu" class="menu-img">
            <h3>Tiramisu</h3>
            <p>A classic Italian dessert with layers of espresso-soaked ladyfingers, creamy mascarpone cheese, and a dusting of cocoa powder, creating a rich and indulgent treat.</p>
            <p><strong>Price: ₹550</strong></p>
        </div>
        <div class="menu-item">
            <img src="mojito.jpg" alt="Mint Mojito" class="menu-img">
            <h3>Mint Mojito</h3>
            <p>A refreshing blend of mint leaves, lime, sugar, and soda water, served over ice with a hint of sweetness and a burst of citrus. Perfect for a cool and revitalizing drink!</p>
            <p><strong>Price: ₹330</strong></p>
        </div>

        <div class="menu-item">
            <img src="brownie.jpg" alt="Sizzling Brownie" class="menu-img">
            <h3>Sizzling Brownie</h3>
            <p>A warm, fudgy brownie served on a sizzling hot plate, topped with a scoop of vanilla ice cream and drizzled with chocolate sauce, creating a delightful contrast of hot and cold with every bite.</p>
            <p><strong>Price: ₹490</strong></p>
        </div>
        <div class="menu-item">
            <img src="cake.jpg" alt="Molten Chocolate Lava Cake" class="menu-img">
            <h3>Molten Chocolate Lava Cake</h3>
            <p>A decadent chocolate dessert with a gooey, flowing center, served warm with a scoop of ice cream and a touch of chocolate syrup.</p>
            <p><strong>Price: ₹440</strong></p>
        </div>

        <div class="menu-item">
            <img src="falooda.jpg" alt="Strawberry Falooda" class="menu-img">
            <h3>Strawberry Falooda</h3>
            <p>A sweet and creamy dessert drink made with rose syrup, fresh strawberries, basil seeds, and topped with a scoop of vanilla ice cream, offering a refreshing and indulgent treat </p>
            <p><strong>Price: ₹280</strong></p>
        </div>
        <div class="menu-item">
            <img src="img13.jpg" alt="Chocolate Chip Waffle" class="menu-img">
            <h3>Chocolate Chip Waffle</h3>
            <p>A delicious and indulgent variation of the classic waffle, with pockets of gooey chocolate chips in every bite.</p>
            <p><strong>Price: ₹290</strong></p>
        </div>
        <div class="menu-item">
            <img src="img12.jpg" alt="Almond Croissant Royale" class="menu-img">
            <h3>Almond Croissant Royale</h3>
            <p>A regal treat featuring our buttery, golden croissant, filled with almond cream and topped with toasted almonds. The perfect balance of crisp, buttery layers and a nutty, rich filling.</p>
            <p><strong>Price: ₹310</strong></p>
        </div>
        <div class="menu-item">
            <img src="img14.jpg" alt="Frozen Choco Milkshake" class="menu-img">
            <h3>Frozen Choco Milkshake</h3>
            <p>Dive into a world of frozen chocolate perfection — our Frozen Choco Milkshake is a creamy, chilled treat that delivers rich chocolate flavor with every frosty sip. A true indulgence for chocolate lovers!</p>
            <p><strong>Price: ₹350</strong></p>
        </div>
    </div>
</section>


<section id="about">
    <h2>About Us</h2>
    <p>Zelaya Restaurant is where every bite is an exploration of taste and refinement. We craft exceptional dishes using the finest ingredients, blending bold flavors with elegant simplicity. Our menu celebrates culinary artistry, offering a unique experience for every guest.At Zelaya, we believe dining is not just about food — it’s about creating moments and memories. From the inviting atmosphere to impeccable service, every detail is designed to make you feel at home. Whether you’re here for a casual meal or a special celebration, we promise an experience that will stay with you long after you leave.Join us at Zelaya for a journey of flavor, warmth, and unforgettable moments.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email:ZaleyaRestaurant@gmail.com</p>
    <p>Phone:7010630258</p>
    <p>Location:new main road,chennai</p>
</section>

<footer>
    <p>&copy; Zaleya Restaurant. All Rights Reserved.</p>
</footer>

</body>
</html>
```
## OUTPUT:

![Screenshot 2025-04-27 194305](https://github.com/user-attachments/assets/930a0f90-fdf1-4cd5-b04a-1aa20fe5cff8)

![Screenshot 2025-04-27 194329](https://github.com/user-attachments/assets/25ac9797-6094-476c-8fdb-63c71e2b429a)

![Screenshot 2025-04-27 194353](https://github.com/user-attachments/assets/1e40ee34-b0f6-4043-aaa8-01779d894a61)

![Screenshot 2025-04-27 194411](https://github.com/user-attachments/assets/7a5affc5-9247-4c5e-80d7-e48f4cb1cbae)

![Screenshot 2025-04-27 194429](https://github.com/user-attachments/assets/0f396709-25fe-4eae-a4fb-371b0daf46cd)

![Screenshot 2025-04-27 194506](https://github.com/user-attachments/assets/6323e2cd-b0f2-4704-a1a0-daf9b11fde99)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
