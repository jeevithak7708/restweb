# Ex.07 Restaurant Website
## Date:07.10.2025

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
home.html
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="restname">
            <h1><b>WOW CRAB</b></h1>
        </div >
        
        <div class="lines">
            <i>"Proudly serving flavor that everyone loves-this is CRAB"</i>
            
        </div>
        <div class="image1">
            <img src="ambiance1.jpg" width="400" height="400">
        </div>
        <footer class="copyrights">
            &copy; JEEVITHA K(25016606)
        </footer>
        </div>
    </body>
</html>

style1.css

.background {
    width: 1470px;
    height: 680px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background\ img1.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.restname {
    color: greenyellow;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 300%;
    top: -50px;
}


.lines {
    color: white;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 130%;
    top: -100px;
}

.image1 {
    position: relative;
    top: -90px;
    left: 500px;
    right: 250px;
    background-size:contain;
}



.copyrights{
    width: 1510px;
    height: 20px;
    background-color: pink;
    text-align: center;
    top: -50px;
    left: -20px;
    position: relative;
}

menu.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="menu">
            <h1><b>MENU</b></h1>
        </div >
        <div class="menugrid">
            <div class="menuitem">
                <img src="food1.jpg" width="300" height="150">
                <h1>Crab curry</h1>
                <p>Rs. 500</p>
            </div>
            <div class="menuitem">
                <img src="food2.jpg" width="300" height="150">
                <h1>Crab salad</h1>
                <p>Rs. 350</p>
            </div>
            <div class="menuitem">
                <img src="food3.jpg" width="300" height="150">
                <h1>Hoboken gril</h1>
                <p>Rs. 640</p>
            </div>
            <div class="menuitem">
                <img src="food4.jpg" width="300" height="150">
                <h1>Crab masala</h1>
                <p>Rs. 430</p>
            </div>
            <div class="menuitem">
                <img src="food5.jpg" width="300" height="150">
                <h1>Crab cake</h1>
                <p>Rs. 320</p>
            </div>
            <div class="menuitem">
                <img src="food6.jpg" width="300" height="150">
                <h1>Crab crispy fry</h1>
                <p>Rs. 350</p>
            </div>
            <div class="menuitem">
                <img src="food7.jpg" width="300" height="150">
                <h1>Crab thandoori</h1>
                <p>Rs. 410</p>
            </div>
            <div class="menuitem">
                <img src="food8.jpeg" width="300" height="150">
                <h1>Sri lankar crab curry</h1>
                <p>Rs. 200</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; JEEVITHA K(25016606)
        </footer>
        </div>
    </body>
</html>

style2.css

.background {
    width: 1470px;
    height: 680px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background2.jpg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.menu {
    color: greenyellow;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
    border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: pink;
    text-align: center;
    top: 80px;
    left: -20px;
    position: relative;
}

admin.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="admin">
            <h1><b>ADMINISTRATION TEAM</b></h1>
        </div>
        <div class="admingrid">
            <div class="adminlist">
                <img src="jeevitha k.jpg" width="130" height="250">
                <h1>JEEVITHA K</h1>
                <p class="post">CEO</p>
            </div>
            <div class="adminlist">
                <img src="vijay.jpg" width="130" height="250">
                <h1>VIJAY</h1>
                <p class="post">Marketing Manager</p>
            </div>
            <div class="adminlist">
                <img src="sk.jpg" width="130" height="250">
                <h1>SIVA KARTHIKEYAN</h1>
                <p class="post">Operations Manager</p>
            </div>
            <div class="adminlist">
                <img src="bala.jpg" width="130" height="250">
                <h1>BALA</h1>
                <p class="post">HR Manager</p>
            </div>
            <div class="adminlist">
                <img src="Dhanush-.jpg" width="130" height="250">
                <h1>DHANUSH</h1>
                <p class="post">Executive Chef</p>
            </div>
            <div class="adminlist">
                <img src="surya.jpg" width="130" height="250">
                <h1>SURYA</h1>
                <p class="post">Customer Service Manager</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; JEEVITHA K(25016606)
        </footer>
        </div>
    </body>
</html>

style3.css

.background {
    width: 1470px;
    height: 680px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background2.jpg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.admin {
    color: greenyellow;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminlist{
    background-color: white;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminlist img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminlist h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.adminlist p {
    color: black;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: pink;
    text-align: center;
    top: -0px;
    left: -20px;
    position: relative;
}

contact.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="contact">
            <h1><b>CONTACT</b></h1>
        </div>
        <div class="info">
            <h1>Visit us at:</h1>
            <p>MEERA<br>96, ABC street<br>newcity-123456<br>India</p>
            <br>
            <h1>Phone:</h1>
            <p>+91 7654328919</p>
            <br>
            <h1>Email ID:</h1>
            <p>meera125@gmail.com</p>
        </div>
        <footer class="copyrights">
            &copy; JEEVITHA K(25016606)
        </footer>
        </div>
    </body>
</html>

style4.css

.background {
    width: 1470px;
    height: 680px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background2.jpg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.contact {
    color: greenyellow;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.info {
    color: white;
    font-family: Times New Roman;
    position: relative;
    top: -70px;
    left: 700;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: pink;
    text-align: center;
    top: -30px;
    left: -20px;
    position: relative;
}


```

## OUTPUT:
![alt text](jeevitha/foodapp/static/rest1.png)
![alt text](jeevitha/foodapp/static/rest2.png)
![alt text](jeevitha/foodapp/static/rest3.png)
![alt text](jeevitha/foodapp/static/rest4.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
