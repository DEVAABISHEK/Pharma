# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(25, 190, 236, 0.75),rgba(229, 17, 17, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-product {
                border: 1px;
                padding: 10px;
                color: gray;
                background-color:#08f03e;
                border-radius: 30px;
            }
            .logo {
                color:#320be1;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: gray;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(4, 250, 41, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(102, 103, 102);
            } 
            ::placeholder {
                color: gray;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: gray;
                border-radius: 10px;
                background:#6e4ad2;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(11, 6, 117);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(11, 6, 117);
                background-color:#07f039;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: rgb(11, 1, 1);
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 10px;
                background: transparent;
                border: 1px solid rgb(30, 7, 243);
                padding: 30px 20px;
            }
            .container .box-container .box img {
                height: 200px;
                border-radius: 10px;
            }
            .container .box-container .box h3 {
                color:#030303;
                font-size: large;
                padding: 50px 10;
            }
            .container .box-container .box p {
                color: gray;
                font-size: small;
                line-height: 1.5;
            }
            footer {
                background-color:#06b7e3;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">INTRO TECH</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/homepage.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/products.html" class="bg-product"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact us</a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
              
                
                <div class="box">
                    <h3 align="center">CYNCLY</h3>
                    <image src="cyncly.png" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center"> FORWORX </h3>
                    <image src="forworx.png" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">HASHICORP</h3>
                    <image src="hashicrop.png" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">HUBSPOT</h3>
                    <image src="hubspot.png" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">SCHEMATIO</h3>
                    <image src="schematio.png" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">SLACK</h3>
                    <image src="slack.png" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">HOVEROVER</h3>
                    <image src="hoverover.png" width="150" height="500"></image>
                </div>
                <div class="box">
                    <h3 align="center">DEVCOVE</h3>
                    <image src="devcove.png" width="150" height="500"></image>
                </div>

            </div>
              
            </div>
        </div>
    </div>
    <footer>
        <center>Designed and Developed by Samakash.R.S(212223230182) &copy; 2024</center>
    </footer>
</body>
</html>
```
## OUTPUT:
![product-1](https://github.com/DEVAABISHEK/Pharma/assets/150319305/b790892f-9cd8-459c-b470-bcc5302f77dd)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
