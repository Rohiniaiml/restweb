# Ex.07 Restaurant Website
## Date:15.12.2024

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
restuarant.html

<!DOCTYPE html>
<html lang="en"?>
    <head>
        <title>RRR</title>
        <link rel="icon" href="logo.png">
    </head>
    <style>
        body{
            background-image: url("resbc.png");
            background-size: cover;
            background-position: center;
        }
        .nav-list{
            position: absolute;
            top: 30px;
            left: 80%;
            transform:  translatex(10%);
        }
        .nav-list a{
            display: inline blocks;
            margin: 0 10px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: rgb(210, 29, 29);
        }
        .nav-list a:hover{
            color: rgb(235, 9, 149);
        }
    </style>
        <div class="nav-list">
        
        <a href="res.html">Home</a>
        <a href="menu.html">menu</a>
        <a href="contact.html">contact</a>
        <a href="administration.html">Administration</a>

        </div>
    <body style="color: rgb(24, 70, 185);">
        <center>
        <img src="logo.png" style="height: 150px;">
        </center>
        <center>
            <h1 style="color:rgb(165, 17, 17); font-size: 50px;">RRR restuarant</h1>
    <table> 
        <center>
        <tr>
            <td><img src="biriyani.png"" style="width: 300px; height: 250px;"></td>
            <td><img src="poori.png" style="width:300px; height: 250px;"></td>
            <td><img src="meals.png" style="width:300px; height: 250px;"></td>
            <td><img src="noddle.png" style="width:300px; height: 250px;"></td>
            <td><img src="parotta.png" style="width:300px; height: 250px;"></td>
        </tr>
        </center>
        <tr>
            <td><h3 style="color:rgb(25, 9, 81);"><center>BIRIYANI</center></h3></td>
            <td><h3 style="color:rgb(180, 107, 107);"><center>poori</center></h3></td>
            <td><h3 style="color:rgb(11, 221, 221);"><center>meals</center></h3></td>
            <td><h3 style="color:rgb(224, 126, 182);"><center>NODDLE</center></h3></td>
            <td><h3 style="color:rgb(28, 5, 76);"><center> PAROTTA</center></h3></td>
        </tr>
    </table>
    <h2>OUR specialities:
        <h2><center>ARE:</center></h2>
    </h2>
        <p 
        style="font-family: 'Times New Roman',Times, serif";><center>Welcome to our RRR restaurant, where every meal is a celebration of fresh, high-quality ingredients and expertly grilled flavors. From sizzling steaks and juicy burgers to flavorful vegetarian dishes, our menu offers something for everyone. We take pride in providing a customizable dining experience, allowing you to create your perfect meal. Whether you're enjoying a casual lunch, a family gathering, or a special celebration, our cozy and inviting atmosphere makes every occasion memorable. With weekly specials, friendly service, and a commitment to quality, we promise an unforgettable dining experience. Come visit us and taste the difference today!

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>THE BEST PLACE TO EXPERIENCE THE REAL TASTE!</center></h4></td>
        </tr>
        <footer align="center" id="copywrite">
            Designed and developed by ROHINI &copy 2024
        </footer>
    </body>        
</html>

contact.html

<html>
    <head>
        <title> CONTACT </title>
    </head>
    <style>
        
        body{
        
            background-image: url("restuarant.web.jpg");
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            color: rgb(2, 12, 18);
            position:absolute;
            top: 200px;
        }
    </style>
    <div class="nav-list">
        
        <a href="restuarant.html">restuarant</a>
        <a href="menu.html">menu</a>
        <a href="contact.html">contact</a>
        <a href="admin.html">Admin</a>

        </div>
    <center>
        <section id="contact">  
            <h1 style="color:rgb(1, 13, 20)">contact<h1>
            <h4  style="color:rgb(11, 7, 1)">+91 9876546321 <br> |RRRrestuarent@gmail.com</h4>
            <P  style="color:rgb(3, 10, 19)">Address: no.1 ,bagalur road ,hosur <br>
                <br> contact us to place the order<br>
            <hr> COME AND ENJOY THE FOOD
            </P>
            <footer align="center" id="copywrite">
                Designed and developed by ROHINI &copy 2024
            </footer>
         </section> 
    </center>
    </body>
</html> 

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RRR - Administration</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #0d1b88;
            background-color: #850d0d;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #196d66;
            color: rgb(62, 138, 159);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(8, 218, 99, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: rgb(33, 121, 176);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #2a688b;
        }

        .admin-container {
            padding: 40px 20px;
            background: #743793;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: #3a0407;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: rgb(180, 185, 153);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(159, 154, 149, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #978b5a;
            color: rgb(123, 154, 169);
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>    

<header>
        <h1> RRR</h1>
        <nav>
            <a href="restuarant.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Admin</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>OUR BACKBONES</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="VIJAY2.png" alt="CEO">
                <div class="admin-details">
                    <h3>vijay</h3>
                    <p>CEO of RRR</p>
                </div>
            </div>

            <div class="admin-item">
                <img src=".png" alt="Manager">
                <div class="admin-details">
                    <h3>dhruv vikram</h3>
                    <p>Manager of RRR</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="SAIPALLAVI.png" alt="Master Chef">
                <div class="admin-details">
                    <h3>saipallavi</h3>
                    <p>Master Chef of RRR</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="sk.png" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>siva</h3>
                    <p>Assistant Managing Director of RRR</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 RRR. All rights reserved. | <a href="restuarant.html">Back to Home</a></p>
    </footer>

</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - RRR</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f693ea; margin: 0; color: #333; }
    .header, .footer { background: #cd74ae; color: #042d3b; text-align: center; padding: 1rem; }
    .header nav ul { list-style: none; display: flex; justify-content: center; padding: 0; }
    .header nav ul li { margin: 0 1rem; }
    .header nav ul li a { color: #1c57d6; text-decoration: none; font-size: 1.1rem; }
    .menu { padding: 2rem; text-align: center; }
    .menu ul { list-style: none; padding: 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; }
    .menu ul li { background: #3685df; border: 1px solid #ddd; padding: 1rem; border-radius: 5px; }
    .menu ul li:hover { transform: scale(1.05); transition: transform 0.3s; }
  </style>
</head>
<body>
  <header class="header">
    <h1>OUR MENU</h1>
    <nav>
      <ul>
        <li><a href="restuarant.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admini.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Our Menu</h2>
    <ul>
        <li>
            <img src="biriyani.png" alt="Biriyani" width="100" height="100">
            Biriyani - $190
        </li>
        <li>
            <img src="idli.png" alt="idli" width="100" height="100">
            Idly - $80
        </li>
        <li>
            <img src="dosa.png" alt="dosa" width="100" height="100">
            Masal Dosai - $15
        </li>
        <li>
            <img src="kulipanyyaram.png" alt="panniyaram" width="100" height="100">
            Kuzhi Panniyaram - $60
        </li>
        <li>
            <img src="icecream.png" alt="ice" width="100" height="100">
            Icecream - $40
        </li>
        <li>
            <img src="coffee.png" alt="coffee" width="100" height="100">
            Coffee - $50
        </li>
        <li>
            <img src="noddle.png" alt="Noodles" width="100" height="100">
            Hot Noodles- $90
        </li>
        <li>
            <img src="poori.png" alt="poori" width="100" height="100">
            Puff Poori - $90
        </li>
        <li>
            <img src="icecream cone.png" alt="icecream" width="100" height="100">
            Icecream Cone - $60
        </li>
        <li>
            <img src="f7.jpg" alt="ice" width="100" height="100">
            cream cake - $150
        </li>
        <li>
            <img src="cc.png" alt="pizza" width="100" height="100">
            Pizza- $250
        </li>
        <li>
            <img src="meals.png" alt="meals" width="100" height="100">
            Meals - $90
        </li>
        
    </ul>
</section>
     
      </body>
      </html>


```



## OUTPUT:
![alt text](<Screenshot 2024-12-15 224240.png>)
![alt text](<Screenshot 2024-12-15 224252.png>)
![alt text](<Screenshot 2024-12-15 224328.png>)
![alt text](<Screenshot 2024-12-15 224348.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
