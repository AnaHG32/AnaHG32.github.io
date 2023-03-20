<html>
<head>
	<title>Mi Curriculum Vítae</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" type="image/x-icon" href="th_bing_com-OIP.ico">
	<<link rel="stylesheet" href="CSS/estilos.css" />
	<link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital@1&family=Roboto:wght@300&display=swap" rel="stylesheet">
    <script>
		function cambiartexto() {
			cont.innerHTML=cont.innerHTML=="Mi e-mail"?"Gracias!":"Mi e-mail";
		}
	</script>
<body>
<section>
    <h1>Mi curriculum</h1>
    <p id="cont">Mi e-mail</p>
    <a href="mailto:fernando.hansen@example.com"><button type="button" onclick="cambiartexto(); myFunction()">Contactame!</button></a>

    <script>
        function myFunction() {  
        document.getElementById("cont").style.fontSize = "50px"; 
        document.getElementById("cont").style.color = "grey";
        document.getElementById("cont").style.backgroundColor = "PaleGoldenrod"; 
        document.getElementById("cont").style.textShadow = "black 3px 4px";
}
    </script>

</section>
<section id="contenedor">
    <section id="sidebar">
        <h1 onmouseover="showImage()">Datos personales</h1>
        <script>
            function showImage() {
            var img = document.getElementById ("miImagen");
            img.src = "https://th.bing.com/th/id/OIP.YjWnvN5BrFfnL2t_C7t5QAAAAA?pid=ImgDet&w=391&h=576&rs=1"; 
            img.style.display = "block";        
            }
        </script>
        <img id="miImagen" alt="Fernando Hansen">
        <ul>
            <li><strong>Nombre:</strong>Fernando Hansen</li>
            <li><strong>Teléfono:</strong> (829) 632-6765</li>
            <li><strong>Correo electrónico:</strong>fernando.hansen@example.com</li>
            <li><strong>Nacimiento:</strong>8/5/1991</li>
            <li><strong>Dirección:</strong>452 E Center St</li>
        </ul>
    </section>
<section id="principal">
    <section>
        <h1>Experiencia laboral</h1>
            <ul>
                <li>
                    <h2>Empresa ABC</h2>
                    <ul>
                    <li><strong>Puesto:</strong> Desarrollador web</li>
                    <li><strong>Fecha de inicio:</strong> Enero 2020</li>
                    <li><strong>Fecha de término:</strong> Presente</li>
                    <li><strong>Descripción:</strong> Desarrollo de aplicaciones web utilizando tecnologías como HTML, CSS, JavaScript, PHP y MySQL.</li>
                    </ul>
                </li>
                <li>
                    <h2>Empresa XYZ</h2>
                    <ul>
                    <li><strong>Puesto:</strong> Analista de datos</li>
                    <li><strong>Fecha de inicio:</strong> Mayo 2018</li>
                    <li><strong>Fecha de término:</strong> Diciembre 2019</li>
                    <li><strong>Descripción:</strong> Análisis de datos para mejorar la eficiencia de los procesos empresariales.</li>
                    </ul>
                </li>
            </ul>
    </section>
    <section>
        <h1 >Formación académica</h1>
        <ul>
            <li>
            <h2>Universidad Nacional</h2>
                <ul>
                <li><strong>Carrera:</strong> Licenciatura en Informática</li>
                <li><strong>Fecha de inicio:</strong> Agosto 2014</li>
                <li><strong>Fecha de término:</strong> Diciembre 2018</li>
                </ul>
            </li>
        </ul>
    </section>
</section>
</section>
</body>

