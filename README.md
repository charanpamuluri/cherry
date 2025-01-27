body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    padding: 10px;
}

nav ul {
    display: flex;
    justify-content: space-around;
    list-style: none;
    padding: 0;
    margin: 0;
}

nav a {
    color: white;
    text-decoration: none;
}

.product-list {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.product-item {
    text-align: center;
    border: 1px solid #ccc;
    padding: 10px;
    width: 200px;
}

.product-item img {
    width: 100%;
}

button {
    padding: 10px;
    background-color: #28a745;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #218838;
}

#cart {
    padding: 20px;
    background-color: #f4f4f4;
}

#cart-list {
    list-style: none;
    padding: 0;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
