# animaleeees
Animaleeees
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mundo Animal</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:linear-gradient(to bottom, #dff9fb, #c7ecee);
    text-align:center;
}

header{
    background:#22a6b3;
    color:white;
    padding:30px;
    font-size:35px;
    font-weight:bold;
}

.contenedor{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
    padding:30px;
}

.tarjeta{
    background:white;
    width:250px;
    border-radius:20px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,0.2);
    transition:0.3s;
}

.tarjeta:hover{
    transform:scale(1.05);
}

.tarjeta img{
    width:100%;
    height:180px;
    object-fit:cover;
}

.tarjeta h2{
    color:#22a6b3;
}

.tarjeta p{
    padding:10px;
}

button{
    background:#22a6b3;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:10px;
    margin-bottom:20px;
    cursor:pointer;
    font-size:16px;
}

button:hover{
    background:#1b7f89;
}

footer{
    background:#22a6b3;
    color:white;
    padding:15px;
    margin-top:20px;
}
</style>
</head>

<body>

<header>
🐾 Mundo Animal 🐾
</header>

<div class="contenedor">

<div class="tarjeta">
<img src="https://images.unsplash.com/photo-1517849845537-4d257902454a" alt="Perro">
<h2>Perro</h2>
<p>Los perros son leales, juguetones y grandes compañeros.</p>
<button onclick="alert('¡Los perros pueden aprender muchos trucos!')">
Dato curioso
</button>
</div>

<div class="tarjeta">
<img src="https://images.unsplash.com/photo-1519052537078-e6302a4968d4" alt="Gato">
<h2>Gato</h2>
<p>Los gatos son independientes y muy adorables.</p>
<button onclick="alert('¡Los gatos duermen hasta 16 horas al día!')">
Dato curioso
</button>
</div>

<div class="tarjeta">
<img src="https://images.unsplash.com/photo-1501706362039-c6e80948bb31" alt="Tigre">
<h2>Tigre</h2>
<p>El tigre es uno de los felinos más fuertes del mundo.</p>
<button onclick="alert('¡Cada tigre tiene rayas únicas!')">
Dato curioso
</button>
</div>

</div>

<footer>
Hecho por Genesis 💙
</footer>

</body>
</html>