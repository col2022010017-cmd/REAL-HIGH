<!DOCTYPE html>
<html>
<head>
    <title>REAL HIGH</title>
    <style>
        body {
            font-family: Arial;
            background-color: #F5F5F5;
            text-align: center;
        }

        h1 {
            background-color: #333;
            color: white;
            padding: 15px;
        }

        .product {
            background: white;
            margin: 20px;
            padding: 15px;
            border-radius: 10px;
            display: inline-block;
            width: 200px;
        }

        .product img {
            width: 100%;
            border-radius: 10px;
        }

        img.main-image {
            width: 500px;
            border-radius: 10px;
        }

        button {
            background-color: green;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: darkgreen;
        }
    </style>
</head>
<body>

<h1>🛍️ Andrian Online Shop</h1>

<!-- Title at Image -->
<h2>Title ng Image</h2>
<img class="main-image" src="468780963_874775498105157_2166684103895548029_n.jpg" 
     alt="Sample Image">

<!-- Products -->
<div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>T-Shirt</h3>
    <p>₱500</p>
    <button onclick="buyItem('T-Shirt')">Buy Now</button>
</div>

<div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>Loong sleeve</h3>
    <p>₱500</p>
    <button onclick="buyItem('Shoes')">Buy Now</button>
</div>

<div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>sando</h3>
    <p>₱500</p>
    <button onclick="buyItem('Bag')">Buy Now</button>
</div>

<script>
function buyItem(product) {
    alert("You selected: " + product);
}
</script>

</body>
</html>
