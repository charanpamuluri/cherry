<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple E-commerce</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Cart</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="product-list">
            <div class="product-item">
                <img src="https://via.placeholder.com/200" alt="Product 1">
                <h3>Product 1</h3>
                <p>$20.00</p>
                <button class="add-to-cart" data-product="Product 1" data-price="20.00">Add to Cart</button>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/200" alt="Product 2">
                <h3>Product 2</h3>
                <p>$25.00</p>
                <button class="add-to-cart" data-product="Product 2" data-price="25.00">Add to Cart</button>
            </div>
            <!-- More products -->
        </section>

        <section id="cart">
            <h2>Your Cart</h2>
            <ul id="cart-list"></ul>
            <p>Total: $<span id="total-price">0.00</span></p>
            <button id="checkout-btn">Proceed to Checkout</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Simple E-commerce</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>
