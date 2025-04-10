<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SHO Atacado - Checkout</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 500px;
      margin: 50px auto;
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
    }
    .product-img {
      width: 100%;
      border-radius: 12px;
    }
    .title {
      font-size: 24px;
      font-weight: bold;
      margin: 20px 0 10px;
    }
    .price {
      font-size: 20px;
      color: #d60000;
      font-weight: bold;
    }
    .instructions {
      margin-top: 20px;
      font-size: 16px;
    }
    .pix {
      background: #eee;
      padding: 15px;
      border-radius: 8px;
      font-size: 16px;
      margin-top: 10px;
    }
    .cta {
      margin-top: 30px;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .cta a {
      background: #25d366;
      color: #fff;
      padding: 12px;
      border-radius: 8px;
      text-align: center;
      text-decoration: none;
      font-weight: bold;
    }
    .cta a.copy {
      background: #007bff;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="https://images.unsplash.com/photo-1611078489935-0cb9645b8a96" alt="Panela Premium" class="product-img">
    <div class="title">Panela Premium Antiaderente - Alta Durabilidade</div>
    <div class="price">R$ 89,99</div>

    <div class="instructions">
      Para concluir seu pedido, faça o pagamento via PIX:
      <div class="pix">
        <strong>Chave PIX (CPF):</strong> 04368542010<br>
        <strong>Valor:</strong> R$ 89,99
      </div>
    </div>

    <div class="cta">
      <a href="https://wa.me/555384794295?text=Ol%C3%A1%2C+acabei+de+fazer+o+PIX+de+R%2489%2C99+da+Panela+Premium+e+estou+enviando+o+comprovante." target="_blank">Enviar Comprovante pelo WhatsApp</a>
      <a class="copy" onclick="navigator.clipboard.writeText('04368542010'); alert('Chave PIX copiada!');">Copiar Chave PIX</a>
    </div>
  </div>
</body>
</html>
