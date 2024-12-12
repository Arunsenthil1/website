# Ex.07 Restaurant Website
# Date:12/12/2024
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
main page.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to our Restaurent</title>
   
    
</head>
<style>
   body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color:#948c38;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: rgb(86, 77, 40);
    border-radius: 10px;
}

.menu{
    background-color: black;
    color: rgb(250, 4, 4);
    padding: 25px;
    border-radius: 30px;
}
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 80px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 10px 10px;
}

nav ul li a {
    text-decoration: none;
    color: #fcfafa;
    font-weight: bold;
}

.offer-txt{
    color: black;
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background: url('banner.jpg') no-repeat center center/cover;
    padding: 60px 20px;
    color: #fff;
    border-radius: 10px;
    margin: 25px;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0 0 20px;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: rgb(173, 154, 11);
}

.feature {
    text-align: center;
    background-color: rgba(65, 88, 39, 0.955);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(169, 166, 140, 0.1);
    flex: 1;
    margin: 0 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

p {
    text-align: left;
}

ul {
    text-align: left;
}

.copy{
    margin-left: auto
}

.hyperlink{
    color: blue;
} 
</style>
<body>
    <header>
        <div class="logo">
            
            <h1>LA PALMERA</h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href=file:///C:/Users/Arun/env1/Scripts/.vscode/administrator.html>Home</a></li>
                <li><a href=file:///C:/Users/Arun/env1/Scripts/.vscode/menu.html>Menu</a></li>
                
                <li><a href=file:///C:/Users/Arun/env1/Scripts/.vscode/contact.html>Contact us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner" style="background-image: url('offer.webp');">
            <h2 class="offer-txt" >Tradition,Untouched!!</h2>
              <h2 class="offer-txt"> "Welcome To LA PALMERA Most Awarded Italian Restaurent"</h2>

            <p class = 'offer-txt'>Where Flavor Meets Experience
Dive into a culinary journey like no other, where every dish tells a story and every bite is a celebration,our restaurant blends exquisite flavors, fresh ingredients, and a warm, inviting ambiance. Whether you're craving a cozy dinner, a lively gathering, or a new taste adventure, we promise an unforgettable dining experience..</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Our New Menu</h3>
                <img src="C:\\Users\\Arun\\Documents\\th (2).jpg" alt="Our New Menu">
                <p>Excite your taste buds with our brand-new menu, crafted to bring fresh flavors and unique dishes to your table. From innovative creations to timeless classics reimagined, there’s something for everyone to savor. Explore our seasonal ingredients, bold spices, and mouthwatering combinations. Visit us today and experience the delicious difference.</p>
                <a href="www.google.com">See our new menu</a>
            </div>
            <div class="feature">
                <h3>Reserve your table</h3>
                <img src="C:\\Users\\Arun\\Documents\\th.jpg" alt="Reserve your table">
                <p>Enjoy a seamless dining experience by reserving your table in advance. Whether it’s a romantic dinner, a family gathering, or a casual meal with friends, we’ve got the perfect spot for you. Select your preferred date, time, and party size, and let us take care of the rest. Book now to ensure your seat at our table.</p>
                <a href="www.google.com">Book your table now</a>
            </div>
            <div class="feature">
                <h3>Opening Hours</h3>
                <img src="C:\\Users\\Arun\\Documents\\th (1).jpg" class="hours" alt="Opening Hours">
                <p>We’re here to serve you delicious meals and unforgettable moments every day of the week. Check out our opening hours below and plan your visit. Whether it’s a hearty breakfast, a leisurely lunch, or a delightful dinner, we’re ready to welcome you!.</p>
                <ul>
                    Monday - Friday: 11:00 AM - 10:00 PM <br>
                    Saturday: 10:00 AM - 11:00 PM <br>
                    Sunday: 10:00 AM - 9:00 PM <br>
                </ul>
            </div>
        </section>
        <footer>
            <div class="logo">
                
                <p align="margin-right"> Design And Developed By Arun S  </p>
            </div>
        </footer>
    </main>


   
</body>
</html>

home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
</head>

<style>
    header{
        font-size: 620%;
        font-style:peppy;
        background-color:#ff3700;
    .content{
        font-size: larger;
        font-family: cursive;
    }
</style>
<body bgcolor="#f6dba5">
    <center>
        <header style="color: rgb(22, 22, 18);">
            LA PALMERA
        </header>

        <img src="C:\\Users\\Arun\\Documents\\th (5).jpg" width="1100" height="500">
        
        <div class="content">
        <p>Welcome to The La PALMERA Restaurant: A Wonderful Dining Experience Like No Other
            Here's a mesmerizing description of a restaurant:

            "At La PALMERA, food is more than just a meal – it's an experience. Our chefs combine timeless culinary techniques with contemporary twists, ensuring every dish delights your palate.
             Our story began in [1980] with a simple mission: to create a space where family, friends, and food lovers could come together to share unforgettable moments."

"Our restaurant is named La palmera to reflect our philosophy: fresh, vibrant, and zestful! We take pride in creating dishes with a balance of flavors, freshness, and healthfulness."
                                     "WELCOME TO THE WORLD OF La palmera!!"</p>
        </div>
    </center>

</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
        <div>
    <title>Restaurant Menu</title>
        </div>

    <style>
        /* General body styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url(''); /* Replace with your background image */
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: #ffffff;
        }

        /* Overlay to darken the background image */
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: grey;
            z-index: -1;
        }

        /* Main container */
        .menu-container {
            width: 80%;
            margin: 50px auto;
            background-color: rgb(255, 255, 255);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            color: #333;
        }

        /* Header styles */
        header {
            text-align: center;
            padding: 20px 0;
            color: #ffffff;
            background-color: #7d4017; /* Orange header */
            border-radius: 15px 15px 0 0;
        }

        header h1 {
            margin: 0;
            font-size: 48px;
        }

        /* Section titles */
        h2 {
            text-align: center;
            color: #19753f; /* Green color */
            border-bottom: 2px solid #d35400;
            font-size: 36px;
            margin-bottom: 20px;
        }

        /* Menu items */
        .menu-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            align-items: center;
        }

        .menu-item img {
            width: 150px;
            height: 100px;
            border-radius: 10px;
            object-fit: cover;
        }

        .menu-item-details {
            flex-grow: 1;
            margin-left: 20px;
        }

        .menu-item-name {
            font-size: 24px;
            font-weight: bold;
            color: #34495e;
        }

        .menu-item-price {
            font-size: 22px;
            color: #e74c3c;
        }

        .description {
            font-size: 16px;
            color: #7f8c8d;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            color: #bdc3c7;
        }

        /* Responsive styles */
        @media screen and (max-width: 768px) {
            .menu-container {
                width: 95%;
            }

            .menu-item {
                flex-direction: column;
                align-items: flex-start;
            }

            .menu-item img {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body bgcolor="black">
<div class="overlay"></div>

<header>
    <h1>WELCOME TO OUR RESTAURENT</h1>    
</header>

<div class="menu-container">

    <div class="menu-section">
        <h2>LA PALMERA</h2>
        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\italian sand.jpg" alt="Italian Sandwich"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Italian Sandwich</p>
                <p class="description">Crusty bread, cured meats, cheese, fresh veggies, and olive oil for a flavorful, hearty meal.</p>
            </div>
            <p class="menu-item-price">rs.150</p>
        </div>

        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\pottato focassia.jpg" alt="Potato Foccacia"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Potato Foccacia</p>
                <p class="description">Potato,vegetables, garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">rs.170</p>
        </div>
        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\noodles.jpg"alt="Noodles"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Noodles</p>
                <p class="description">Noodles,vegetables,mushrooms filled with garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">rs.110</p>
        </div>
        

<center>
    
    </center>
    <div class="menu-section">
        <h2>Desserts</h2>
        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\choco lava cake.jpg" alt="Chocolate Lava Cake"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Chocolate Lava Cake</p>
                <p class="description">Warm cake with a molten chocolate center.</p>
            </div>
            <p class="menu-item-price">rs.70</p>
        </div>

        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\tiramisu.jpg" alt="Tiramisu"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Tiramisu</p>
                <p class="description">Best dessert in the world.</p>
            </div>
            <p class="menu-item-price">rs.250</p>
        </div>
    

    <div class="menu-section">
        <h2>Beverages</h2>
        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\beer.jpg" alt="Beer"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Beer</p>
                <p class="description">Fermented beverage made with malted grains.</p>
            </div>
            <p class="menu-item-price">rs.200</p>
        </div>

        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\champaign.avif" alt="Champagne"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Champagne</p>
                <p class="description">Sparkling wine with effervescenes.</p>
            </div>
            <p class="menu-item-price">rs.2500</p>
        </div>
    
    
    <h2>BREWED BLISS</h2>
        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\champaign.avif" alt="Espresso"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Espresso</p>
                <p class="description">Coffe brewed by hot water through finely ground coffee beans.</p>
            </div>
            <p class="menu-item-price">rs.130</p>
        </div>
        <div class="menu-item">
            <img src="C:\\Users\\Arun\\Documents\\cold coffee.jpg" alt="Cold Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Cold Coffee</p>
                <p class="description">Milk,ice cubes,sugar and coffee powder.</p>
            </div>
            <p class="menu-item-price">rs.80</p>
        
       
        

       
    
    </body>
    </html>
    
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
</head>
<style>
    header{
        font-size: 420%;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .address{
        font-size: x-large;
    }
    .contact{
        font-size: larger;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
</style>
<body bgcolor=yellow>
    <center>
        <header style="color: rgb(176, 20, 20);">LA PALMERA RESTAURENT
        </header>
        <img src="C:\\Users\\Arun\\Documents\\th (1).jpg" width="750" height="450">
        
       
        </center>
        <side>
            
        </side>
        <center>
        <td><h3 style="font-size:25px"> CONTACT </h3></td>
    <td><h4 style="font-size:25px">PHONE: +91 9876543210|EMAIL ID:lapalmera@gmail.com</h4></td> 
    <td><h3 style="font-size:25px"> ADDRESS:11, Anna Nagar, Avadi, Chennai </h3></td>
    </center>
    </body>
    </html>
```



# OUTPUT:
![Screenshot 2024-12-12 195110](https://github.com/user-attachments/assets/d0e3aaeb-888d-4ab4-ab33-b07c75f77649)
![Screenshot 2024-12-12 195135](https://github.com/user-attachments/assets/3f510ff0-1ac6-4a2b-a7f3-6f7945c282f7)
![Screenshot 2024-12-12 195149](https://github.com/user-attachments/assets/ef9cf666-641f-4a3d-bb31-569879f6e0f0)
![Screenshot 2024-12-12 195220](https://github.com/user-attachments/assets/5836fcf3-0eda-4c21-8d0a-2ad8f3b647ab)
![Screenshot 2024-12-12 195235](https://github.com/user-attachments/assets/1024bf8d-1335-4a3d-a376-13711e339830)
![Screenshot 2024-12-12 195248](https://github.com/user-attachments/assets/a592baa7-dbbb-4a36-a76b-f036dd4b2e9d)
![Screenshot 2024-12-12 195309](https://github.com/user-attachments/assets/4e613b27-6367-432b-93ee-5b7e72972a60)





# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
