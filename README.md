<html>
<head>
    <base href="https://fake-host.com">
    <meta charset="UTF-8">
    <title>Clínica de Fertilidad - Inseminación Artificial</title>
    <style>
        :root {
            --primary: #2c5282;
            --secondary: #90cdf4;
            --accent: #4299e1;
            --light: #ebf8ff;
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--light);
            color: #2d3748;
        }

        .header {
            background: linear-gradient(135deg, var(--primary), var(--accent));
            color: white;
            padding: 3rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .header::after {
            content: '';
            position: absolute;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0) 70%);
            animation: rotate 20s linear infinite;
            top: -50%;
            left: -50%;
        }

        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .info-card {
            background: white;
            border-radius: 15px;
            padding: 2rem;
            margin: 1.5rem 0;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .info-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 4px;
            background: linear-gradient(90deg, var(--accent), var(--primary));
        }

        .info-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
        }

        .statistics {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .stat-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: var(--primary);
            margin: 1rem 0;
        }

        .testimonial-section {
            background: white;
            padding: 3rem;
            border-radius: 15px;
            margin: 3rem 0;
        }

        .testimonial {
            font-style: italic;
            color: #4a5568;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            line-height: 1.6;
        }

        .cta-section {
            text-align: center;
            padding: 4rem 0;
            background: linear-gradient(135deg, var(--primary), var(--accent));
            border-radius: 15px;
            color: white;
            margin: 3rem 0;
            position: relative;
            overflow: hidden;
        }

        .cta-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(circle at center, rgba(255,255,255,0.2) 0%, rgba(255,255,255,0) 70%);
            animation: pulse 3s ease-in-out infinite;
        }

        .cta-section h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .cta-section p {
            font-size: 1.2rem;
            line-height: 1.6;
            margin: 0.5rem 0;
            letter-spacing: 0.5px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        @keyframes pulse {
            0% { transform: scale(1); opacity: 0.5; }
            50% { transform: scale(1.05); opacity: 0.8; }
            100% { transform: scale(1); opacity: 0.5; }
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .method-card {
            background: white;
            border-radius: 15px;
            padding: 2rem;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }

        .method-card h3 {
            color: var(--primary);
            border-bottom: 2px solid var(--accent);
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }

        .method-card ul {
            list-style-type: none;
            padding: 0;
        }

        .method-card li {
            margin: 1rem 0;
            padding-left: 1.5rem;
            position: relative;
        }

        .method-card li::before {
            content: "•";
            color: var(--accent);
            font-weight: bold;
            position: absolute;
            left: 0;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

<header class="header">
    <h1>Inseminación Artificial</h1>
    <p>Haciendo realidad el sueño de formar una familia</p>
</header>

<div class="container">
    <div class="info-card">
        <h2>¿Qué es la Inseminación Artificial?</h2>
        <p>La inseminación artificial es un procedimiento de reproducción asistida que consiste en la colocación de espermatozoides previamente preparados en el útero de la mujer durante sus días fértiles, aumentando las probabilidades de embarazo.</p>
    </div>

    <div class="info-grid">
        <div class="method-card">
            <h3>Situaciones de Uso</h3>
            <ul>
                <li>Dificultades de fertilidad masculina leve o moderada</li>
                <li>Alteraciones del moco cervical</li>
                <li>Endometriosis leve</li>
                <li>Mujeres sin pareja masculina</li>
                <li>Parejas con infertilidad inexplicada</li>
            </ul>
        </div>

        <div class="method-card">
            <h3>Ventajas sobre otros métodos</h3>
            <ul>
                <li>Menos invasiva que la Fecundación In Vitro</li>
                <li>Menor costo de tratamiento</li>
                <li>Proceso más natural que otros tratamientos</li>
                <li>Recuperación más rápida</li>
                <li>Menor uso de medicamentos que otros tratamientos</li>
            </ul>
        </div>

        <div class="method-card">
            <h3>Comparación con otros métodos</h3>
            <ul>
                <li>Más efectiva que el coito programado en casos de subfertilidad</li>
                <li>Menos compleja que la fecundación in vitro</li>
                <li>Complementa la inducción a la ovulación para mejores resultados</li>
                <li>Puede ser el primer paso antes de considerar la FIV</li>
            </ul>
        </div>
    </div>

    <div class="statistics">
        <div class="stat-card">
            <div class="stat-number">95%</div>
            <p>Tasa de satisfacción de pacientes</p>
        </div>
        <div class="stat-card">
            <div class="stat-number">15+</div>
            <p>Años de experiencia</p>
        </div>
        <div class="stat-card">
            <div class="stat-number">5000+</div>
            <p>Familias formadas</p>
        </div>
    </div>

    <div class="testimonial-section">
        <h2>Lo que dicen nuestros pacientes</h2>
        <div class="testimonial">
            "El equipo médico nos hizo sentir seguros y acompañados durante todo el proceso. Hoy, gracias a su profesionalismo y dedicación, tenemos la familia que siempre soñamos."
        </div>
    </div>

    <div class="cta-section">
        <h2>Creadores</h2>
        <p>Lautaro Ynsaurralde • Facundo Troncoso • Jordan Ojeda • Lautaro Martin</p>
        <p style="font-style: italic; margin-top: 1.5rem;">Información obtenida de ChatGPT</p>
    </div>
</div>

<script>
document.querySelector('.cta-button').addEventListener('click', function() {
    window.location.href = "https://clinica-fertilidad.com/contacto";
});

// Animación de números estadísticos
const observerOptions = {
    threshold: 0.5,
    rootMargin: '0px'
};

const observer = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            const statNumber = entry.target.querySelector('.stat-number');
            const finalNumber = parseInt(statNumber.textContent);
            let currentNumber = 0;
            
            const interval = setInterval(() => {
                if (currentNumber >= finalNumber) {
                    clearInterval(interval);
                    return;
                }
                
                currentNumber += Math.ceil(finalNumber / 50);
                if (currentNumber > finalNumber) currentNumber = finalNumber;
                
                statNumber.textContent = currentNumber + (statNumber.textContent.includes('+') ? '+' : '%');
            }, 30);
            
            observer.unobserve(entry.target);
        }
    });
}, observerOptions);

document.querySelectorAll('.stat-card').forEach(card => {
    observer.observe(card);
});
</script>

</body>
</html>
