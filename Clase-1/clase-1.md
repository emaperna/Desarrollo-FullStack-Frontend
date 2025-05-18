# 📘 Clase 1: Introducción a la Web y HTML Básico

> Curso de Desarrollo FullStack - Frontend 2025  
> Universidad Popular Gral. Levalle, Córdoba  
> [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-1.php)

---

## 🧠 ¿Qué es la programación?

La programación es el proceso de dar instrucciones a una computadora para que realice tareas específicas. Es como escribir un conjunto de pasos que la computadora debe seguir para lograr un objetivo.

```python
def saludar():
    print("¡Hola mundo!")

saludar()
```

### ✨ ¿Qué se puede hacer con la programación?

- Crear software: desde aplicaciones móviles hasta sistemas operativos.
- Desarrollar sitios web interactivos y dinámicos.
- Diseñar videojuegos.
- Analizar grandes cantidades de datos.
- Automatizar tareas repetitivas y tediosas.

La programación no se trata solo de escribir código, sino de usar la lógica y la creatividad para resolver problemas.

### 🛠 ¿Qué se necesita para programar?

- **Computadora**
- **Editor de código**
- **Lógica**
- **Aprendizaje constante**

Hay muchos lenguajes y herramientas gratuitas disponibles, como Python, Java o JavaScript.

### 📈 ¿Es difícil aprender a programar?

- **Principiante**: Empieza con lo básico.
- **Intermedio**: Practica regularmente.
- **Avanzado**: Domina conceptos complejos.

Con paciencia y práctica, cualquiera puede aprender. Lo importante es empezar con conceptos sencillos e ir avanzando gradualmente.

### 🎯 ¿Por qué es importante aprender a programar?

- Desarrolla la creatividad.
- Mejora el pensamiento lógico.
- Ayuda a resolver problemas.
- Amplía oportunidades laborales.

---

## 👨‍💻 ¿Qué es un programador?

Un programador es un profesional que se dedica a crear y optimizar software informático. Utiliza lenguajes de programación, que son similares a idiomas, para comunicarse con la computadora y escribir instrucciones que generan nuevos programas.

### 🧩 Tipos de programadores

#### Por Especialidad

- **Desarrollador web**: Crea y mantiene sitios web y aplicaciones web.
- **Desarrollador móvil**: Crea aplicaciones para dispositivos móviles.
- **Desarrollador de software**: Crea software para diferentes plataformas.
- **Desarrollador de videojuegos**: Crea videojuegos para diferentes plataformas.
- **Ingeniero de datos**: Trabaja con grandes conjuntos de datos.
- **Científico de datos**: Analiza datos y desarrolla modelos predictivos.
- **Ingeniero de IA**: Desarrolla sistemas de aprendizaje autónomo.

#### Por Lenguaje de Programación

- **Desarrollador Java**: Especializado en aplicaciones empresariales.
- **Desarrollador Python**: Análisis de datos, IA, web y desarrollo general.
- **Desarrollador C++**: Sistemas de bajo nivel, juegos y alto rendimiento.
- **Desarrollador JavaScript**: Aplicaciones web, móviles y de servidor.
- **Desarrollador PHP**: Aplicaciones web y gestión de contenidos.

#### Por Experiencia

- **Junior**: Poca experiencia, generalmente recién graduado.
- **Semi Senior**: Conocimientos medios del rubro y programación.
- **Senior**: Mucha experiencia y conocimiento en su especialización.
- **Lead**: Lidera equipos y toma decisiones técnicas.

#### Por Rol

- **Desarrollador**: Se encarga de escribir el código.
- **QA**: Se encarga de probar el software.
- **DevOps**: Automatiza implementación y mantenimiento.
- **Gerente de proyecto**: Planifica y gestiona el desarrollo.
- **Arquitecto de software**: Diseña la estructura del sistema.

---

## 🌐 Historia y Evolución de la Web

La web ha experimentado una notable evolución desde sus inicios.

### 🕸️ Web 1.0

- Fue la primera versión de Internet, desarrollada en los años 90.
- Conocida como "World Wide Web".
- Características principales:
  - Era estática y de solo lectura.
  - Contenidos unidireccionales y estáticos.
  - Los sitios almacenaban contenidos directamente en archivos.
  - Formularios vinculados a correo electrónico.

### 🌍 Web 2.0

- Permitió la interacción y colaboración entre usuarios.
- Incluyó redes sociales, blogs y wikis.
- Los usuarios se convirtieron en "prosumidores".
- Fomenta la creación y distribución colaborativa de contenido.

### 🌐 Web 3.0

- Se centra en la inteligencia artificial.
- Implementa web semántica.
- Evoluciona hacia espacios 3D.
- Los usuarios son dueños de sus datos.
- Control sobre cómo compartir la información.
- Utiliza tecnologías como:
  - Blockchain
  - Criptomonedas
  - Metaversos

---

## 🧱 Frontend vs Backend

El desarrollo web se divide en dos áreas principales que trabajan juntas para crear una aplicación web funcional:

### 🎨 Frontend (Lado del Cliente)

Es todo lo que el usuario ve e interactúa directamente en el navegador.

**Tecnologías clave:**

- **HTML**: Estructura el contenido.
- **CSS**: Da estilo y diseño visual.
- **JavaScript**: Añade interactividad y dinamismo.

**Ejemplo:** Un botón en el que haces clic, un formulario que rellenas, la animación de un menú.

```html
<!-- Ejemplo HTML -->
<button class="btn-primary">Haz Clic</button>
```

```css
/* Ejemplo CSS */
.btn-primary {
  background-color: blue;
  color: white;
  padding: 10px;
}
```

### ⚙️ Backend (Lado del Servidor)

Es la lógica "detrás de cámaras" que procesa datos, gestiona usuarios y se conecta a bases de datos.

**Tecnologías clave (ejemplos):**

- **PHP**
- **Python (Django, Flask)**
- **Node.js (JavaScript)**
- **Bases de Datos (SQL, NoSQL)**

**Ejemplo:** Cuando te registras en un sitio, el backend guarda tu información en la base de datos. Cuando inicias sesión, verifica tus credenciales.

```
<?php
// Ejemplo (conceptual) Backend con PHP
if ($_SERVER['REQUEST_METHOD'] === 'POST' && isset($_POST['register'])) {
  $username = $_POST['username'] ?? '';
  $password = $_POST['password'] ?? '';

  // ... Lógica para validar y guardar en la base de datos ...
  // $hashedPassword = password_hash($password, PASSWORD_DEFAULT);
  // Guardar $username y $hashedPassword en la BD
  echo "Usuario registrado exitosamente.";
  // header('Location: login.php'); // Redirigir después del registro
  exit;
}
?>
```

---

## 🎩 Tecnologías que aprenderás en este curso

Este programa te permitirá dominar las tecnologías esenciales para convertirte en desarrollador Full Stack:

### ⚙️ HTML 5: 

- Estructura y organización de contenidos web mediante etiquetas semánticas.

### ⚙️ CSS 3:

- Diseño visual, maquetación y estilos para crear interfaces atractivas y responsivas.

### ⚙️ JavaScript:

- Interactividad en el cliente, manipulación del DOM y funcionalidades dinámicas.

### ⚙️ PHP:

- Programación del lado del servidor para gestionar datos y lógica de negocio.

### ⚙️ MySQL:

- Base de datos relacional para almacenar y consultar información de manera estructurada.

---

## 🛠️ Entorno de Trabajo

Herramientas Básicas: Editores de Código, Navegadores y el Inspector de Elementos

**Editores de Código** Visual Studio Code: versátil y con extensiones que facilitan la programación.

- [🔗 Link Descarga](https://code.visualstudio.com/)


**Navegadores Web** Chrome, Firefox, Safari, Edge, Opera. Recomiendo ¿Puedo Usarlo? para consultar compatibilidad.

- [🔗 Link Consulta](https://caniuse.com/)

**Inspector de Elementos** Herramienta integrada (tecla F12) para depurar HTML/CSS y experimentar en tiempo real.

---

## 📄 Introducción a HTML Básico

### ¿Qué es HTML?

- HTML (HyperText Markup Language) es el lenguaje estándar para crear y estructurar páginas web a través de etiquetas y atributos.

### Principales etiquetas HTML

- Las etiquetas HTML son los bloques fundamentales para construir páginas web. Cada tipo cumple una función específica en la estructura de tu documento.

### Encabezados (6)

- `<h1>` – Encabezado principal
- `<h2>` – Segundo nivel
- `<h3>` – Tercer nivel
… hasta `<h6>` – Define la jerarquía y organización del contenido en la página.


### Texto y contenido (9+)

- `<p>` – Párrafo
- `<a href="#">` – Enlace
- `<img src="…" alt="…">` – Imagen
- `<strong>` - Negrita semántica
- `<em>` – Cursiva semántica
- `<br>` – Salto de línea
- `<hr>` – Línea horizontal
- `<span>` – Contenedor en línea
- `<div>` – Contenedor en bloque

- Elementos fundamentales para mostrar y organizar tu contenido.


### Listas (3)

- `<ul>` – Lista desordenada
- `<ol>` – Lista ordenada
- `<li>` – Elemento de lista

- Organiza información en formato de listas numeradas o con viñetas.


### Tablas (4)

- `<table>` – Tabla
- `<tr>` – Fila de tabla
- `<td>` – Celda
- `<th>` – Encabezado de celda

- Muestra datos tabulares organizados en filas y columnas.


### Formularios e Interacción (5+)

- `<form>` – Formulario
- `<input type="...">` – Campos de entrada
- `<button>` – Botón
- `<select> y <option>` – Menú desplegable
- `<textarea>` – Área de texto

- Permite a los usuarios interactuar y enviar información a través de la web.


### Multimedia (4)

- `<audio>` – Audio
- `<video>` – Video
- `<source>` – Fuente multimedia
- `<iframe>` – Contenido externo

- Incorpora contenido multimedia como audio, video y elementos externos.


### Otros elementos importantes (4)

- `<script>` – JavaScript
- `<link>` – Hojas de estilo o iconos
- `<style>` – CSS interno
- `<noscript>` – Contenido sin JS

- Elementos para incorporar scripts, estilos y comportamientos a tu página.

---


## 📝 Actividades

**Actividad 1:** Mi primera página web

- Crear un archivo nombre_del_alumno.html.
- Escribir la estructura básica de un documento HTML.
- Crear un encabezado saludando.
- Crear un encabezado de segundo nivel con tu nombre y apellido.
- Crear un párrafo con el texto: "Esta es mi primera página web".
- Abrirlo en el navegador.

**Actividad 2:** Descargar VS Code

- Visitar el sitio oficial de Visual Studio Code.
- Descargar la versión estable adecuada para tu sistema operativo.
- Instalar el editor siguiendo los pasos del asistente de instalación.
- Explorar la interfaz del editor:
  - Barra lateral izquierda (explorador de archivos, búsqueda, extensiones)
  - Editor central
  - Terminal integrada (Ctrl+`)
- Abrir la página HTML creada en la Actividad 1 usando VS Code.


- [🔗 Link Descarga](https://code.visualstudio.com/)


**Actividad 3:** Descargar Live Server

- Extensión que recarga automáticamente la página al guardar cambios en HTML, CSS o JS.

  - Abrir VS Code y hacer clic en el icono de extensiones en la barra lateral izquierda.
  - Buscar "Live Server" en el marketplace de extensiones.
  - Instalar la extensión desarrollada por Ritwick Dey.
  - Reiniciar VS Code si es necesario.
  - Para usar Live Server, haz clic derecho en un archivo HTML y selecciona "Abrir con Live Server".


## 📚 Recursos Adicionales

- [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-1.php)