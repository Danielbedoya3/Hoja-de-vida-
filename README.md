<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida - Daniel Bedoya Ríos</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <a href="#" class="brand">Daniel Bedoya Ríos</a>
            <span class="hamburger"><i class="fas fa-bars"></i></span>
            <ul class="nav-links">
                <li><a href="#perfil">Perfil</a></li>
                <li><a href="#experiencia">Experiencia</a></li>
                <li><a href="#educacion">Educación</a></li>
                <li><a href="#referencias">Referencias</a></li>
            </ul>
        </div>
    </nav>
    <div class="container">
        <header>
            <img src="img/IMG_20210310_131705.jpg" alt="Foto de Daniel Bedoya Ríos" class="profile-img">
            <h1>Daniel Bedoya Ríos</h1>
            <p><i class="fas fa-id-card"></i> C.C. 1.007.346.299</p>
            <p><i class="fas fa-phone"></i> 3147387472</p>
            <p><i class="fas fa-envelope"></i> danielbedoyarios@gmail.com</p>
            <p><i class="fas fa-map-marker-alt"></i> Calle 24 N # 22-16, La Ceja (Ant)</p>
        </header>

        <div class="section" id="perfil">
            <h2>Perfil Profesional</h2>
            <p>Soy bachiller académico con amplia experiencia y conocimientos en todo lo relacionado con el campo de la logística, conocimiento en control de inventarios, empaque, etiquetado, y todo lo relacionado a los procesos de bodegaje. Me describo como una persona innovadora, íntegra, socialmente comprometida y con gran disposición para enfrentar retos y cambios que ayuden a mejorar los resultados de los servicios que preste y de igual forma fortalezcan mi crecimiento personal.</p>
        </div>

        <div class="section experience" id="experiencia">
            <h2>Experiencias Profesionales</h2>
            <h3>Auxiliar de Logística - Extiblu, Zona Franca Rionegro</h3>
            <p>Septiembre 2022 - Diciembre 2022</p>
            <ul>
                <li>Realización de funciones como picking y packing, cargue y descargue de todo tipo de mercancía.</li>
                <li>Seguimiento a la recepción y despacho de la mercancía.</li>
                <li>Control y garantía de los inventarios físicos de la mercancía.</li>
                <li>Supervisión de las condiciones y manejo de almacenamiento de la mercancía.</li>
            </ul>

            <h3>Operario de Producción - Multivack, FreshColombia, Zona Franca</h3>
            <p>Noviembre 2021 - Septiembre 2022</p>
            <ul>
                <li>Manejo y manipulación de materia prima, manejo de maquinaria.</li>
                <li>Apoyo en diferentes áreas de procesos, control de calidad y manipulación de inventario.</li>
                <li>Manejo de programas de la empresa, análisis del estado del aguacate y descomposiciones.</li>
            </ul>

            <h3>Auxiliar Operativo - DHL, Protec and Grade, Kilómetro 1 vía Rionegro - El Carmen</h3>
            <p>Junio 2023 - Noviembre 2023</p>
            <ul>
                <li>Realización de funciones como picking en Flow rap y packing en bodega, cargue y descargue de mercancía.</li>
                <li>Seguimiento a la recepción y despacho de la mercancía.</li>
                <li>Control y garantía de los inventarios físicos de la mercancía.</li>
                <li>Supervisión de las condiciones y manejo de almacenamiento, líder de cuadrilla, movimiento en patios, organización y decoración de bodega, manejo de sistema (ardity y computador).</li>
            </ul>

            <h3>Bombero - Islero, Los Cristales, La Ceja</h3>
            <p>Febrero 2024 - Diciembre 2024</p>
            <ul>
                <li>Tanqueo de vehículos, vales y créditos de empresas.</li>
                <li>Contabilidad y manejo de dinero, descargue de gasolina, medidor y calidad de la misma.</li>
                <li>Mantenimiento y apoyo en la labor de mantenimiento, apoyo en otras islas y venta de aceites.</li>
            </ul>
        </div>

        <div class="section education" id="educacion">
            <h2>Información Académica</h2>
            <p><strong>Bachiller Académico</strong> - Monseñor Alfonso Uribe Jaramillo, Diciembre 2019</p>
            <p><strong>Tecnología</strong> - Desarrollo de Software</p>
            <p><strong>Diplomado</strong> - Gestión del Talento Humano</p>
            <p><strong>Diplomado</strong> - Logística</p>
            <p><strong>Complementario</strong> - Administración de Recursos del Talento Humano</p>
        </div>

        <div class="section references" id="referencias">
            <h2>Referencias Personales</h2>
            <p><strong>María Isabel Bedoya Ríos</strong><br>Secretaria de Admisiones y Servicio, Wompi SAS<br><i class="fas fa-phone"></i> 315-839-7691</p>
            <p><strong>Nelson Alexander Bedoya</strong><br>Analista Investigación y Laboratorio, Leonisa<br><i class="fas fa-phone"></i> 320-676-0694</p>
        </div>
    </div>
    <script>
        
        document.querySelector('.hamburger').addEventListener('click', () => {
            document.querySelector('.nav-links').classList.toggle('active');
        });
    </script>
</body>
</html>
