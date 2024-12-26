# Ex.07 Restaurant Website
# Date:8/11/2024
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
Home page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>FUSION FORK</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#menu">Menu</a></li>
                <li><a href="C:\Users\admin\Downloads\administration.html">Administration</a></li>
                <li><a href="C:\Users\admin\Downloads\administration.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="menu">
        <h2>Menu</h2>
        <div class="menu-items">
            <div class="menu-item">Italian Cussine <a href="C:\Users\admin\Downloads\italian .html"><img src="C:\Users\admin\Downloads\italian cussine.jpeg"></a></div>
            <div class="menu-item">Indian Cussine<a href="C:\Users\admin\Downloads\italian .html"><img src="C:\Users\admin\Downloads\indian cussine.jpeg"></a></div>
            <div class="menu-item">Pastries<a href="C:\Users\admin\Downloads\italian .html"><img src="C:\Users\admin\Downloads\pasteries.jpeg"></a></div>
            <div class="menu-item">Beverages<a href="C:\Users\admin\Downloads\italian .html"><img src="C:\Users\admin\Downloads\beverages.webp"></a></div>
           
        </div>
    </section>
    <footer>
        <p>&copy; 2024 My Restaurant - Designed by Alageshwari</p>
    </footer>
</body>
</html>

Menu page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <section id="menu">
        <h2>Italian Cussine</h2>
        <div class="menu-items">
            <div class="menu-item">Pasta <a href="C:\Users\admin\Downloads\pasta.html"><img src="C:\Users\admin\Downloads\pasta.jpeg"></a></div>
            <div class="menu-item">Pizza<a href="C:\Users\admin\Downloads\pizza.html"><img src="C:\Users\admin\Downloads\pizza.jpeg"></a></div>
            <div class="menu-item">Soups<a href="C:\Users\admin\Downloads\soups.html"><img src="C:\Users\admin\Downloads\soups.jpeg"></a></div>
            <div class="menu-item">Sea foods<a href="C:\Users\admin\Downloads\sea foods.html"><img src="C:\Users\admin\Downloads\sea foods.jpeg"></a></div>
           
        </div>
    </section>
    <section id="menu">
        <h2>Indian Cussine</h2>
        <div class="menu-items">
            <div class="menu-item">North Indian<a href="C:\Users\admin\Downloads\north indian.html"><img src="C:\Users\admin\Downloads\north indian.jpeg"></a></div>
            <div class="menu-item">Vegetarian Dishes<a href="C:\Users\admin\Downloads\vegetarian dishes.html"><img src="C:\Users\admin\Downloads\vegetarian dishes.jpeg"></a></div>
            <div class="menu-item">South Indian<a href="C:\Users\admin\Downloads\south indian.html"><img src="C:\Users\admin\Downloads\south indian.jpeg"></a></div>
            <div class="menu-item">Sweets<a href="C:\Users\admin\Downloads\sweets.html"><img src="C:\Users\admin\Downloads\sweets.jpeg"></a></div>
           
        </div>
    </section>
    <section id="menu">
        <h2>Pastries</h2>
        <div class="menu-items">
            <div class="menu-item">Sweet Pastries<a href="C:\Users\admin\Downloads\sweet pastries.html"><img src="C:\Users\admin\Downloads\sweet pastries.jpeg"></a></div>
            <div class="menu-item">Savory Pastries<a href="C:\Users\admin\Downloads\savory pastries.html"><img src="C:\Users\admin\Downloads\savory pastries.jpeg"></a></div>
            <div class="menu-item">Miniature Pastries<a href="C:\Users\admin\Downloads\miniature pastries.html"><img src="C:\Users\admin\Downloads\miniature pastries.jpeg"></a></div>
            <div class="menu-item">Experimental Pastries<a href="C:\Users\admin\Downloads\experimental pastries.html"><img src="C:\Users\admin\Downloads\experimental pasteries.jpeg"></a></div>
           
        </div>
    </section>
    <section id="menu">
        <h2>Beverages</h2>
        <div class="menu-items">
            <div class="menu-item">Hot Beverages<a href="C:\Users\admin\Downloads\hot beverages.html"><img src="C:\Users\admin\Downloads\hot beverages.jpeg"></a></div>
            <div class="menu-item">Cold Beverages<a href="C:\Users\admin\Downloads\cold beverages.html"><img src="C:\Users\admin\Downloads\cold beverages.jpeg"></a></div>
            <div class="menu-item">Mocktails<a href="C:\Users\admin\Downloads\mocktails.html"><img src="C:\Users\admin\Downloads\mocktails.jpeg"></a></div>
            <div class="menu-item">Dessert Drinks<a href="C:\Users\admin\Downloads\dessert drinks.html"><img src="C:\Users\admin\Downloads\dessert drinks.jpeg"></a></div>
           
        </div>
    </section>
</body>
</html>

styles1.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #639293;
    color: black;
    padding: 10px 0;
    text-align: center;
}

.banner {
    background-image: url("Restaurant Banner.jpg"); /* Change this to your banner image */
    height: 200px;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 2.5em;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 50px;
    background-color: rgb(170, 181, 185);
    border-radius: 8px;
}

.menu-items {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 3fr));
    gap: 30px;
}

.menu-item {
    background-color: rgb(174, 181, 185);
    padding: 35px;z
    border-radius: 5px;
    text-align: top;
}
.menu-item img{
    width: 250px;
    height: 250px;
    border-radius: 15px;
    align-content: center;
    align-items: center;
}

.admin {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.admin-member {
    text-align: center;
    width: 150px;
}

.admin-member img {
    width: 100%;
    border-radius: 50%;
}

pastas
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>PASTAS</h1>
    </header>
    <section id="menu">
        <h2>Spaghetti<br><p>₹150</p><p>Experience the ultimate Italian comfort food with our signature Spaghetti dishes</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\spaghetti.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Fusilli<br><p> &emsp;&ensp;₹299</p><p>Indulge in our irresistible Fusilli Pasta, with perfect spirals that hold every drop of sauce.</h2></p>
        <div class="menu-item">
            &emsp;&emsp13;<img src="C:\Users\admin\Downloads\fucilli.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Macaroni<br><p>&emsp;&ensp;₹200</p><p>Indulge in the ultimate comfort food – our freshly prepared Macaroni Dishes.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\macaroni.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Trofie<br><p>&emsp;&ensp;₹499</p><p>Our handmade Trofie, crafted to perfection and tossed in rich, flavorful sauces. </h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\trofie.jpeg">
        </div>
    </section>
</body>
</html>

sweets
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>SWEETS</h1>
    </header>
    <section id="menu">
        <h2>Rasgulla<br><p>₹50-</p><p>Indulge in the soft, spongy perfection of freshly made Rasgullas.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\rasgulla.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Kaju Katli<br><p> &emsp;&ensp;₹80</p><p>Our Kaju Katli is made with 100% premium cashews.</h2></p>
        <div class="menu-item">
            &emsp;&emsp13;<img src="C:\Users\admin\Downloads\kaju katli.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Gulab Jamun<br><p>&emsp;&ensp;₹100</p><p>Come savor the taste of tradition and let every bite melt in your mouth!</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\gulab jamun.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Mysore Pak<br><p>&emsp;&ensp;₹90</p><p>Indulge in the rich, buttery goodness of authentic Mysore Pak.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\mysore pak.jpeg">
        </div>
    </section>
</body>
</html>

Miniature Pastries
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>MINIATURE PASTRIES</h1>
    </header>
    <section id="menu">
        <h2>Macarons<br><p>₹130</p><p>From classic vanilla and rich chocolate to vibrant raspberry and pistachio</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\Macarons.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Miniature apple pies<br><p> &emsp;&ensp;₹140</p><p>Fresh, warm apples spiced with cinnamon, all nestled in a buttery, golden crust.</h2></p>
        <div class="menu-item">
            &emsp;&emsp13;<img src="C:\Users\admin\Downloads\mini apple pies.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Shortbread Cookies<br><p>&emsp;&ensp;₹160</p><p>Made with finest ingredients, each bite offers the perfect balance of sweetness.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\shortbread cookies.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Chocolate Tarts<br><p>&emsp;&ensp;₹190</p><p>Our Mini Chocolate Tarts are the ultimate treat to end your meal on a high note.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\chocolate tarts.jpeg">
        </div>
    </section>
</body>
</html>

Hot Beverages
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>HOT BEVERAGES</h1>
    </header>
    <section id="menu">
        <h2>Hot Chocolate<br><p>₹140</p><p>Served piping hot, topped with whipped cream, marshmallows, or a drizzle of caramel.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\hot chocolate.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Atole<br><p> &emsp;&ensp;₹190</p><p>Discover Atole, a traditional Mexican hot beverage made with creamy masa.</h2></p>
        <div class="menu-item">
            &emsp;&emsp13;<img src="C:\Users\admin\Downloads\atole.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Hot Cider<br><p>&emsp;&ensp;₹140</p><p>Infused with a hint of cinnamon and a touch of citrus. it's the blend of sweet.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\hot cider.jpeg">
        </div>
    </section>
    <section id="menu">
        <h2>&emsp;&ensp;Special Coffees<br><p>&emsp;&ensp;₹90</p><p>From velvety Turkish delights to frothy Caramel Cappuccinos, and bold Espresso Martinis.</h2></p>
        <div class="menu-item">
            <img src="C:\Users\admin\Downloads\special coffees.jpeg">
        </div>
    </section>
</body>
</html>

styles.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #2663a5;
    color: white;
    padding: 10px 0;
    text-align: center;
}

.banner {
    background-image: url("Restaurant Banner.jpg"); /* Change this to your banner image */
    height: 200px;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 2.5em;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

section {
    padding: 50px;
    margin: 40px;
    background-color: white;
    border-radius: 8px;
}

.menu-items {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 3fr));
    gap: 10px;
}

.menu-item {
    background-color: white
    padding: 50px;
    border-radius: 5px;
    text-align: center;
    justify-content: center ;
}
.menu-item img{
    width: 220px;
    height: 220px;
    padding: 10px;
    border-radius: 15px;

}

.admin {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.admin-member {
    text-align: center;
    width: 150px;
}

.admin-member img {
    width: 100%;
    border-radius: 50%;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
#menu{
    padding: 50px;
    margin: 50px;
    background :#7d92b4;
    border-radius: 8px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    color: rgb(13, 9, 13);
}

Administration page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us & Contact Us</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #343a40;
            color: #ffffff;
            padding: 1.5rem 0;
            text-align: center;
        }
        .container {
            margin: 2rem auto;
            max-width: 900px;
            padding: 2rem;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #343a40;
            border-bottom: 2px solid #007bff;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }
        p {
            line-height: 1.6;
            margin-bottom: 1rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        ul {
            list-style: disc;
            padding-left: 20px;
        }
        .form-group {
            margin-bottom: 1rem;
        }
        .form-group label {
            font-weight: bold;
            display: block;
            margin-bottom: 0.5rem;
        }
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.75rem;
            font-size: 1rem;
            border: 1px solid #ced4da;
            border-radius: 5px;
            background-color: #f8f9fa;
        }
        button {
            background-color: #007bff;
            color: white;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <!-- About Us Section -->
    <header>
        <h1>About Us</h1>
    </header>
    <div class="container">
        <div class="section">
            <h2>Who We Are</h2>
            <p>Welcome to our restaurant! We take pride in offering exceptional dining experiences with our expertly crafted dishes, fresh ingredients, and warm hospitality.</p>
        </div>
        <div class="section">
            <h2>Our Achievements</h2>
            <ul>
                <li>Rated as the top dining spot in the city for three consecutive years.</li>
                <li>Featured in numerous culinary magazines and food blogs.</li>
                <li>Renowned for our innovative fusion cuisine and signature dishes.</li>
            </ul>
        </div>
        <div class="section">
            <h2>Future Missions</h2>
            <p>Our mission is to expand our reach and bring our exceptional dining experience to more locations while maintaining the highest standards of quality and service.</p>
        </div>
        <div class="section">
            <h2>Awards & Recognitions</h2>
            <ul>
                <li>Michelin Star Award 2023.</li>
                <li>Best Fine Dining Restaurant - Culinary Excellence Awards 2022.</li>
                <li>People's Choice Award - Gourmet Magazine 2021.</li>
            </ul>
        </div>
    </div>

    <!-- Contact Us Section -->
    <header>
        <h1>Contact Us</h1>
    </header>
    <div class="container">
        <h2>Get in Touch</h2>
        <p>We would love to hear from you! Reach out with any questions, feedback, or to make a reservation.</p>
        <ul>
            <li><strong>Phone:</strong> +1-234-567-890</li>
            <li><strong>Email:</strong> contact@restaurant.com</li>
            <li><strong>Address:</strong> 123 Foodie Lane, Gourmet City</li>
        </ul>
    </div>

</body>
</html>
```

# OUTPUT:

![Screenshot (71)](https://github.com/user-attachments/assets/48a712fb-0965-4295-8c01-1d1fc3425beb)

![Screenshot (72)](https://github.com/user-attachments/assets/81670e45-a051-45a6-a4c4-c42774f66677)

![Screenshot (73)](https://github.com/user-attachments/assets/7c468e08-737f-4537-ad44-a11fead3f9c0)

![Screenshot (74)](https://github.com/user-attachments/assets/aaebafa8-dba1-43cd-a3e4-e5cc1bad8cf5)

![Screenshot (75)](https://github.com/user-attachments/assets/a0b295b1-944a-4c6a-8d64-8d3c0f7833e0)

![Screenshot (76)](https://github.com/user-attachments/assets/b0dd3a39-e15f-48b4-a211-62d6aec59208)

![Screenshot (77)](https://github.com/user-attachments/assets/83afb703-6d12-499e-8c3f-219809e453ec)

![Screenshot (78)](https://github.com/user-attachments/assets/f2953637-821a-44e5-ae23-849aebc52a63)

![Screenshot (79)](https://github.com/user-attachments/assets/ed3a4751-20da-42d1-8eb7-168d1bdac0f4)

![Screenshot (80)](https://github.com/user-attachments/assets/e8c32386-1713-4e52-9b9e-fa6bdeaacc4b)

![Screenshot (81)](https://github.com/user-attachments/assets/22aa0193-f933-4c81-8bad-1534ceb18f9c)

![Screenshot (82)](https://github.com/user-attachments/assets/d196eb35-bfd7-4320-a5ae-6ff46b43c602)

![Screenshot (83)](https://github.com/user-attachments/assets/18174762-c4a7-4134-b601-f55807156d9f)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
