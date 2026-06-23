<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>coffee shop</title>

    <style>

        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body{
            background-color: #f5f5f5;
        }

        /* HEADER */
        .header{
            background-color: #3e2723;
            color: rgb(255, 255, 255);
            padding: 20px;
            text-align: center;
        }

        .header h1{
            font-size: 40px;
        }

        /* NAVBAR */
        .navbar{
            background-color: #5d4037;
            padding: 15px;
            text-align: center;
        }

        .navbar a{
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        navbar a:hover{
            color: #ffd54f;
        }

        /* HERO */
        .hero{
            height: 300px;
            background-image:
            url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085');
            background-size: cover;
            background-position: center;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px black;
        }

        .hero h2{
            font-size: 45px;
        }

        /* CONTENT */
        .content{
            display: flex;
            padding: 30px;
            gap: 20px;
        }

        .card{
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0, 2);
            flex: 1;
            text-align: center;
        }

        .card img{
            width: 100%;
            border-radius: 10px;
        }

        .card h3{
            margin: 15px 0;
            color: #3e2723;
        }

        .card p{
            color: #555;
        }

        /* FOOTER */
        .footer{
            background-color: #3e2723;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        
    </style>
</head>
<body>

    <!-- HEADER -->
     <div class="header">
        <h1>Ripan Coffee Shop</h1>
        <p>Nikmat Kopi Terbaik Setiap Hari</p>
     </div>

     <!-- NAVBAR -->
      <div class="navbar">
        <a href="#">Home</a>
        <a href="#">Menu</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
      </div>

      <!-- HERO -->
       <div class="hero">
        <h2>Fresh Coffee & Cozy Place</h2>
       </div>

       <!-- CONTENT -->
    <div class="content">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" alt="coffee">
            <h3>Expresso</h3>
            <p>kopi expresso dengan cinta rasa kuat dan aroma khas.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085" alt="Coffee">
            <h3>cappuccino</h3>
            <p>Perpaduan kopi, susu, dan foam yang lembut.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348" alt="Coffee">
            <h3>Latte</h3>
            <p>Minuman kopi creamy yang cocok untuk santai.</p>
        </div>
    </div>
    
    <!-- FOOTER -->
     <div class="footer">
        <p>@ 2026 Ripan Coffee Shop | All Rights Reseved</p>
     </div>

</body>
</html>
