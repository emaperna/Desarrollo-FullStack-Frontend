# 📘 Clase 2 – Estructura HTML, Enlaces y Formularios

> Curso de Desarrollo FullStack - Frontend 2025  
> Universidad Popular Gral. Levalle, Córdoba  
> [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-2.php)

---

## 🧠 Objetivo de la clase

- Ampliar los conocimientos de HTML mediante la creación de formularios y listas. A través de ejercicios guiados, se busca que los estudiantes adquieran confianza en el uso de estas etiquetas y desarrollen una estructura HTML más completa.

---

## ✨ ¿Cómo funcionan las etiquetas HTML?

### Estructura de las etiquetas

- Las etiquetas HTML son los bloques básicos que definen la estructura y el contenido de una página web. La mayoría de etiquetas tienen una estructura de apertura y cierre que envuelve el contenido.

#### Etiqueta de apertura:

- Indica dónde comienza el enlace.

```html
<a href="https://ejemplo.com">
```

#### Etiqueta de cierre:

- Indica dónde termina el enlace.

```html
</a>
```

#### Atributo:

- Define la URL de destino del enlace.

```html
href="https://ejemplo.com"
```

#### Ejemplo completo de estructura:

```html
<a href="https://ejemplo.com">
  Visitar ejemplo
</a>
```

**Etiqueta de apertura**

**Contenido**

**Etiqueta de cierre**

- Algunas etiquetas como `<img>`, `<br>` o `<input>` son auto-cerradas y no necesitan etiqueta de cierre:

```html
<img src="imagen.jpg">
```

o en formato XHTML:

```html
<img src="imagen.jpg"/>
```

### Enlaces (`<a>`)

- Los enlaces permiten conectar diferentes páginas o recursos en la web. Se crean con la etiqueta `<a>` y el atributo `href` para indicar la dirección de destino.

#### Tipos de enlaces:

- **Enlace interno:**

  ```html
  <a href="pagina2.html">Ir a Página 2</a>
  ```

- **Enlace externo:**

  ```html
  <a href="https://www.google.com" target="_blank">Google</a>
  ```

- **Enlace a correo:**

  ```html
  <a href="mailto:correo@ejemplo.com">Enviar correo</a>
  ```

---

## 📈 ¿Qué son los formularios y listas?

### Formularios

- Los formularios son elementos que permiten al usuario introducir y enviar datos a través de una página web. Son esenciales para crear sistemas de contacto, registro, búsquedas, encuestas, etc.

#### Estructura básica de un formulario:

```html
<form action="/enviar" method="post">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre">
  <button type="submit">Enviar</button>
</form>
```

### Listas

- Las listas se utilizan para organizar elementos relacionados. Pueden ser ordenadas (con números) o desordenadas (con viñetas).

#### Lista desordenada (`<ul>`)

- Cada elemento aparece con una viñeta o bullet point.

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>
```

#### Lista ordenada (`<ol>`)

- Cada elemento aparece con un número o letra secuencial.

```html
<ol>
  <li>Paso 1</li>
  <li>Paso 2</li>
</ol>
```

#### Elemento de lista (`<li>`)

- Se usa dentro de `<ul>` o `<ol>` para cada ítem.

```html
<ul>
  <li>Elemento</li>
</ul>
```

---

## 📝 Actividades

### Actividad 1: Formulario de contacto

**Objetivo:** Familiarizarse con la estructura y componentes de un formulario en HTML.

1. Crear un archivo llamado `formulario_contacto.html`.
2. Dentro del `<body>`, crear un formulario con los siguientes campos:
   - Nombre (`type="text"`)
   - Correo electrónico (`type="email"`)
   - Mensaje (`<textarea>`)
   - Un botón para enviar
3. Agregar etiquetas `<label>` asociadas a cada campo.
4. Probar el formulario en el navegador.

**Bonus:** Usar el atributo `required` para validar que los campos no estén vacíos.

### Actividad 2: Listas desordenadas y ordenadas

**Objetivo:** Entender cómo organizar información de manera clara y ordenada utilizando listas.

1. Crear un archivo llamado `listas.html`.
2. Crear:
   - Una lista desordenada con al menos 5 cosas favoritas (películas, comidas, etc.).
   - Una lista ordenada con los pasos para hacer una receta.

**Bonus:** Agregar un título usando `<h2>` encima de cada sección.

## 📚 Recursos Adicionales

- [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-2.php)