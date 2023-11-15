# Ex.07 Software Product Company Website
## Date: 14.11.2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### site1.html

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <Title> Twilio </Title>
    <link rel="stylesheet" href="style.css">
    <style>
      p{
        margin-top: 0px;
        padding-top: 7px;
      }

      h1{
        margin-top: 30px;
        padding-top: 30px;
      }
      body{
        margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      /* Set background image with linear gradient */
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.7)),
                  url(twilio\ 2nd.png) center/cover no-repeat;
    background-size: cover;             /* Replace 'your-image-url.jpg' with your actual image URL */
      height: 100vh; /* Ensure full viewport height */
      color: white; /* Set text color to contrast with the background */
      display: flex;
      align-items: center;
      justify-content: center;
      }
      button{
        margin-top: 250px;
        margin-left: 100px;
      }
      .logo {
        position: absolute;
      top: 10px; /* Adjust the value as needed */
      left: 10px; 
      }


    </style>
  </head>
  <body>
    <header>
          <img src="twilio.png" class="logo" alt="logo" >
    </header>
      <div class="banner-text">
      <center>
        <h1>Twilio’s mission is to unlock the imagination of builder </h1>
        
        <p>We’re a software company that strengthens businesses by unifying their data to build insightful paths to customers, <br>so they’re smarter with every interaction and able to outmaneuver their competition.</p>

        
      </center>
        <div class="navbar">
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./developers.html">Developers</a></li>
            <li><a href="./contactus.html">Contact Us</a></li>
          </ul>
        </div>
        <a href="products.html"></a>
        <div class="content">
          <h1>  </h1>
          <p>
              
          </p>
          <div>
              <button type="button"> CLICK HERE TO APPLY</button>

          </div>
      </div>
    
  </body>
</html>
```

### products.html
```
<html>
    <head>
        <title>Products</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="navbar">
            <ul>
              <li><a href="site1.html">Home</a></li>
              <li><a href="#">Products</a></li>
              <li><a href="./developers.html">Developers</a></li>
              <li><a href="./contactus.html">Contact Us</a></li>
            </ul>
          </div>
        <section>
            <img src="twilio.png" alt="Product 1">
        </section>
        <div class="product">
            
                <h2>Product Name</h2>
                <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                <h4>Twilio Products<br>Everything you need to build, deliver, and iterate new customer experiences</h4> 
                <p>Price: $19.99</p>
                <button>Add to Cart</button>
            </div>
        </section>
       
     
</body>
</html>


```


### developers.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DEVELOPER</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="twilio.png" class="logo" alt="logo" >
  </header>
    <div class="navbar">
        <ul>
          <li><a href="./site1.html">Home</a></li>
          <li><a href="./products.html">Products</a></li>
          <li><a href="#">Developers</a></li>
          <li><a href="./contactus.html">Contact Us</a></li>
        </ul>
      </div>
    <header>
        <h1>CHIEF DEVELOPER</h1>
    </header>

    <section>
        <img src="sfds.jpeg" alt="Product 1">
    </section>

    <footer>
        <p>&copy; 2023 Product Website</p>
    </footer>

</body>
</html>
```

### contactus.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTACT US</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="twilio.png" class="logo" alt="logo" >
  </header>
    <div class="navbar">
        <ul>
          <li><a href="./site1.html">Home</a></li>
          <li><a href="./products.html">Products</a></li>
          <li><a href="./developers.html">Developers</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </div>
    <header>
        <h1>MAIL : lavamdn04@gmail.com</h1>
    </header>

    <footer>
        <p>&copy; 2023 Product Website</p>
    </footer>

</body>
</html>

```


## OUTPUT:

### HOME PAGE:
![WhatsApp Image 2023-11-15 at 20 07 46_e89eba54](https://github.com/LavanyaMuraleedharan/softweb/assets/120103862/f9dbfebe-59f4-4b22-b991-11f3cbd99bf2)


### PRODUCT PAGE :
![WhatsApp Image 2023-11-15 at 20 09 06_19768211](https://github.com/LavanyaMuraleedharan/softweb/assets/120103862/82c8a481-8a6e-46ca-9028-055c9f8a051e)

### DEVELOPER PAGE :
![WhatsApp Image 2023-11-15 at 20 08 35_d830f7c6](https://github.com/LavanyaMuraleedharan/softweb/assets/120103862/b765a7c3-2788-4385-9a14-04c9e842b38a)

### CONTACT PAGE
![WhatsApp Image 2023-11-15 at 20 08 05_52b903e2](https://github.com/LavanyaMuraleedharan/softweb/assets/120103862/07c6af9b-57a9-4ac0-84a7-165c2bf7199a)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
