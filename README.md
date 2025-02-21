# My-website-2<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Online Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>My Online Store</h1>
        <p>Buy the best products at affordable prices!</p>
    </header>

    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 1">
            <h2>Product 1</h2>
            <p>Price: ₹500</p>
            <button onclick="addToCart('Product 1', 500)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 2">
            <h2>Product 2</h2>
            <p>Price: ₹700</p>
            <button onclick="addToCart('Product 2', 700)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 3">
            <h2>Product 3</h2>
            <p>Price: ₹1000</p>
            <button onclick="addToCart('Product 3', 1000)">Add to Cart</button>
        </div>
    </section>

    <section class="cart">
        <h2>Shopping Cart</h2>
        <ul id="cart-items"></ul>
        <p>Total: ₹<span id="total-price">0</span></p>
        <button onclick="checkout()">Checkout</button>
    </section>

    <script src="script.js"></script>
</body>
</html>
