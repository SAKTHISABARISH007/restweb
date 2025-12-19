# Ex.06 Restaurant Website
## Date:19-12-2025

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
hotel.html

<html>
    <head>
        <title>Crescent Cafe</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body class="cafe">
        <nav class="id1">
        <a href="hotel.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="content">
        <h1 class="head">Crescent Cafe</h1>
        <font class="quote">"Good Friends and great coffee make the perfect blend "</font><br><br>
        <font class="info">A classy Western Style Cafe.</font>
        <div class="images">
            <img src="cafe interior.jpeg">
            <img src="coffee.jpeg">
        </div>
    
        <footer class="footer">
         Designed by SAKTHI SABARISH P [25010759] &copy;
        </footer></div>
</body>
</html>
    </body>
</html>

menu.html

<html>
    <head>
        <title>Menu - Crescent cafe</title>
        <link href="menustyles.css" rel="stylesheet">
    </head>
    <body class="cafe">
        <nav class="id1">
        <a href="hotel.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="box"><br><br>
        <font class="head">MENU</font>
        <div class="row">
            <div class="food">
                <img src="coffee1.jpeg">
                <div class="detail"><br>coffee latte<br><font class="high">$ 9.14</font></div>
            </div>
            <div class="food">
                <img src="croissants.jpeg">
                <div class="detail"><br>French Croissants<br><font class="high">$ 8.50</font></div>
            </div>
            <div class="food">
                <img src="brownie.jpeg">
                <div class="detail"><br>Sizzling Brownie With Ice cream<br><font class="high">$ 14.40</font></div>
            </div>
            <div class="food">
                <img src="blackcoffee.jpeg">
                <div class="detail"><br>Black Coffee<br><font class="high">$ 9.99</font></div>
            </div>
            <div class="food">
                <img src="sandwhich.jpeg">
                <div class="detail"><br>Paneer sandwhich<br><font class="high">$ 20</font></div>
            </div>
            <div class="food">
                <img src="salad.jpeg">
                <div class="detail"><br>Vegetable Salad<br><font class="high">$ 17.8</font></div>
            </div>
        </div>

    </div>
        <footer class="footer">
        Designed by SAKTHI SABARISH P [25010759] &copy;
    </footer>
    </body>
</html>

admin.html

<html>
    <head>
        <title>Admin - Crescent Cafe</title>
        <link href="adminstyles.css" rel="stylesheet">
    </head>
    <body class="cafe">
        <nav class="id1">
        <a href="hotel.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="box"><br><br>
        <font class="head">Admin Team</font>
        <div class="row">
            <div class="admin">
                <img src="mee.jpeg">
                <div class="detail"><br>SASH<br><font class="high">[CEO]</font></div>
            </div>
            <div class="admin">
                <img src="Marketing Manager.jpeg">
                <div class="detail"><br>Brad pitt<br><font class="high">[Marketing Manager]</font></div>
            </div>
            <div class="admin">
                <img src="operations manager.jpeg">
                <div class="detail"><br>Chadwick Boseman<br><font class="high">[Operations Manager]</font></div>
            </div>
            <div class="admin">
                <img src="Executive chef.jpeg">
                <div class="detail"><br>Sanji<br><font class="high">[Executive Chef]</font></div>
            </div>
            <div class="admin">
                <img src="Assistent chef.jpeg">
                <div class="detail"><br>Serena<br><font class="high">[Asst. Chef]</font></div>
            </div>
            <div class="admin">
                <img src="Waiter.jpeg">
                <div class="detail"><br>Lily<br><font class="high">[Waiter]</font></div>
            </div>
        </div>

    </div>
        <footer class="footer">
       Designed by SAKTHI SABARISH P [25010759] &copy;
    </footer>
    </body>
</html>

contact.html

<html>
    <head>
        <title>Contact - Crescent Cafe</title>
        <link href="contactstyles.css" rel="stylesheet">
    </head>
    <body class="cafe">
        <nav class="id1">
        <a href="hotel.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="content">
        <h1 class="head">Contact Us</h1>
        <div class="info">
            <h2>Visit us at:</h2>
            <div>742 Evergreen Terrace</div>
            <div>Apartment 5B,</div>
            <div>Brooklyn, NY 11215</div>
             <div>USA</div>
            <h2>Phone:</h2>
            <div>(212) 555‑7890 
</div>

            <h2>Email:</h2>
            <div>Crescent.NYC@gmail.com</div>
        </div>
        <footer class="footer">
         Designed by SAKTHI SABARISH P [25010759] &copy;
        </footer>
    </div>
    </body>
</html>

styles.css

.cafe
{
    background-image: url('cafe.jpeg');
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,black,silver,black);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}

.head 
{
    color: white;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.quote 
{
    font-style: italic;
    font-size: 25px;
    color:whitesmoke ;
}
.info
{
    font-style: italic;
    font-size: 20px;
    color: whitesmoke;
    padding-left: 500px;
}


.images 
{
    display: flex;
    justify-content: space-evenly;
    margin-top: 60px;
    padding-left: 30px;
    padding-right: 30px;
}

img 
{
    width: 400px;
    height:300px;
    border-radius: 10px;
    border: 2px solid;
}
.content{
    text-align: center;
    padding:10px;
    margin:auto;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: black;
    border-top: 2px solid black;
    color:beige;
}

menustyles.css

.cafe
{
    background-image: url('cafe.jpeg');
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,black,silver,black);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: whitesmoke;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: black;
    border-top: 2px solid black;
    color: aliceblue;
}
.row {
    display: flex;             
    justify-content: space-evenly;                
    gap: 20px;                 
    margin-top: 40px;
}

.food {
    text-align: center;
    background-color: rgb(255, 255, 255);
    padding: 10px;
    border-radius: 10px;
    border: 2px solid black;
    width: 200px;          
}
img {
    width: 180px;
    height: 250px;
    border-radius: 10px;
    border: 2px solid silver;
}
.detail{
    font-size: 16px;
    color: black;
    font-weight: bold;
    padding: 10px;
}
.high{
    color: black;
}

adminstyles.css

.cafe
{
    background-image: url('cafe.jpeg');
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,black,silver,black);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: whitesmoke;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: black;
    border-top: 2px solid black;
    color: antiquewhite;
}
.row {
    display: flex;             
    justify-content: space-evenly;                
    gap: 20px;                 
    margin-top: 40px;
}

.admin {
    text-align: center;
    background-color: rgb(255, 255, 255);
    padding: 10px;
    border-radius: 10px;
    border: 2px solid black;
    width: 200px;          
}
img {
    width: 180px;
    height: 250px;
    border-radius: 10px;
    border: 2px solid silver;
}
.detail{
    font-size: 16px;
    color: rgb(0, 0, 0);
    font-weight: bold;
    padding: 10px;
}
.high{
    color: black;
}

contact.css

.cafe
{
    background-image: url('cafe.jpeg');
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,black,silver,black);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: whitesmoke;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.content{

    padding:10px;
    margin:auto;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: black;
    border-top: 2px solid black;
    color: antiquewhite;
}
.info 
{
    font-size: 18px;
    font-weight: bold;
    color: aquamarine;
}

```


## OUTPUT:
![alt text](<Screenshot (72).png>)
![alt text](<Screenshot (73).png>)
![alt text](<Screenshot (74).png>)
![alt text](<Screenshot (75).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
