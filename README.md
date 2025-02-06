# Fashion-Hub
Shopping website
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Store</title>
    <link rel="stylesheet" href="web.css">
</head>
<body>
    <header>
        <h1>Fashion Hub</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <h2>Latest Fashion Trends</h2>
        <p>Discover the best outfits for your style</p>
        <a href="#products" class="btn">Shop Now</a>
    </section>
    
    <section id="products" class="product-list">
        <h2>Our Collection</h2>
        <div class="products">
            <div class="product">
                <img src="https://stimg.b-cdn.net/images/450/data/2024y/July/51311/Sky%20Blue-Magic%20Slub-Festival%20Wear-Foil%20Print-Readymade%20Kurti-KEERTHI-1001.jpg" alt="Dress 1">
                <h3>Casual Dress</h3>
                <p>$49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://stimg.b-cdn.net/images/450/data/2024y/April/49121/Maroon-Jimmi-Choo-Wedding-Wear-Embroidery-Work-Saree-VT5069-9%20(2).jpg" alt="Dress 2">
                <h3>Party Wear</h3>
                <p>$39.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://assets.ajio.com/medias/sys_master/root/20230613/5Fdu/6487c49742f9e729d73d3af5/-473Wx593H-466028561-yellow-MODEL.jpg" alt="Dress 3">
                <h3>Wedding Wear</h3>
                <p>$100.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://4.imimg.com/data4/WW/TE/MY-26831742/476_blue_1-500x500.jpg" alt="Dress 4">
                <h3>Formal Wear</h3>
                <p>$99.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://ramrajcotton.in/cdn/shop/products/06_cbea4649-adea-4cba-abc1-711ff60728d1.jpg" alt="Dress 5">
                <h3>Wedding Wear</h3>
                <p>$100.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://m.media-amazon.com/images/I/618J490bCRL._AC_UY1100_.jpg" alt="Dress 6">
                <h3>Casual Dress</h3>
                <p>$49.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>
    <section id ="contact" class="Contact-Us">
        <h4>124,Chitra Complrex,Center Bus Stand,Trichy</h4>
        <h4>123456789</h4>
        <a href="#contact"></a>
    </section>
    
    <footer>
        <p>&copy; 2026 Fashion Hub. All rights reserved.</p>
    </footer>
</body>
</html>
CSS
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color:bisque;
    color: #333;
}

/* Header */
header {
    background-color: #ff4081;
    color:white;
    padding: 15px 0;
    text-align: center;
}
nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 50px;
    background: url('hero-bg.jpg') no-repeat center center/cover;
    color: white;
}

.hero h2 {
    font-size: 2.5rem;
}

.hero p {
    font-size: 1.2rem;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: white;
    color: #ff4081;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    margin-top: 10px;
}

/* Products Section */
.product-list {
    text-align: center;
    padding: 50px 20px;
}

.products {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.product {
    background: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 250px;
    text-align: center;
}

.product img {
    width: 100%;
    border-radius: 5px;
}

.product h3 {
    margin: 10px 0;
}

.product p {
    font-size: 1.2rem;
    color: #ff4081;
}

.product button {
    background-color: #ff4081;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
    border-radius: 5px;
}

.product button:hover {
    background-color: #e60073;
}
/* Contact*/
.Contact-Us{
    text-align: center;
    color:white;
}
/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 15px 0;
    margin-top: 30px;
}

