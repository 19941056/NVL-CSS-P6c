# NVL-CSS-P6c
Selectores 3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selectores III</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    Ingredientes para receta: <i lang="es-ES">Rabo de Toro</i>
    <ul>
        <li data-cantidad="2'5 Kg" data-meat>Rabo de ternera</li>
        <li data-cantidad="2" data-vegetal="naranja">Zanahorias</li>
        <li data-cantidad="3 (solo parte blanca)" data-vegetal="verd">Puerros</li>
        <li data-cantidad="3" data-vegetal="verd" >Cebollas</li>
        <li data-cantidad="2" data-vegetal="rojo">Tomates</li>
        <li data-cantidad="4" data-vegetal="verd">Ajos</li>
        <li data-cantidad="3" data-vegetal="verd">Hojas de laurel</li>
        <li data-cantidad="Un poco">Sal</li>
        <li data-cantidad="Un poco">Pimienta</li>
        <li data-cantidad="Un poco">Harina</li>
        <li data-cantidad="1,5 l">Vino tinto</li>
        <li data-cantidad="Un chorreón" data-meat=>Caldo de carne</li>
    </ul>
    <img src="rabodetoro.jpg" width="20%" height="200vh" alt="">
    <form method="POST" action="miservidor.php"></form>
    <div>
        <label for="Comentarios">Comentarios</label>
        <textarea name="" id="Comentarios" cols="" rows=""></textarea>
    </div>
    <input type="submit" value="Enviar">
    
</body>
</html>

[data-vegetal="verd"] {
    color: green;
}
[data-vegetal="rojo"] {
    color: red;
}
[data-vegetal="naranja"] {
    color: orange;
}
[data-meat] {
    color:rgb(128, 88, 16);
}
img {
    box-sizing: border-box;
}
