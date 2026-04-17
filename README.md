<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Butacas - Mueblería Ancajima</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f5f5f5;
}

header {
    background: #111;
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
}

.container {
    padding: 20px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 10px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card-content {
    padding: 15px;
}

.card-content h3 {
    margin: 0 0 10px;
}

.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 15px;
    background: #25D366;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>
    <h1>Mueblería Ancajima</h1>
    <p>Catálogo de Butacas</p>
</header>

<div class="container">
    <div class="grid">

        <!-- Producto 1 -->
        <div class="card">
            <img src="AQUI_TU_IMAGEN_1.jpg">
            <div class="card-content">
                <h3>Butaca Moderna</h3>
                <p>Diseño elegante y cómodo para tu sala.</p>
                <a class="btn" href="https://wa.me/51998884070?text=Hola,%20quiero%20cotizar%20una%20butaca%20moderna">Cotizar</a>
            </div>
        </div>

        <!-- Producto 2 -->
        <div class="card">
            <img src="AQUI_TU_IMAGEN_2.jpg">
            <div class="card-content">
                <h3>Butaca Clásica</h3>
                <p>Estilo tradicional con gran comodidad.</p>
                <a class="btn" href="https://wa.me/51998884070?text=Hola,%20quiero%20cotizar%20una%20butaca%20clásica">Cotizar</a>
            </div>
        </div>

        <!-- Producto 3 -->
        <div class="card">
            <img src="AQUI_TU_IMAGEN_3.jpg">
            <div class="card-content">
                <h3>Butaca Premium</h3>
                <p>Materiales de alta calidad.</p>
                <a class="btn" href="https://wa.me/51998884070?text=Hola,%20quiero%20cotizar%20una%20butaca%20premium">Cotizar</a>
            </div>
        </div>

    </div>
</div>

<footer>
    <p>© 2026 Mueblería Ancajima</p>
</footer>

</body>
</html>
