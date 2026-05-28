<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>iPhone 17 Pro Max</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background:#f4f4f4;
      color:#222;
    }

    /* HEADER */
    header{
      background:black;
      color:white;
      padding:20px 60px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:sticky;
      top:0;
    }

    .logo{
      font-size:30px;
      font-weight:bold;
    }

    nav a{
      color:white;
      text-decoration:none;
      margin-left:20px;
      font-size:18px;
    }

    nav a:hover{
      color:#999;
    }

    /* BANNER */
    .banner{
      height:90vh;
      background:url('https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?q=80&w=1600&auto=format&fit=crop') center/cover no-repeat;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      color:white;
    }

    .banner-content{
      background:rgba(0,0,0,0.6);
      padding:50px;
      border-radius:20px;
    }

    .banner h1{
      font-size:70px;
      margin-bottom:20px;
    }

    .banner p{
      font-size:24px;
      margin-bottom:30px;
    }

    .btn{
      background:white;
      color:black;
      padding:14px 30px;
      text-decoration:none;
      border-radius:10px;
      font-weight:bold;
      transition:0.3s;
    }

    .btn:hover{
      background:#d1d1d1;
    }

    /* FEATURES */
    .features{
      padding:80px 50px;
      text-align:center;
    }

    .features h2{
      font-size:45px;
      margin-bottom:50px;
    }

    .feature-list{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(280px, 1fr));
      gap:30px;
    }

    .card{
      background:white;
      border-radius:20px;
      overflow:hidden;
      box-shadow:0 4px 15px rgba(0,0,0,0.1);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-10px);
    }

    .card img{
      width:100%;
      height:250px;
      object-fit:cover;
    }

    .card h3{
      margin:20px 0 10px;
      font-size:25px;
    }

    .card p{
      padding:0 20px 25px;
      font-size:16px;
    }

    /* FOOTER */
    footer{
      background:black;
      color:white;
      text-align:center;
      padding:25px;
      margin-top:50px;
    }

    @media(max-width:768px){

      header{
        flex-direction:column;
      }

      nav{
        margin-top:10px;
      }

      .banner h1{
        font-size:45px;
      }

      .banner p{
        font-size:18px;
      }
    }

  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <div class="logo"> iPhone 17 Pro Max</div>

    <nav>
      <a href="#">Trang chủ</a>
      <a href="#">Thiết kế</a>
      <a href="#">Tính năng</a>
      <a href="#">Liên hệ</a>
    </nav>
  </header>

  <!-- BANNER -->
  <section class="banner">
    <div class="banner-content">
      <h1>iPhone 17 Pro Max</h1>
      <p>Sức mạnh vượt giới hạn</p>
      <a href="#" class="btn">Khám phá ngay</a>
    </div>
  </section>

  <!-- FEATURES -->
  <section class="features">

    <h2>Tính năng nổi bật</h2>

    <div class="feature-list">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1512499617640-c74ae3a79d37?q=80&w=1200&auto=format&fit=crop" alt="camera">
        <h3>Camera AI 200MP</h3>
        <p>Chụp ảnh siêu nét với công nghệ AI hiện đại và quay video chuẩn điện ảnh.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1580910051074-3eb694886505?q=80&w=1200&auto=format&fit=crop" alt="chip">
        <h3>Chip A19 Pro</h3>
        <p>Hiệu năng mạnh mẽ giúp gaming, chỉnh sửa video và đa nhiệm mượt mà.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1603899122634-f086ca5f5ddd?q=80&w=1200&auto=format&fit=crop" alt="battery">
        <h3>Pin cả ngày</h3>
        <p>Pin dung lượng lớn cùng công nghệ sạc nhanh thế hệ mới.</p>
      </div>

    </div>

  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2026 Apple Việt Nam | Hotline: 1800 9999</p>
  </footer>

</body>
</html>
