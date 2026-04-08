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

<h1>🛍️ REAL HIGH</h1>

<img src="background.jpg" 
     alt="Sample Image" width="1280" height="640" style="border-radius: 10px;">

<!-- Products -->
<div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>T-Shirt</h3>
    <p>₱500</p>
    <button onclick="buyItem('T-Shirt')">Buy Now</button>
</div>

<div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>Long sleeve</h3>
    <p>₱500</p>
    <button onclick="buyItem('Long sleeve')">Buy Now</button>
</div>

<div class="product">
    <img src="https://via.placeholder.com/200">
    <h3>Sando</h3>
    <p>₱500</p>
    <button onclick="buyItem('Sando')">Buy Now</button>
</div>

<script>
function buyItem(product) {
    alert("You selected: " + product);
}
</script>

</body>
</html>
