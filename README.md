<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Corteza - ¡La Pizza Más Épica!</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600;900&display=swap" rel="stylesheet">
    <style>
        body { 
            font-family: 'Poppins', sans-serif; 
            margin: 0; 
            padding: 0; 
            background: linear-gradient(135deg, #ff6b6b, #feca57, #48dbfb); 
            color: #333; 
            overflow-x: hidden;
        }
        header { 
            background: linear-gradient(45deg, #ff3838, #ff9f43); 
            color: white; 
            text-align: center; 
            padding: 40px 20px; 
            position: relative;
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }
        header h1 { 
            font-size: 3em; 
            font-weight: 900; 
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5); 
            margin: 0;
        }
        header p { 
            font-size: 1.2em; 
            font-weight: 300; 
            margin-top: 10px;
        }
        nav { 
            background: #e74c3c; 
            padding: 15px; 
            text-align: center; 
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        nav a { 
            color: white; 
            margin: 0 20px; 
            text-decoration: none; 
            font-weight: 600; 
            font-size: 1.1em; 
            transition: transform 0.3s;
        }
        nav a:hover { 
            transform: scale(1.1); 
            color: #feca57;
        }
        section { 
            padding: 30px; 
            margin: 20px auto; 
            max-width: 800px; 
            background: rgba(255,255,255,0.9); 
            border-radius: 15px; 
            box-shadow: 0 8px 16px rgba(0,0,0,0.1); 
            transition: transform 0.3s;
        }
        section:hover { transform: translateY(-5px); }
        section h2 { 
            color: #e74c3c; 
            font-size: 2.5em; 
            font-weight: 900; 
            text-align: center; 
            margin-bottom: 20px;
        }
        ul { 
            list-style: none; 
            padding: 0;
        }
        li { 
            background: #f8f9fa; 
            margin: 10px 0; 
            padding: 15px; 
            border-radius: 10px; 
            font-size: 1.1em; 
            display: flex; 
            align-items: center;
        }
        li strong { color: #e74c3c; }
        .img-placeholder { 
            width: 100px; 
            height: 100px; 
            background-size: cover; 
            background-position: center; 
            border-radius: 10px; 
            margin-right: 15px; 
            display: inline-block;
        }
        .didactico { 
            background: #ffeaa7; 
            padding: 20px; 
            border-radius: 10px; 
            margin-top: 20px;
        }
        .didactico h3 { color: #d63031; }
        footer { 
            background: #2d3436; 
            color: white; 
            text-align: center; 
            padding: 20px; 
            font-weight: 300;
        }
        .emoji { font-size: 1.5em; }
    </style>
</head>
<body>
    <header>
        <h1>🍕 La Corteza 🍕</h1>
        <p>¡La pizza más épica y deliciosa para jóvenes aventureros del sabor!</p>
    </header>
    <nav>
        <a href="#menu">Menú Épico</a>
        <a href="#nosotros">Nuestra Historia</a>
        <a href="#didactico">Aprende Sobre Pizza</a>
        <a href="#contacto">¡Contáctanos!</a>
    </nav>
    <section id="menu">
        <h2>Menú Épico <span class="emoji">🔥</span></h2>
        <ul>
            <li>
                <div class="img-placeholder" style="background-image: url('https://images.unsplash.com/photo-1513104890138-7c749659a591?ixlib=rb-4.0.3&auto=format&fit=crop&w=100&h=100&q=80');"></div>
                <div><strong>Pizza Margherita:</strong> Tomate fresco, mozzarella cremosa y albahaca aromática. ¡Clásica y perfecta! $12</div>
            </li>
            <li>
                <div class="img-placeholder" style="background-image: url('https://images.unsplash.com/photo-1628840042765-356cda07504e?ixlib=rb-4.0.3&auto=format&fit=crop&w=100&h=100&q=80');"></div>
                <div><strong>Pizza Pepperoni:</strong> Con pepperoni crujiente y queso derretido. ¡Para los amantes del picante! $14</div>
            </li>
            <li>
                <div class="img-placeholder" style="background-image: url('https://images.unsplash.com/photo-1571066811602-716837d681de?ixlib=rb-4.0.3&auto=format&fit=crop&w=100&h=100&q=80');"></div>
                <div><strong>Pizza Vegetariana:</strong> Llena de verduras frescas como pimientos, champiñones y cebolla. ¡Sana y sabrosa! $13</div>
            </li>
            <li>
                <div class="img-placeholder" style="background-image: url('https://images.unsplash.com/photo-1574071318508-1cdbab80d002?ixlib=rb-4.0.3&auto=format&fit=crop&w=100&h=100&q=80');"></div>
                <div><strong>Pizza Cuatro Quesos:</strong> Una explosión de quesos: mozzarella, gorgonzola, parmesano y provolone. ¡Para los queseros! $15</div>
            </li>
        </ul>
    </section>
    <section id="nosotros">
        <h2>Nuestra Historia <span class="emoji">📖</span></h2>
        <p>¡Hola, pizza lovers! En La Corteza, somos un equipo de jóvenes apasionados por la pizza. Usamos ingredientes frescos de granjas locales y horneamos cada pizza con amor en hornos de leña. ¡Ven a probar la magia y únete a nuestra comunidad de fans!</p>
        <p>¿Sabías que la pizza nació en Italia hace siglos? ¡Nosotros la llevamos al siguiente nivel con toques modernos y divertidos!</p>
    </section>
    <section id="didactico">
        <h2>Aprende Sobre Pizza <span class="emoji">🎓</span></h2>
        <div class="didactico">
            <h3>¿Cómo se hace una pizza perfecta?</h3>
            <p>¡Paso a paso, como un pro! Primero, amasa la masa con harina, agua, levadura y sal. Luego, agrega salsa de tomate, queso y toppings. Hornea a 250°C por 10-15 minutos. ¡Fácil y divertido!</p>
            <h3>Beneficios de la pizza</h3>
            <p>La pizza combina carbohidratos de la masa, proteínas del queso y vitaminas de las verduras. ¡Es equilibrada si eliges bien! Pero recuerda, ¡todo en moderación!</p>
            <h3>Trivia Pizza</h3>
            <p>¿Cuál es la pizza más vendida del mundo? ¡La Margherita! ¿Quieres saber más? ¡Pregúntanos en la pizzería!</p>
        </div>
    </section>
    <section id="contacto">
        <h2>¡Contáctanos! <span class="emoji">📞</span></h2>
        <p><strong>Dirección:</strong> Calle Ficticia 123, Ciudad Imaginaria</p>
        <p><strong>Teléfono:</strong> (123) 456-7890</p>
        <p><strong>Email:</strong> info@lacorteza.com</p>
        <p><strong>Horarios:</strong> Lunes a Domingo, 12:00 PM - 11:00 PM</p>
        <p>¡Síguenos en redes sociales para tips de pizza y ofertas épicas! #LaCorteza</p>
    </section>
    <footer>
        <p>&copy; 2023 La Corteza. ¡Hecha con ❤️ para jóvenes hambrientos de pizza!</p>
    </footer>
</body>
</html>
