PK     ξZï8lÓÂ
  Â
  
   index.html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>AffiPub - Produits Recommandés</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --primary: #007bff;
      --bg: #f9f9f9;
      --card-bg: #ffffff;
      --text: #333;
      --shadow: rgba(0, 0, 0, 0.1);
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--bg);
      color: var(--text);
    }

    header {
      background: var(--primary);
      color: white;
      text-align: center;
      padding: 20px 10px;
      font-size: 24px;
      font-weight: bold;
    }

    .container {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 20px;
    }

    .product {
      background: var(--card-bg);
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 12px var(--shadow);
      transition: transform 0.2s;
    }

    .product:hover {
      transform: scale(1.02);
    }

    .product img {
      width: 100%;
      height: auto;
    }

    .product-content {
      padding: 10px;
      text-align: center;
    }

    .product-title {
      font-size: 16px;
      font-weight: 600;
      margin: 10px 0;
    }

    .badge {
      position: absolute;
      background: #28a745;
      color: white;
      font-size: 12px;
      padding: 3px 8px;
      border-radius: 4px;
      top: 10px;
      left: 10px;
    }

    a {
      color: inherit;
      text-decoration: none;
      position: relative;
      display: block;
    }

    @media (max-width: 600px) {
      header {
        font-size: 20px;
        padding: 15px;
      }
    }
  </style>
</head>
<body>
  <header>AffiPub - Sélections Amazon & Zendrop</header>
  <div class="container">
    <div class="grid">
      <div class="product">
        <a href="https://www.amazon.fr/dp/EXEMPLE1?tag=toncode-21" target="_blank">
          <span class="badge">Amazon</span>
          <img src="https://via.placeholder.com/200x200?text=Whey" alt="Whey Amazon">
          <div class="product-content">
            <div class="product-title">Whey Protéine Amazon</div>
          </div>
        </a>
      </div>
      <div class="product">
        <a href="https://zendrop.com/produit-exemple" target="_blank">
          <span class="badge" style="background:#ff6347;">Zendrop</span>
          <img src="https://via.placeholder.com/200x200?text=Shaker" alt="Shaker Zendrop">
          <div class="product-content">
            <div class="product-title">Shaker Premium Zendrop</div>
          </div>
        </a>
      </div>
    </div>
  </div>
</body>
</html>
PK     ξZï8lÓÂ
  Â
  
           ¤    index.htmlPK      8   ê
    
