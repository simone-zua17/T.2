
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercício 2 - Card Simples</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .card {
            width: 300px;
            padding: 20px;
            background: linear-gradient(135deg, #ffffff, #f8f8f8);
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
            box-shadow: 6px 6px 12px rgba(0, 0, 0, 0.35);
        }

        h2 {
            color: #333;
            font-size: 22px;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        p {
            color: #555;
            font-size: 16px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="card">
        <h2>ZUN´S AUTO CARD</h2>
        <p>VENHA VISITAR AS NOSSAS GARAGENS ÚNICAS.</p>
    </div>
</body>
</html>
