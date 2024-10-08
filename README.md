<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Componentes de PC</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 10px;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            text-align: center;
        }
        .product img {
            width: 200px;
            height: auto;
            margin-bottom: 15px;
        }
        .product h3 {
            margin: 0 0 10px;
        }
        .product p {
            color: #555;
            font-size: 16px;
        }
        .product button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Componentes de PC - Tienda Online</h1>
</header>

<div class="container">
    <!-- Producto 1 -->
    <div class="product">
        <img src="https://example.com/image1.jpg" alt="Producto 1">
        <h3>Tarjeta Gráfica RTX 3080</h3>
        <p>La mejor tarjeta gráfica para tus juegos y proyectos.</p>
        <button onclick="addToCart('Tarjeta Gráfica RTX 3080')">Añadir al Carrito</button>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="https://example.com/image2.jpg" alt="Producto 2">
        <h3>Procesador Intel i9</h3>
        <p>Potencia y velocidad para tareas exigentes.</p>
        <button onclick="addToCart('Procesador Intel i9')">Añadir al Carrito</button>
    </div>

    <!-- Producto 3 -->
    <div class="product">
        <img src="https://example.com/image3.jpg" alt="Producto 3">
        <h3>SSD Samsung 1TB</h3>
        <p>Almacenamiento rápido y fiable para tu PC.</p>
        <button onclick="addToCart('SSD Samsung 1TB')">Añadir al Carrito</button>
    </div>
</div>

<footer>
    <p>&copy; 2024 Tienda de Componentes de PC</p>
</footer>

<script>
    function addToCart(productName) {
        alert(productName + ' ha sido añadido al carrito.');
    }
</script>

</body>
</html>
