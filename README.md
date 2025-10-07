# Ex.07 Restaurant Website
## Date:7.10.2025

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
main.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Red Dragon Chinese Restaurant | Home</title>
  <link rel="stylesheet" href="main.css">
</head>
<body>
  <header>
    <h1>The Golden Table Restaurent</h1>
    <nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Admin</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="home">
    
    <h2></color>Welcome to The Golden Table</h2>
    <p>Where Every Meal is a Golden Experience. Gather Around the Golden Table.</p>
    <img src="Pepperoni Pizza_1_compressed.jpg">
  </section>

  <footer>
    <p>© 2025 The Golden Table | Designed by <strong>Infant Vijay(25017478)</strong></p>
  </footer>
</body>
</html>

main.css



body {
  background-image:url('Pepperoni Pizza_1_compressed.jpg');
  font-family: Arial, sans-serif;
  background-color: white;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: rgb(207, 114, 22);
  padding: 20px;
  border-bottom: 3px solid rgb(244, 241, 241);
}

h1 {
    position:relative;
  color: rgb(243, 238, 238);
  right:30%;
  top:20%;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left:30%;
  
}

nav a.active,
nav a:hover {
  color: red;
  position: relative;
  left:30%;
}


.home {
  padding: 40px;
}

.home img {
  width: 500px;
  border-radius: 10px;
  margin-top: 20px;
  border: 3px solid red;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid red;
}

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Golden Table - Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans&family=Playfair+Display&family=Roboto+Mono&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <section class="menu-section">
        <h1>Our Menu</h1>
        <div class="category">
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/725990/pexels-photo-725990.jpeg" alt="Calamari">
                <h3>Calamari</h3>
                <p>Fried squid served with marinara sauce. &#8377 299;</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/533325/pexels-photo-533325.jpeg" alt="Prosciutto e Melone">
                <h3>Prosciutto e Melone</h3>
                <p>Thinly sliced prosciutto wrapped around sweet melon. &#8377 399</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/1437267/pexels-photo-1437267.jpeg" alt="Margherita Pizza">
                <h3>Margherita Pizza</h3>
                <p>Classic pizza with fresh tomatoes, mozzarella, and basil. &#8377 199</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/2619967/pexels-photo-2619967.jpeg" alt="Spaghetti Carbonara">
                <h3>Spaghetti Carbonara</h3>
                <p>Creamy pasta with pancetta, egg, and Parmesan. &#8377 299</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/1487511/pexels-photo-1487511.jpeg" alt="Lasagna">
                <h3>Lasagna</h3>
                <p>Layers of pasta, meat sauce, and melted cheese. &#8377 299</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/2133989/pexels-photo-2133989.jpeg" alt="Fettuccine Alfredo">
                <h3>Fettuccine Alfredo</h3>
                <p>Creamy Alfredo sauce over fettuccine pasta. &#8377 199</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/323682/pexels-photo-323682.jpeg" alt="Pesto Gnocchi">
                <h3>Pesto Gnocchi</h3>
                <p>Soft potato dumplings in a basil pesto sauce. &#8377 299</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/2144112/pexels-photo-2144112.jpeg" alt="Tiramisu">
                <h3>Tiramisu</h3>
                <p>Rich coffee-flavored dessert with mascarpone and cocoa. &#8377 499</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/338713/pexels-photo-338713.jpeg" alt="Espresso">
                <h3>Espresso</h3>
                <p>Rich, bold Italian coffee. &#8377 199</p>
            </div>
            <div class="menu-item">
                <img src="mango-mojito.jpg" alt="Chicken Parmesan">
                <h3>Mango Mogito</h3>
                <p>Fresh and refresment. &#8377 99</p>
            </div>
            <div class="menu-item">
                <img src="mutton-biriyani-recipe.jpeg" alt="Caprese Salad">
                <h3>Mutton Biriyani</h3>
                <p>Fresh Mutton, Rice, Spices. &#8377 299</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/1351238/pexels-photo-1351238.jpeg" alt="Lemon Sorbet">
                <h3>Lemon Sorbet</h3>
                <p>Refreshing lemon dessert with a zesty finish. &#8377 159</p>
            </div>
        </div>
    </section>
    <footer>
        <h4>&copy; The Golden Table 2025 | Infant Vijay | 25017478</h4>
    </footer>
</body>
</html>

menu.css

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Open Sans', sans-serif;
    color: #2A2D43;
}

.menu-section {
    padding: 50px; 
    text-align: center;
}

.menu-section h1 {
    font-family: 'Playfair Display', serif;
    font-size: 2.5rem;
    color: #2A2D43;
    margin-bottom: 40px;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.2);
}

.category {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    padding: 20px;
}

.menu-item {
    background: #FAF9F6;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    animation: scaleUp 1s ease-out forwards;
}

.menu-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 15px;
}

.menu-item h3 {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    color: #2A2D43;
    margin-bottom: 10px;
}

.menu-item p {
    font-family: 'Open Sans', sans-serif;
    font-size: 1rem;
    color: #555;
}

footer {
    background-color: #2e2e2e;
    color: #FAF9F6;
    text-align: center;
    padding: 20px;
    font-family: 'Roboto Mono', monospace;
    margin-top: 40px;
}

#navbar {
    display: flex;
    flex-direction: column;
    position: absolute;
    top: 70px;
    right: 0;
    background-color: #A52A2A;
    width: 100%;
    padding: 20px;
}
admin.html

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        <h1>Admin Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html" class="active">Admin</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Meet Our Team</h2>

        <div class="team">
            <div class="member">
                <img src="Gordon-Ramsay.webp"alt="Gordan Ramsay">
                <h3>Gordan Ramsay</h3>
                <b>CEO</b>
            </div>

            <div class="member">
                <img src="John_Wick_Keanu.jpeg" alt="John Wick">
                <h3>John Wick</h3>
                <b>Marketing Manager</b>
            </div>

            <div class="member">
                <img src= "tom.jpg"alt="Taamu">
                <h3>Tom Cruise</h3>
                <b>Operations Manager</b>
            </div>

            <div class="member">
                <img src="emma.jpg" alt="Venkat">
                <h3>Emma Watson</h3>
                <b>HR Manager</b>
            </div>

            <div class="member">
                <img src= "loki.jpg"alt="Gorden">
                <h3>Tom Hiddleston</h3>
                <b>Executive Chef</b>
            </div>

            <div class="member">
                <img src="800px-Emma_Myers.jpg" alt="Newton">
                <h3>Emma Myres</h3>
                <b>Customer Service Manager</b>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 The Golden Restaurent | Designed by <strong>Infant Vijay(25017478)</strong></p>
    </footer>
</body>
</html>

admin.css

admin.css

body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #fff;
}

/* Header */
header {
    background-color: #FFD500;
    color: rgb(248, 245, 245);
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: black;
    font-weight: 600;
}

nav ul li a.active {
    text-decoration: underline;
}

/* Main Section */
main {
    text-align: center;
    padding: 40px 20px;
}

main h2 {
    color: #222;
    font-size: 1.8em;
    margin-bottom: 40px;
}

/* Team Cards */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.member {
    background-color: #cc9807;
    color: white;
    width: 150px;
    padding: 20px;
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-8px);
}

.member img {
    width: 80%;
    height: 230px;
    object-fit: cover;
    
    border: 4px solid rgb(164, 17, 54);
}

.member h3 {
    margin-top: 15px;
    color: #fff;
    font-size: 1.2em;
}

.member p {
    color: #0f0c00;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 0.9em;
}

contact.html



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | Namma Thalapathi Restaurant</title>
  <link rel="stylesheet" href="contact.css">
</head>
<body>
  <header>
    <h1>CONTACT US</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Admin</a></li>
        <li><a href="contact.html" class="active">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>Contact Us</h2>
    <p> 45,Deiva Nager, Villupuram</p>
    <p> 9092091255</p>
    <p>✉ abcd123@gmail.com</p>
  </section>

  <footer>
    <p>© 2025 The Golden Table | Designed by <strong>Infant Vijay(25017478)</strong></p>
  </footer>
</body>
</html>

contact.css



body {
  font-family: Arial, sans-serif;
  background-color: rgb(220, 131, 7);
  color: rgb(12, 6, 2);
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid rgb(229, 229, 235);
}

h1 {
  color: rgb(234, 234, 240);
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: rgb(206, 69, 10);
}

.contact {
  padding: 50px;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid blue;
}

```


## OUTPUT:

![alt text](<restaurent/Screenshot (41).png>)

![alt text](<restaurent/Screenshot (42).png>)

![alt text](<restaurent/Screenshot (43).png>)

![alt text](<restaurent/Screenshot (44).png>)

![alt text](<restaurent/Screenshot (45).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
