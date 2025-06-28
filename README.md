📚 Proyectos de HTML y CSS
Este repositorio contiene varios proyectos simples desarrollados en HTML y CSS como parte de una serie de prácticas diarias. Cada día se trabajó un tema distinto enfocado en componentes y estructuras clave del desarrollo web.

🗓 Día 1 - "Hola Mundo" en HTML
🧾 Descripción
Este es un proyecto básico que muestra cómo iniciar una página web con HTML, utilizando un encabezado principal.

💻 Código Destacado
html
Copiar
Editar
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Hola Mundo</title>
</head>
<body>
    <h1>Hola Mundo!!!</h1>
</body>
</html>
🗓 Día 2 - Formulario de Registro
🧾 Descripción
Página web con un formulario para registrar información personal. Incluye nombre, apellido, género, correo, población y una descripción personal, con validación básica.

📐 Estructura del Código
🧠 Encabezado (<head>)
<!DOCTYPE html>: Especifica HTML5.

<html lang="es">: Define el idioma.

<meta charset="UTF-8">: Soporte para caracteres especiales.

<meta name="viewport">: Responsive design.

<title>: Título del navegador.

🧍‍♂️ Cuerpo (<body>)
<h1> Título principal: Formulario de Registro

Campos:

Nombre / Apellido: Inputs de texto.

Sexo: Radio buttons.

Correo electrónico: Validación de formato.

Población: Menú desplegable.

Descripción personal: Textarea.

Términos: Casilla de verificación.

🗓 Día 3 - Maqueta Prime Video & Twitch
🌐 Descripción del Proyecto
Diseño visual que simula plataformas como Prime Video o Twitch Prime, con recursos gráficos y estilos personalizados.

🔧 Componentes
Logo central.

Títulos/subtítulos llamativos.

Imagen de fondo.

Ícono de búsqueda.

Botón de login.

Texto explicativo.

📁 Estructura de Archivos
pgsql
Copiar
Editar
📁 Dia3/
├── index.html
├── style.css
├── Fonts/
│   ├── Amazon Ember Bold.ttf
│   └── Amazon Ember Light.ttf
├── Images/
│   ├── FondoTwitch.png
│   ├── LogoPrimeE2.png
│   └── Icon awesome-search.png
🧱 HTML Ejemplo
html
Copiar
Editar
<h2 class="Title1">Holaaaaaaa</h2>
<img class="LogoPrime" src="./LogoPrimeE2.png" alt="Logo principal">

<div class="Login"><h1>Login</h1></div>
<div class="Sub_text">
  <h1>Enjoy Amazon Prime Video and Twitch Prime...</h1>
</div>
🗓 Día 4 - Gradientes con CSS
🧾 Descripción
Página web con diferentes tipos de fondos aplicados a elementos usando CSS Gradients.

🎨 Elementos Visuales
Título principal con colores llamativos.

Logo tipo Google con <span> de colores.

Secciones con:

Gradiente lineal.

Gradiente radial.

Gradiente cónico.

🗓 Día 5 - Tarjeta Metrolínea
🚍 Descripción del Proyecto
Representación gráfica de una tarjeta del sistema de transporte Metrolínea, usando HTML y CSS.

🧩 Elementos de la Tarjeta
Un rectángulo de fondo (.rectangle).

Logo oficial de Metrolínea.

Título principal con el nombre del sistema.

Subtítulo mostrando el saldo actual.

Todo organizado con clases CSS.

🗓 Día 6 - Formulario + Botones + BEM
🧪 Descripción
Ejercicio completo de formulario, botones y ejemplo práctico de la metodología BEM (Block Element Modifier) para nombrar clases CSS.

🧱 Estructura HTML
🔤 Títulos y Botones
html
Copiar
Editar
<h1>Wenas</h1>
<h1 id="tarde">Tardes</h1>
<h1>Compas</h1>

<button>No me des click</button>
<button disabled>No me des click</button>
📝 Formulario
html
Copiar
Editar
<form action="https://google.com">
  <label>Nombre</label>
  <input type="text" placeholder="John Doe" />

  <label>Apellido</label>
  <input type="password" />
</form>
🧱 Ejemplo BEM
html
Copiar
Editar
<div class="boton">
  <span class="boton__icono">...</span>
  <span class="boton__texto">Hacer click</span>
  <div class="boton boton--primario"></div>
</div>
