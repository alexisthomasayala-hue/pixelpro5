🎮 PixelPro - Proyecto Web Dinámico (PHP, SSI, SSR y Seguridad)

📝 Descripción del Proyecto

Este proyecto corresponde a la asignatura Programación Web y documenta la evolución del sitio web PixelPro🎮 desde una maquetación estática en HTML hasta una aplicación web dinámica en PHP.

Se implementó una arquitectura modular mediante Server Side Includes (SSI) (header.php, nav.php, footer.php), renderizado de títulos dinámicos del lado del servidor (SSR) y procesamiento de datos con formularios POST y GET que incluyen sanitización estricta (htmlspecialchars(), trim(), filter_input()) para prevenir vulnerabilidades de Scripting Entre Sitios (XSS).

🛠️ Tecnologías Utilizadas

PHP 8.x (Lógica de servidor, SSI, SSR, sanitización y persistencia)

HTML5 & CSS3 (todo.css)

JavaScript (todo.js)

XAMPP / Laragon (Servidor web local Apache)

Git & GitHub (Control de versiones)

📁 Estructura del Directorio (/clase5)

El desarrollo actualizado con procesamiento de formularios y sanitización se encuentra dentro de la carpeta clase5:

pixelpro/
├── README.md
├── clase5/
│   ├── config/
│   │   └── env.php              # Configuración de variables globales
│   ├── includes/
│   │   ├── footer.php           # Cierre de body y scripts JS
│   │   ├── header.php           # Head y $titulo_pagina dinámico
│   │   └── nav.php              # Navegación y formulario GET de búsqueda
│   ├── blog.php
│   ├── configuracion.php
│   ├── contactos.php
│   ├── curso.php
│   ├── deseas unirte.php
│   ├── formulario.php           # Formulario POST con validación y persistencia
│   ├── generos.php
│   ├── index.php                # Inicio (Sobre Nosotros)
│   ├── logo.php
│   ├── noticias.php             # Resultados de búsqueda GET
│   ├── opiniones.php
│   ├── perfil jugador.php
│   ├── precios.php
│   ├── preguntas.php
│   ├── ranking.php
│   ├── ubicacion sucursal.php
│   ├── todo.css
│   └── todo.js
├── Captura.PNG
├── tp.1.PNG
├── tp1.PNG
└── tpn1.PNG


🚀 Instalación y Ejecución Local

Clonar el repositorio en la carpeta raíz del servidor local (htdocs en XAMPP o www en Laragon):

git clone https://github.com/alexisthomasayala-hue/Pixelpro.git


Iniciar el módulo Apache desde el panel de XAMPP / Laragon.

Abrir el navegador e ingresar a la ruta local:

http://localhost/Pixelpro/index.php
