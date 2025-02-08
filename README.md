# Ex.07 Restaurant Website
## Date:08.02.2025

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



contact.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">About us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Team</a></li>
            </ul>
        </nav>
    </header>
</head>
<body>
   
    <section>
        <p>Email: rajkumarkpm2006@gmail.com</p>
        <p>Phone: 9342603456</p>
        <p>Address:11,sethurayan nagar,kanchipuram</p>
    </section>
    <img src="contact us.jpg" width="350px" height="150px" align="left">
    <footer>
        <p>By T rajkumar(24004992)</p>
        <p>All Rights Reserved</p>
    </footer>
</body>
</html>

index.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<header>
    <h1 style="font-family: cursive;"><i>Italiano Restaurant</i></h1>
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="team.html">Team</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>
<body>
   
    <section id="about">
        <h2>About Us</h2>
        <img src="about img.jpg" align="left" width="400px" height="200px">
        <p>Over 3 Decades, <b>Italiano Restaurant</b> has pioneered Italian cuisine in India. With 50 outlets in 4 countries, we are India’s largest home grown italian brand bringing you a delicious menu of Pizzas, Pastas, Appetizers, Cheeses, Wines & much more.

            Italian food is simple yet sophisticated, using few ingredients to make a dish so flavourful you keep coming back for more. Inspired by Italy’s finest family chefs, we bring you the warmth & love of Italian Cuisine directly to your home.</p>
    </section>
    <div class="image-row">
        
        <img src="menu1.jpg" alt="Abt" width="420" height="250">
    </div>
    

</body>
</html>


menu.html


<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu</title>
    <link rel="stylesheet" href="styles.css">
    <header>
        <h1>Our Menu</h1>
        <nav>
            <ul>
                <li><a href="index.html">About us</a></li>
                <li><a href="team.html">Team</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
</head>
<body>  
    <section>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="lasagna.webp" alt="" width="150">
                <p>lasagna</p>
            </div>
            <div class="menu-item">
                <img src="Crostata.webp" alt="" width="150">
                <p>Crostata with Dark Chocolate</p>
            </div>
            <div class="menu-item">
                <img src="Polenta.webp" alt="" width="150">
                <p>Pork Ragù Over Creamy Polenta</p>
            </div>
            <div class="menu-item">
                <img src="carpese.webp" alt="" width="150">
                <p>Carpese Salad</p>
            </div>
            <div class="menu-item">
                <img src="stuff.webp" alt="" width="150">
                <p>Stuffed peppers</p>
            </div>
            <div class="menu-item">
                <img src="old-school-tiramisu.webp" alt="" width="150">
                <p>Tiramisu</p>
            </div>
            <div class="menu-item">
                <img src="fettuccine-alfredo.webp" alt="" width="150">
                <p>Fettuccine Alfredo</p>
            </div>
            <div class="menu-item">
                <img src="steak.png" alt="" width="150">
                <p>Grilled Steak</p>
            </div>
            <div class="menu-item">
                <img src="pasta.png" alt="" width="150">
                <p>Italian Pasta</p>
            </div>
            <div class="menu-item">
                <img src="marinated-zucchini-with-hazelnuts-and-ricotta.webp" alt="" width="150">
                <p>Marinated Zucchi</p>
            </div>
            <div class="menu-item">
                <img src="20221013-1222-13257-AOTT.webp" alt="" width="150">
                <p>Cuccinati</p>
            </div>
            <div class="menu-item">
                <img src="panna-cotta-with-cherries-and-lemon.webp" alt="" width="150">
                <p>Panna Cotta</p>
            </div>
        </div>        
    </section>
</body>
</html>


team.html


<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team</title>
    <link rel="stylesheet" href="styles.css">
</head>
<header>
    <h1 style="font-family: cursive;"><i>Our Team</i></h1>
    <nav>
        <ul>
            <li><a href="index.html">About us</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>
<body>
    
    <section>
        <div class="team">
            <div class="team-member">
                <img src="myphoto.jpg" alt="Owner" class="team-img">
                <p><b>T Rajkumar</b></p>
                <p>Manager</p>
            </div>
            <div class="team-member">
                <img src="bezos.jpg" alt="Oops" class="team-img">
                <p><b>Jeff Bezos</b></p>
                <p>Head Chef </p>
            </div>
            <div class="team-member">
                <img src="elonmusk.jpg" alt="Oops" class="team-img">
                <p><b>Elon musk</b></p>
                <p>Cashier</p>
            </div>
            <div class="team-member">
                <img src="waiter1.jpg" alt="W" class="team-img">
                <p><b>Smith</b></p>
                <p>Waiter</p>
            </div>
            <div class="team-member">
                <img src="waiter 2.jpg" alt="W" class="team-img">
                <p><b>Jack</b></p>
                <p>Table cleaner</p>
            </div>
            <div class="team-member">
                <img src="billgates.jpg" alt="Microsoft" class="team-img">
                <p><b>Gates</b></p>
                <p>Assistant(Micro) chef</p>
            </div>
        </div>
    </section>
</body>
</html>



style.css




body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.9;
    font-size: large;
    background-image:url(bg3.jpg);
    background-size: cover; 
    background-position: center;
    background-repeat: no-repeat; 
    height: 100vh;
    color: rgb(213, 215, 222);
}


header {
    background-image:url(bg2.avif) ; 
    color: rgb(246, 240, 245);
    padding: 10px 0;
    text-align: center;
    font-style: oblique;
    border-radius: 20px;
}



nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: rgb(241, 17, 17);
    text-decoration: none;
    font-weight: bold;
    font-size: larger;
}

section {
    padding: 20px;
    margin: 30px;
}



footer {
    text-align: center;
    padding: 10px 0;
    background: #373d2d;
    color: rgb(153, 136, 136);
    position: fixed;
    bottom: 0;
    width: 100%;
    

    
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(6, 1fr); 
    gap: 20px;
    margin: 20px auto;
    text-align: center;
}

.menu-item img {
    width: 150px;
    height: 150px; 
    object-fit: cover; 
    border: 2px solid #fff; 
    border-radius: 5px; 
    display: block; 
    margin: 0 auto; 
}

.menu-item p {
    margin-top: 10px; 
    font-size: 17px; 
    color: #c7ecde; 
    font-weight: 800;
}

.team {
    display: flex;
    justify-content: center;
    flex-wrap: wrap; 
    gap: 75x; 
    margin: 10px auto;
    max-width: 1200px; 
}

.team-member {
    text-align:center;
    width: 200px; 
}

.team-img {
    width: 150px; 
    height: 150px; 
    object-fit: cover; 
    border-radius: 50%;
    margin-bottom: 10px;
}

.team-member p {
    margin: 5px 0;
    font-size: 24px;
    color: #fcf3f3;
}
.image-row {
    display: flex; 
    justify-content: center; 
    gap: 25px;
    margin: 20px 0; 
}

.image-row img {
    border: 6px solid #0a0a0a; 
    border-radius: 20px; 
}


```


## OUTPUT:
![alt text](<Screenshot (64).png>)
 ![alt text](<Screenshot (65).png>) 
 ![alt text](<Screenshot (66).png>) 
 ![alt text](<Screenshot (67).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
