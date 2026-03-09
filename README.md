# Product Card Design with Hover Effect using CSS
## Date:09/03/2026

## AIM:
To design a Product Card for an E-commerce website using HTML and CSS and apply hover effects, transitions, and styling techniques to create an interactive user interface.

## DESIGN STEPS:

### Step 1:
Create a basic HTML structure using ```<!DOCTYPE html>, <html>, <head>, and <body>```.

### Step 2:
Add a container div for the product card.

### Step 3:
Insert the product image using the ```<img>``` tag.

### Step 4:
Add product name, description, and price using ```<h3>``` and ```<p>``` tags.

### Step 5:
Create an Add to Cart button using the ```<button>``` tag.

### Step 6:
Style the product card using CSS by applying:
<ul>
  <li>width</li>
  <li>padding</li>
  <li>border-radius</li>
  <li>box-shadow</li>
</ul>

### Step 7:
Align the card content using text-align and spacing properties.

### Step 8:
Add hover effects using :hover selector.

### Step 9:
Apply transform: translateY() to move the card slightly upward on hover.

### Step 10:
Increase the box-shadow to create a lifting effect.

### Step 11:
Add transform: scale() to slightly zoom the product image on hover.

### Step 12:
Apply transition property to make the hover animation smooth.

### Step 13:
Create a footer section at the bottom of the page.

### Step 14:
Display Learner Name and Register Number inside the footer.

### Step 15:
Style the footer using background color and center alignment.

### Step 10:
Test your webpage in a browser.

## PROGRAM:
```
<head>
    <title>Product Card</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin: 5;
            padding: 20px;
            background-color: #dfcccc;
        }
        .product-card {
            width: 300px;
            background-color: burlywood;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 20px;
            margin-bottom: 20px;
                }
        .product-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }
        .product-name {
            font-size: 24px;
            margin: 15px 0 10px 0;
        }
        .product-description {
            font-size: 16px;
            color: #666;
            margin: 10px 0;
        }
        .product-price {
            font-size: 20px;
            font-weight: bold;
            color: #333;
            margin: 10px 0;
        }
        .add-to-cart {
            background-color: #19c01e;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 5px;
           
        }
        .add-to-cart:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            width: 100%;
            position: fixed;
            bottom: 0;
            left: 0;
        }
    </style>
</head>
<body>
    <div class="product-card">
        <h2 class="product-name">SKYBAGS </h2>
        <img src="https://skybags.co.in/cdn/shop/files/KYRO02SCBPKATANAREDBLACK1_1_1800x1800.png?v=1740657606" alt="Product Image" class="product-image">
        <p class="product-description">The Skybags backpack features a bold,stylish and unique red-and-black graphic design that gives it a modern and trendy look. It comes with spacious compartments that help you neatly organize books, gadgets, and other daily essentials. Made from durable and lightweight materials.</p>
        <p class="product-price">$25</p>
        <button class="add-to-cart">Add to Cart</button>
    </div>
    <footer>
        <p>Learner Name: Ashwin Kumar.M</p>
        <p>Register Number: 212225040033</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![alt text](image.png)
## RESULT:
The Product Card with Hover Effect was successfully designed using HTML and CSS.
