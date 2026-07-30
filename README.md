index.html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Ajwad Meal Boxes</title>
    <style>
        /* Pengaturan Warna dan Font Dasar */
        :root {
            --maroon: #3d0309; /* Warna latar belakang merah gelap */
            --gold: #c29d5b;   /* Warna aksen emas */
            --white: #fdfdfd;
            --black: #0a0a0a;
        }
        
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--maroon);
            color: var(--white);
        }

        /* Bagian Header (Judul Restoran) */
        header {
            text-align: center;
            padding: 50px 20px 30px;
            background-image: linear-gradient(to bottom, #1f0003, var(--maroon));
            border-bottom: 2px solid var(--gold);
        }
        
        header h1 {
            font-family: 'Georgia', serif;
            color: var(--white);
            font-size: 3.5rem;
            margin: 0;
            font-style: italic;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .subtitle {
            color: var(--gold);
            text-transform: uppercase;
            letter-spacing: 2px;
            font-size: 0.85rem;
            margin-top: -10px;
            margin-bottom: 30px;
        }
        
        header h2 {
            font-family: 'Georgia', serif;
            font-size: 2.5rem;
            margin: 10px 0;
            letter-spacing: 1px;
        }
        
        header p {
            font-size: 1.2rem;
            margin: 10px 0;
            font-style: italic;
            color: #dddddd;
        }
        
        .contact {
            display: inline-block;
            background-color: var(--gold);
            color: var(--maroon);
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: bold;
            text-decoration: none;
            margin-top: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
            transition: transform 0.2s;
        }

        .contact:hover {
            transform: scale(1.05);
        }

        /* Bagian Grid Menu */
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        
        .menu-item {
            background-color: var(--black);
            border: 1px solid var(--gold);
            border-radius: 12px;
            padding: 25px;
            text-align: center;
            box-shadow: 0 8px 15px rgba(0,0,0,0.4);
            position: relative;
        }
        
        .menu-item::before {
            content: '';
            position: absolute;
            top: 5px; left: 5px; right: 5px; bottom: 5px;
            border: 1px dashed rgba(194, 157, 91, 0.3);
            border-radius: 8px;
            pointer-events: none;
        }
        
        .menu-item h3 {
            color: var(--gold);
            margin-top: 0;
            font-family: 'Georgia', serif;
            font-size: 1.8rem;
            border-bottom: 1px solid #333;
            padding-bottom: 15px;
            margin-bottom: 15px;
        }
        
        .menu-item p {
            font-size: 1.1rem;
            line-height: 1.6;
            margin: 0;
            color: #eeeeee;
        }

        /* Bagian Footer */
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            font-size: 0.9rem;
            color: #888;
            background-color: #1a0104;
        }
    </style>
</head>
<body>

    <header>
        <h1>Ajwad</h1>
        <div class="subtitle">Original Arabian Cuisine</div>
        <h2>MEAL BOXES</h2>
        <p>"Feel free to mix and match!"</p>
        <a href="https://wa.me/6281113301010" class="contact">📞 08111 330 10 10</a>
    </header>

    <div class="container">
        <div class="menu-grid">
            <div class="menu-item">
                <h3>Ajeeb 1</h3>
                <p>Ayam, Mie Goreng Kambing, & Nasi Mandhi</p>
            </div>
            
            <div class="menu-item">
                <h3>Ajeeb 2</h3>
                <p>Ayam, Buncis Kambing, & Nasi Mandhi</p>
            </div>
            
            <div class="menu-item">
                <h3>Ajeeb 3</h3>
                <p>Ayam, Sambosa, & Kentang Goreng</p>
            </div>
            
            <div class="menu-item">
                <h3>Ajeeb 4</h3>
                <p>Sate Maranggi, Sambosa Keju & Kentang Goreng</p>
            </div>
            
            <div class="menu-item">
                <h3>Ajeeb 5</h3>
                <p>Roti, Kambing, & Telor</p>
            </div>
            
            <div class="menu-item">
                <h3>Ajeeb 6</h3>
                <p>Roti, Tuna, & Kari Kentang</p>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2026 Ajwad Original Arabian Cuisine. All rights reserved.
    </footer>

</body>
</html>
