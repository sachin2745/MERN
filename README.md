# MERN
Journey of Mern 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:100,100italic,300,300italic,regular,italic,500,500italic,700,700italic,900,900italic" rel="stylesheet" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<style>
    :root{
        --theme-color:100px;
    }
        body{
            margin: 0;
        }

        header{
            background-image: url('https://images.hdqwalls.com/download/dark-road-clouds-over-landscape-view-front-al-2560x1440.jpg');
            color: white;
            height: 60vh;
            background-size: cover;
            text-align: center;
            padding-top: 300px;
            /* box-sizing: border-box; */
        }

        .hero-title{
            margin: 0;
        }
        .hero-btn{
            padding: 10px 12px;
            background-color: WHITE;
            font-family: Georgia, 'Times New Roman', Times, serif;
            border: 3px;
            border-radius: 9px;
        }
        .feature-card{
            width: 200px;
            border: 3px solid red;
            border-radius: 80px;
            text-align: center;
            padding: 50px;
            margin: 20px;
            margin-left: 80px;
            text-align: center;
            font-family:roboto;
        }
        
        .card-container
        {
            display:flex;
            width: 100%;
            
        }
        .card-container :hover
        {
            background-color: aqua;
            transition-duration: 0.3s;
            border-radius: 30px;
        
        }
        .section-features{
            color: rgb(56, 7, 44);
            font-size: var(--theme-color:large);
        }
    </style>

</head>

<body>

    <header>
        <h1 class="hero-title" style="text-align: center; font-size: 4rem;">Welcome to my site</h1>
        <h3 class="hero-subtitle">Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quod doloribus architecto sunt beatae dolor optio ullam quia aut! Magnam.</h3>
        <button class="hero-btn">Learn More</button>
    </header>

    <main>
      
        <section class="section-features">
            <h2 class="section-title" style="text-align: center;font-family:roboto; font-size:2rem;">Our Features</h2> 
            <div class="card-container">
<div class="feature-card">
    <i class="fa-3x fa-solid fa-rocket"></i>
    <h3>Fast Delivery</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, eos.</p>
</div>
<div class="feature-card">
    <i class="fa-3x fa-solid fa-shop"></i>
    <h3>Shop</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, eos.</p>
</div>
<div class="feature-card">
    <i class="fa-3x fa-brands fa-instagram"></i>
    <h3>Instagram</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, eos.</p>
</div>

        </section>
    </div>
    </main>

    <footer>

    </footer>

</body>

</html>
