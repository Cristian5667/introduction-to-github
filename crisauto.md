<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AutoLux - Mașini de vânzare</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }
        .car-card {
            background: white;
            border-radius: 8px;
            margin: 15px;
            width: 300px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .car-card:hover {
            transform: scale(1.03);
        }
        .car-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .car-details {
            padding: 15px;
        }
        .car-details h3 {
            margin-top: 0;
        }
        .price {
            color: green;
            font-size: 1.2em;
            margin: 10px 0;
        }
        .contact-button {
            display: block;
            background: #007bff;
            color: white;
            text-align: center;
            padding: 10px;
            text-decoration: none;
            border-radius: 4px;
        }
        .contact-button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

<header>
    <h1>AutoLux</h1>
    <p>Mașini de vânzare - Calitate și preț corect</p>
</header>

<div class="container">

    <!-- Mașina 1 -->
    <div class="car-card">
        <img src="https://cdn.pixabay.com/photo/2016/11/29/06/15/audi-1868726_1280.jpg" alt="Audi A4 2016">
        <div class="car-details">
            <h3>Audi A4 2016</h3>
            <p>Diesel, 2.0 TDI, automată, 150.000 km</p>
            <div class="price">€12.500</div>
            <a href="mailto:contact@autolux.ro?subject=Interesat de Audi A4 2016" class="contact-button">Contactează</a>
        </div>
    </div>

    <!-- Mașina 2 -->
    <div class="car-card">
        <img src="https://cdn.pixabay.com/photo/2016/03/27/17/42/bmw-1281640_1280.jpg" alt="BMW Seria 3 2014">
        <div class="car-details">
            <h3>BMW Seria 3 2014</h3>
            <p>Benzină, 1.6 Turbo, manuală, 135.000 km</p>
            <div class="price">€10.900</div>
            <a href="mailto:contact@autolux.ro?subject=Interesat de BMW Seria 3 2014" class="contact-button">Contactează</a>
        </div>
    </div>

    <!-- Mașina 3 -->
    <div class="car-card">
        <img src="https://cdn.pixabay.com/photo/2015/01/19/13/51/jeep-604005_1280.jpg" alt="Jeep Grand Cherokee 2017">
        <div class="car-details">
            <h3>Jeep Grand Cherokee 2017</h3>
            <p>Diesel, 3.0 V6, 4x4, 120.000 km</p>
            <div class="price">€19.800</div>
            <a href="mailto:contact@autolux.ro?subject=Interesat de Jeep Grand Cherokee 2017" class="contact-button">Contactează</a>
        </div>
    </div>

    <!-- Mașina 4 -->
    <div class="car-card">
        <img src="https://cdn.pixabay.com/photo/2017/03/27/14/56/volkswagen-2179277_1280.jpg" alt="Volkswagen Golf 7 2015">
        <div class="car-details">
            <h3>VW Golf 7 2015</h3>
            <p>Diesel, 1.6 TDI, manuală, 160.000 km</p>
            <div class="price">€8.300</div>
            <a href="mailto:contact@autolux.ro?subject=Interesat de VW Golf 7 2015" class="contact-button">Contactează</a>
        </div>
    </div>

    <!-- Mașina 5 -->
    <div class="car-card">
        <img src="https://cdn.pixabay.com/photo/2020/05/25/19/20/mercedes-benz-5220605_1280.jpg" alt="Mercedes C-Class 2018">
        <div class="car-details">
            <h3>Mercedes C-Class 2018</h3>
            <p>Diesel, 2.0, automată, 100.000 km</p>
            <div class="price">€21.900</div>
            <a href="mailto:contact@autolux.ro?subject=Interesat de Mercedes C-Class 2018" class="contact-button">Contactează</a>
        </div>
    </div>

    <!-- Mașina 6 -->
    <div class="car-card">
        <img src="https://cdn.pixabay.com/photo/2013/07/13/12/07/car-159837_1280.png" alt="Ford Focus 2013">
        <div class="car-details">
            <h3>Ford Focus 2013</h3>
            <p>Benzină, 1.0 EcoBoost, 140.000 km</p>
            <div class="price">€6.800</div>
            <a href="mailto:contact@autolux.ro?subject=Interesat de Ford Focus 2013" class="contact-button">Contactează</a>
        </div>
    </div>

</div>

</body>
</html>
