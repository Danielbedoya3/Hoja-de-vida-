<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoja de Vida - Daniel Bedoya Ríos</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
       
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f0f2f5;
            color: #333;
            padding-top: 60px; 
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            padding: 30px;
        }

        header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 2px solid #2c3e50;
        }

        header h1 {
            font-size: 28px;
            margin: 10px 0 5px;
            color: #2c3e50;
        }

        header p {
            font-size: 16px;
            color: #7f8c8d;
            margin: 5px 0;
        }

        .section {
            margin: 20px 0;
        }

        .section h2 {
            font-size: 22px;
            color: #2c3e50;
            border-left: 4px solid #3498db;
            padding-left: 10px;
            margin-bottom: 15px;
        }

        .section p, .section li {
            font-size: 16px;
            line-height: 1.6;
            color: #34495e;
        }

        .experience h3 {
            font-size: 18px;
            color: #2c3e50;
            margin-bottom: 5px;
        }

        .experience p {
            font-style: italic;
            color: #7f8c8d;
            margin: 5px 0;
        }

        .experience ul {
            list-style-type: disc;
            padding-left: 20px;
            margin-top: 10px;
        }

        .experience li {
            margin-bottom: 10px;
        }

        .contact-info p {
            display: flex;
            align-items: center;
            gap: 10px;
            margin: 8px 0;
        }

        .contact-info i {
            color: #3498db;
        }

        .education p, .references p {
            margin: 8px 0;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #3498db;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
            margin: 0 auto 15px;
            display: block;
        }

    
        .navbar {
            background: #2c3e50;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .navbar .nav-container {
            max-width: 900px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
        }

        .navbar .brand {
            color: #fff;
            font-size: 20px;
            font-weight: bold;
            text-decoration: none;
        }

        .nav-links {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        .nav-links li {
            margin-left: 20px;
        }

        .nav-links a {
            color: #fff;
            text-decoration: none;
            font-size: 16px;
            padding: 10px;
            transition: background 0.3s;
        }

        .nav-links a:hover {
            background: #3498db;
            border-radius: 5px;
        }

        .hamburger {
            display: none;
            font-size: 24px;
            color: #fff;
            cursor: pointer;
        }

        @media print {
            body {
                background: #fff;
                padding-top: 0;
            }
            .container {
                box-shadow: none;
                padding: 0;
            }
            .section h2 {
                border-left: none;
                padding-left: 0;
            }
            .profile-img {
                border: 2px solid #2c3e50;
                box-shadow: none;
            }
            .navbar {
                display: none; 
            }
        }

        @media (max-width: 600px) {
            .container {
                padding: 15px;
            }
            header h1 {
                font-size: 24px;
            }
            .section h2 {
                font-size: 20px;
            }
            .profile-img {
                width: 100px;
                height: 100px;
            }
            .hamburger {
                display: block;
            }
            .nav-links {
                display: none;
                flex-direction: column;
                position: absolute;
                top: 50px;
                left: 0;
                width: 100%;
                background: #2c3e50;
                padding: 10px 0;
            }
            .nav-links.active {
                display: flex;
            }
            .nav-links li {
                margin: 10px 0;
                text-align: center;
            }
            .nav-links a {
                display: block;
                padding: 15px;
            }
        }
    </style>
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
