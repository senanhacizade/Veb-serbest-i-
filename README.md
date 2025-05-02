# Veb serbest is

#Html

<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Əşya Kirayələmə</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1 class="logo">Əşya Kirayələmə</h1>
      <nav class="nav">
        <ul>
          <li><a href="#">Ana Səhifə</a></li>
          <li><a href="#">Necə işləyir?</a></li>
          <li><a href="#">Əşyalar</a></li>
          <li><a href="#">Əlaqə</a></li>
        </ul>
      </nav>
    </div>
  </header>
  <section class="how-it-works">
    <div class="container">
      <h2>Necə işləyir?</h2>
      <ol>
        <li>Sayta daxil olun və qeydiyyatdan keçin.</li>
        <li>İstədiyiniz əşyanı seçin və rezervasiya edin.</li>
        <li>Əşyanı götür və istifadə et.</li>
        <li>Müddət bitdikdən sonra geri qaytarın.</li>
      </ol>
    </div>
  </section>
</body>
</html>
#Css
body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  .container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
  }
  .site-header {
    background-color: #2c3e50;
    color: white;
    padding: 20px 0;
  }
  .logo {
    margin: 0;
  }
  .nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    gap: 20px;
  }
  .nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
  }
  .how-it-works {
    padding: 40px 0;
    background-color: #f5f5f5;
  }
  .how-it-works h2 {
    margin-bottom: 20px;
  }
  .how-it-works ol {
    padding-left: 20px;
  } 
