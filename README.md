# izabelaslamnea

Portfolio personal de proyectos de desarrollo web, programación y ciberseguridad.

# Portfolio de proyectos

¡Bienvenido/a a mi portfolio!

Este repositorio reúne proyectos en los que trabajo para desarrollar mis habilidades en tecnología, desarrollo web, programación y ciberseguridad.

## Proyectos

### 1. Vanguard Luxury Estates

Sitio web inmobiliario enfocado en propiedades de lujo, desarrollado con WordPress y Elementor.

**Características principales:**
- Diseño de una página web inmobiliaria.
- Catálogo de propiedades con fichas individuales.
- Filtros personalizados por ubicación, tipo de inmueble, precio y número de habitaciones.
- Interfaz adaptada a las necesidades de búsqueda de los usuarios.

**Tecnologías utilizadas:** WordPress, Elementor, HTML, CSS y JavaScript.

**Web del proyecto:** [vanguardluxuryestates.com](https://vanguardluxuryestates.com)

### 2. XAES — Cifrado y descifrado de archivos

Herramienta desarrollada en Python para cifrar y descifrar datos mediante AES-128 en modo CBC. El programa permite trabajar con archivos desde la terminal y utiliza PBKDF2 con SHA-256 para derivar la clave y el vector de inicialización a partir de una contraseña.

**Características principales:**
- Cifrado y descifrado de datos desde la línea de comandos.
- Uso de contraseñas para derivar las claves criptográficas.
- Generación aleatoria de una sal para cada cifrado.
- Lectura desde la entrada estándar y escritura en la salida estándar.

**Tecnologías utilizadas:** Python 3, AES-128-CBC, PBKDF2, SHA-256 y PyCryptodome.

**Código fuente y documentación:** [github.com/izabelaslamnea/xaes](https://github.com/izabelaslamnea/xaes)

**Memoria del proyecto:** disponible en el repositorio de XAES.

**Nota de seguridad:** este proyecto tiene fines educativos. AES-CBC no proporciona autenticación ni garantiza por sí solo la integridad de los datos.

### 3. Password Analyzer — Analizador de contraseñas

Herramienta desarrollada en Python para evaluar la fortaleza de contraseñas mediante criterios básicos de seguridad. Analiza su longitud, variedad de caracteres y presencia de patrones o contraseñas habituales, proporcionando una puntuación y recomendaciones de mejora.

**Características principales:**
- Evaluación de la longitud de las contraseñas.
- Comprobación de letras mayúsculas y minúsculas.
- Detección de números y símbolos especiales.
- Identificación de patrones y contraseñas comunes.
- Clasificación de la fortaleza: débil, media o fuerte.
- Puntuación de seguridad sobre 6.
- Introducción de contraseñas sin mostrarlas en pantalla.

**Tecnologías utilizadas:** Python 3, getpass y string.

**Código fuente y documentación:** [github.com/izabelaslamnea/password-analyzer](https://github.com/izabelaslamnea/password-analyzer)

**Nota de seguridad:** proyecto educativo basado en reglas sencillas. Su puntuación no garantiza que una contraseña sea segura.

### 4. Security Log Analyzer — Analizador de registros

Herramienta desarrollada en Python para analizar registros de acceso e identificar patrones de actividad potencialmente sospechosa, como posibles ataques de fuerza bruta y accesos exitosos precedidos de múltiples intentos fallidos.

**Características principales:**
- Análisis automático de registros de acceso.
- Identificación de inicios de sesión exitosos y fallidos.
- Agrupación de eventos por dirección IP.
- Detección de posibles ataques de fuerza bruta.
- Identificación de accesos exitosos después de varios fallos.
- Clasificación de alertas según el nivel de riesgo.
- Detección de registros inválidos.
- Generación de informes CSV con fecha, hora y detalles de las alertas.

**Tecnologías utilizadas:** Python 3, collections, datetime y csv.

**Código fuente y documentación:** [github.com/izabelaslamnea/log-analyzer](https://github.com/izabelaslamnea/log-analyzer)

**Nota de seguridad:** proyecto educativo basado en registros ficticios. Las alertas son indicadores de actividad sospechosa y no demuestran por sí solas la existencia de un ataque.

### 5. HONEYPOT — Sistema de detección y monitorización de amenazas

Herramienta desarrollada en Python que simula un panel de autenticación administrativo mediante un servidor TCP señuelo. Permite registrar conexiones, identificar direcciones IP y detectar posibles ataques de fuerza bruta a través de un panel gráfico de monitorización en tiempo real.

**Características principales:**
- Simulación de un servicio de autenticación mediante TCP.
- Registro de conexiones entrantes y nombres de usuario introducidos.
- Identificación y seguimiento de direcciones IP únicas.
- Detección de cinco o más intentos fallidos desde una misma IP en un intervalo de dos minutos.
- Generación de alertas de seguridad.
- Panel gráfico de monitorización en tiempo real.
- Visualización de conexiones, IP detectadas y alertas.
- Registro de eventos con fecha y hora.
- Exportación de informes de actividad en formato CSV.

**Tecnologías utilizadas:** Python 3, Tkinter, sockets TCP, threading, queue, csv y logging.

**Código fuente y documentación:** [github.com/izabelaslamnea/honeypot](https://github.com/izabelaslamnea/honeypot)

**Nota de seguridad:** proyecto educativo diseñado para entornos de laboratorio controlados. El servicio escucha exclusivamente en `127.0.0.1`, no implementa SSH real y no debe exponerse a redes públicas.

## Objetivos

- Desarrollar proyectos prácticos y documentar lo aprendido.
- Mejorar mis conocimientos de programación y desarrollo web.
- Ampliar mis habilidades en ciberseguridad.
- Construir un portfolio técnico para futuras oportunidades profesionales.

---

Este portfolio se actualizará a medida que incorpore nuevos proyectos.
