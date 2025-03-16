<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Shop | E-Ticaret</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        /* Header */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px;
            background: #fff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .header h1 {
            font-size: 24px;
            color: #333;
        }
        .search-bar {
            display: flex;
            gap: 10px;
        }
        .search-bar input {
            padding: 8px;
            width: 250px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .search-bar button {
            padding: 8px 12px;
            border: none;
            background: #007bff;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
        .icons {
            display: flex;
            gap: 10px;
        }
        .icons button {
            background: none;
            border: none;
            font-size: 18px;
            cursor: pointer;
        }
        /* Ürün Listesi */
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .product-card {
            background: white;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .product-card img {
            width: 100%;
            max-width: 150px;
            border-radius: 8px;
            margin-bottom: 10px;
        }
        .product-card h2 {
            font-size: 18px;
            margin-bottom: 5px;
        }
        .product-card p {
            color: #555;
            margin-bottom: 10px;
        }
        .product-card button {
            padding: 8px 12px;
            border: none;
            background: #28a745;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        <h1>E-Shop</h1>
        <div class="search-bar">
            <input type="text" placeholder="Ürün ara...">
            <button>Ara</button>
        </div>
        <div class="icons">
            <button>❤️</button>
            <button>🛒</button>
        </div>
    </div>

    <!-- Ürün Listesi -->
    <div class="container">
        <div class="products">
            <div class="product-card">
                <img src="https://via.placeholder.com/150" alt="Ürün 1">
                <h2>Ürün 1</h2>
                <p>₺100</p>
                <button>Sepete Ekle</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/150" alt="Ürün 2">
                <h2>Ürün 2</h2>
                <p>₺200</p>
                <button>Sepete Ekle</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/150" alt="Ürün 3">
                <h2>Ürün 3</h2>
                <p>₺300</p>
                <button>Sepete Ekle</button>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/150" alt="Ürün 4">
                <h2>Ürün 4</h2>
                <p>₺400</p>
                <button>Sepete Ekle</button>
            </div>
        </div>
    </div>

</body>
</html>
