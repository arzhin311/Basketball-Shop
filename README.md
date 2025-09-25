<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>T-Shirt Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f2f2f2;
      text-align: center;
    }
    header {
      background: black;
      color: white;
      padding: 20px;
      font-size: 24px;
    }
    .product {
      background: white;
      margin: 20px auto;
      padding: 20px;
      width: 300px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .product img {
      max-width: 100%;
      border-radius: 8px;
    }
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: black;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .btn:hover {
      background: darkred;
    }
  </style>
</head>
<body>

  <header>T-Shirt Shop</header>

  <div class="product">
    <img src="https://via.placeholder.com/300x200?text=Naked+T-Shirt" alt="T-Shirt">
    <h2>Naked T-Shirt</h2>
    <p>Preis: 19,99 €</p>
    <a href="#" class="btn">Jetzt kaufen</a>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/300x200?text=Black+T-Shirt" alt="T-Shirt">
    <h2>Black T-Shirt</h2>
    <p>Preis: 24,99 €</p>
    <a href="#" class="btn">Jetzt kaufen</a>
  </div>

</body>
</html>
