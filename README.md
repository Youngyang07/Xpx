# Xpx
<!DOCTYPE html>
<html>
<head>
    <title>My E-Commerce Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My E-Commerce Store</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Cart</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="product">
            <img src="product-image.jpg" alt="Product">
            <h2>Product Name</h2>
            <p>Description of the product</p>
            <p>$XX.XX</p>
            <button>Add to Cart</button>
        </section>
        
        <!-- Additional product sections here -->
    </main>
    
    <footer>
        <p>&copy; 2021 My E-Commerce Store. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    text-align: center;
}

nav li {
    display: inline;
    margin: 0 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

main {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.product {
    width: 300px;
    margin: 20px;
    padding: 10px;
    border: 1px solid #ccc;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
