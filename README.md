# Reclutamiento-ww1
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Web sencilla</title>
    <style>
body {
    font-family: "Times New Roman", serif;
    margin: 0;
    background-image: url("https://image.slidesdocs.com/responsive-images/background/texture-of-grungy-cardboard-with-worn-out-paper-sheet-powerpoint-background_e19ebd09a3__960_540.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    
    color: #2b1d0e; /* Color tinta oscura */
}
.contenedor {
    max-width: 900px;
    margin: 40px auto;
    padding: 40px;
    background: rgba(245, 222, 179, 0.85);
    border: 3px solid #3b2a1a;
    box-shadow: 0 0 25px rgba(0,0,0,0.6);
    position: relative;
}
.contenedor::before {
    content: "CONFIDENCIAL";
    position: absolute;
    top: 20px;
    right: -40px;
    transform: rotate(-25deg);
    font-size: 40px;
    color: rgba(120, 0, 0, 0.4);
    border: 3px solid rgba(120, 0, 0, 0.4);
    padding: 10px 20px;
    font-weight: bold;
    letter-spacing: 3px;
}
header {
    text-align: center;
    padding-bottom: 20px;
    border-bottom: 2px solid #3b2a1a;
}

header h1 {
    font-size: 32px;
    letter-spacing: 4px;
    text-transform: uppercase;
}

header h2 {
    font-size: 18px;
    font-weight: normal;
    margin-top: 5px;
}
.seccion {
    margin: 25px 0;
    padding: 15px;
    border: 1px dashed #3b2a1a;
    background: rgba(255,255,255,0.2);
}

.seccion h3 {
    text-transform: uppercase;
    border-bottom: 1px solid #3b2a1a;
    padding-bottom: 5px;
    margin-bottom: 10px;
    letter-spacing: 2px;
}
.especial {
    display: flex;
    align-items: center;
    gap: 25px;
}

.imagen img {
    width: 160px;
    border: 3px solid #3b2a1a;
    padding: 3px;
    background: #e6d3b3;
    filter: sepia(60%) contrast(90%);
}
.texto {
    flex: 1;
    font-size: 18px;
    line-height: 1.6;
}
input, textarea {
    width: 100%;
    border: none;
    border-bottom: 1px solid #3b2a1a;
    background: transparent;
    font-family: "Courier New", monospace;
    font-size: 16px;
    padding: 5px;
}
footer {
    text-align: center;
    margin-top: 30px;
    font-size: 14px;
    border-top: 2px solid #3b2a1a;
    padding-top: 10px;
}

</style>

</head>
 
<body>
 
<header>
<h1>Esta pagina busca recrear como seria el reclutamiento militar antigüo en HTML</h1>
</header>
 
<main>
 
    <div class="seccion">
<h2>¡CIUDADANOS!
</h2>
<p>En esta hora solemne, cuando los cañones retumban en el horizonte y el destino de nuestra Nación pende de la voluntad de sus hijos, el deber llama con voz firme e ineludible. No es tiempo de dudas ni vacilaciones; es tiempo de hombres decididos, de corazones ardientes y espíritus indomables.

Nuestros campos, nuestras ciudades, nuestros hogares —todo aquello que amamos— confían en el valor de quienes estén dispuestos a defenderlos. Más allá de las colinas y los ríos, nuestros soldados ya sostienen la línea con disciplina y honor. En las trincheras, bajo la lluvia y el estruendo del combate, resisten con la mirada puesta en la bandera y el recuerdo de sus familias.</p>
</div>
 
    <div class="seccion especial">
<div class="imagen">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTt8faL19ShcQi0nUqtYaEYFOcbKsTvCFeYsg&s"> <style: imagen>
</div>
      
 
        <div class="texto">
<h2>¡LA PATRIA OS NECESITA!</h2>
<p>
               Cada paso al frente es un juramento.
Cada uniforme, un símbolo de orgullo.
Cada sacrificio, una promesa de libertad.

¿Dejarás que otros carguen con el peso de la historia mientras tú permaneces al margen? ¿Consentirás que el sacrificio recaiga únicamente en los hombros de tus compatriotas? La Nación no pide lo imposible: pide valor, compromiso y lealtad.

Alistarse no es solo empuñar un fusil; es abrazar el honor. Es demostrar que la sangre que corre por tus venas late al ritmo del deber. Es forjar, con coraje y disciplina, el futuro que heredarán nuestros hijos.
</p>
</div>
</div>
 
    <div class="seccion">
<h2>¡A LA VICTORIA!</h2>
<p>La victoria pertenece a quienes se atreven.
La gloria acompaña a quienes responden.
El recuerdo eterno honra a quienes sirven.

Acude hoy mismo al puesto de reclutamiento más cercano.
Marcha con orgullo bajo los colores de tu bandera.
Haz que tu nombre sea pronunciado con respeto.

¡Alístate!
Por tu familia.
Por tu honor.
Por la Patria.</p>
</div>
 
</main>
 
<footer>
<p></p>
</footer>
</body>
 </html>
