# Ex.07 Software Product Company Website
## Date:

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

### soft.html
```
<!DOCTYPE html>
<html>
<head>
<title>SDev Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
          }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
                         }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        p1 {
            color: #fff  ;
            margin-bottom: 20px; 
            font-size: 15px;
          }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
        <h2>About Our Company</h2>
        <p>
            Our SDev company specializes in creating tailored software solutions for diverse clients,<br>
            spanning industries like healthcare, finance, and e-commerce. Utilizing a range of technologies<br>
            and methodologies such as Agile and Scrum, these companies employ multidisciplinary teams of<br>
            software engineers, designers, and project managers to deliver high-quality products. Offering<br>
            services including <strong>custom software development, web and mobile app development, and quality assurance,</strong><br>
            they prioritize customer satisfaction through close collaboration, iterative development cycles, and<br>
            rigorous testing processes. Continuously adapting to emerging technologies and industry trends, software<br>
            development companies strive for innovation, efficiency, and excellence in delivering robust and reliable<br>
            software solutions to meet the evolving needs of their clients.
        </p>
        <div class="image-container">
            <img src="image.jpg" alt="Image 1">
            <img src="image2.jpg" alt="Image 2">
        </div>
    </div>
    <footer>
        <p1>&#169ARJUN N S [212223230020]~SEC</p1>
    </footer>
</body>
</html>
```

### products.html
```
<!DOCTYPE html>
<html>
<head>
    <title>SDev Company - Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
        }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .product {
            display: inline-block;
            width: 45%;
            margin: 10px;
            text-align: center;
        }
        .product img{
           max-width: 100%;
           height: auto;
           border-radius: 50%;
        }
        .product h3 {
            color: #fff;
        }
        .product p {
            color: #007bff;
            font-size: 18px;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Products</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
    
        <h2>Our Products</h2>

        <div class="product">
            <img src="prod1.jpeg" alt="Python Programming" width="200" height="200">
            <h3>1. Accounting Software</h3>
            <p>Price: $9999</p>
        </div>
        
        <div class="product">
            <img src="prod2.jpeg" alt="Python Programming" width="200" height="200">
            <h3>2. Tax Software</h3>
            <p>Price: $4999</p>
        </div>
        
        <div class="product">
            <img src="prod3.jpeg" alt="Python Programming" width="200" height="200">
            <h3>3. Bookkeeping Software</h3>
            <p>Price: $5999</p>
        </div>
        
        <div class="product">
            <img src="prod4.jpeg" alt="Python Programming" width="200" height="200">
            <h3>4. Time Tracking Software</h3>
            <p>Price: $3499</p>
        </div>
        
        <div class="product">
            <img src="prod5.jpeg" alt="Python Programming" width="200" height="200">
            <h3>5. Project Management Software</h3>
            <p>Price: $8999</p>
        </div>
        
        <div class="product">
            <img src="prod6.jpeg" alt="Python Programming" width="200" height="200">
            <h3>6. Customer Relationship Management Software</h3>
            <p>Price: $7999</p>
        </div>
        
        <div class="product">
            <img src="prod7.jpeg" alt="Python Programming" width="200" height="200">
            <h3>7. Communication Software</h3>
            <p>Price: $4499</p>
        </div>
        
        <div class="product">
            <img src="prod8.jpeg" alt="Python Programming" width="200" height="200">
            <h3>8. Website Building Software</h3>
            <p>Price: $6999</p>
        </div>
        
        <div class="product">
            <img src="prod9.jpeg" alt="Python Programming" width="200" height="200">
            <h3>9. Payment Transaction Software</h3>
            <p>Price: $7999</p>
        </div>
        
        <div class="product">
            <img src="prod10.jpeg" alt="Python Programming" width="200" height="200">
            <h3>10. Sales, Marketing, and PR Software</h3>
            <p>Price: $8999</p>
        </div>
        
        <div class="product">
            <img src="prod11.jpeg" alt="Python Programming" width="200" height="200">
            <h3>11. Medical software</h3>
            <p>Price: $9999</p>
        </div>
        
        <div class="product">
            <img src="prod12.png" alt="Python Programming" width="200" height="200">
            <h3>12. ERP Software</h3>
            <p>Price: $10999</p>
        </div>
        

    </div>
    <footer>
        <p1>&#169ARJUN N S [212223230020]~SEC</p1>
    </footer>
</body>
</html>
```

### council.html
```
<!DOCTYPE html>
<html>
<head>
    <title>SDev Company - Council</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
        }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .product {
            display: inline-block;
            width: 45%;
            margin: 10px;
            text-align: center;
        }
        .product img{
           max-width: 100%;
           height: auto;
           border-radius: 50%;
        }
        .product h3 {
            color: #007bff;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Council Members</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
    
        <h2>Our Members</h2>

        <div class="product">
            <img src="p1.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 1</h3>
        </div>
        
        <div class="product">
            <img src="p2.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 2</h3>
        </div>
        
        <div class="product">
            <img src="p3.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 3</h3>
        </div>
        
        <div class="product">
            <img src="p4.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 4</h3>
        </div>
        
        <div class="product">
            <img src="p5.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 5</h3>
        </div>
        
        <div class="product">
            <img src="p6.avif" alt="Python Programming" width="200" height="200">
            <h3>person 6</h3>
        </div>
           

    </div>
    <footer>
        <p1>&#169ASHWINA [212223230025]~SEC</p1>
    </footer>
</body>
</html>
```
## OUTPUT:

![pic1](https://github.com/Ashwinakn/softweb/assets/152128332/fd3ec7ef-b41d-41d3-9fa0-ee4a7592f70f)

![pic2](https://github.com/Ashwinakn/softweb/assets/152128332/c0cd3d53-f71e-4b48-ba16-52d5184bb329)

![pic3](https://github.com/Ashwinakn/softweb/assets/152128332/a8fe30a9-3be7-4c47-94f1-f84fb1848ec3)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
