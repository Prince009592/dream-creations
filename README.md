<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dream Creations | Luxury Handmade Jewellery</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>

body{
    margin:0;
    font-family:'Poppins', sans-serif;
    background: #fff;
    overflow-x:hidden;
}

/* HEADER */
header{
    background: linear-gradient(135deg,#ff4d6d,#ff99ac);
    color:white;
    text-align:center;
    padding:40px 20px;
    animation: fadeDown 1.5s ease;
}

header h1{
    font-family:'Playfair Display', serif;
    font-size:45px;
    margin:0;
}

header p{
    letter-spacing:2px;
}

/* HERO */
.hero{
    text-align:center;
    padding:70px 20px;
}

.hero h2{
    font-family:'Playfair Display', serif;
    font-size:38px;
    color:#ff4d6d;
    animation: fadeUp 2s ease;
}

.hero button{
    padding:12px 30px;
    background:linear-gradient(45deg,#ff4d6d,#ff758f);
    border:none;
    color:white;
    border-radius:30px;
    font-size:16px;
    cursor:pointer;
    margin-top:20px;
    transition:0.3s;
}

.hero button:hover{
    transform:scale(1.1);
}

/* GALLERY */
.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
    padding:50px;
}

.gallery img{
    width:100%;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
    transition:0.4s;
    animation: fadeUp 1.5s ease;
}

.gallery img:hover{
    transform:scale(1.08);
}

/* FOOTER */
footer{
    background:#ff4d6d;
    color:white;
    text-align:center;
    padding:20px;
}

/* ANIMATIONS */
@keyframes fadeUp{
    from{opacity:0; transform:translateY(40px);}
    to{opacity:1; transform:translateY(0);}
}

@keyframes fadeDown{
    from{opacity:0; transform:translateY(-40px);}
    to{opacity:1; transform:translateY(0);}
}

</style>
</head>

<body>

<header>
    <h1>Dream Creations</h1>
    <p>Luxury Handmade Jewellery & Crochet Flowers</p>
</header>

<section class="hero">
    <h2>Elegant • Unique • Handmade With Love</h2>
    <button onclick="window.location.href='#gallery'">Explore Collection</button>
</section>

<section class="gallery" id="gallery">
    <img src="dream_creations._.dc-20260206-0001.jpg">
    <img src="dream_creations._.dc-20260206-0005.jpg">
    <img src="dream_creations._.dc-20260206-0006.jpg">
    <img src="dream_creations._.dc-20260206-0019.jpg">
    <img src="dream_creations._.dc-20260206-0020.jpg">
    <img src="dream_creations._.dc-20260206-0029.jpg">
    <img src="dream_creations._.dc-20260206-0041.jpg">
    <img src="dream_creations._.dc-20260206-0047.jpg">
    <img src="dream_creations._.dc-20260222-0002.jpg">
    <img src="dream_creations._.dc-20260222-0025.jpg">
</section>

<footer>
    © 2026 Dream Creations | Instagram: @dream_creations._.dc
</footer>

</body>
</html>
