
# 📚 Clase 3 – Tablas, Imágenes y Semántica HTML

> Curso de Desarrollo FullStack - Frontend 2025  
> Universidad Popular Gral. Levalle, Córdoba  
> [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-3.php)

---

## 🎯 Objetivo de la clase

- 📡 Continuar ampliando los conocimientos de HTML mediante la creación de tablas, inserción de imágenes y uso de etiquetas semánticas. A través de ejercicios guiados, se busca que los estudiantes adquieran confianza en el uso de estas etiquetas y desarrollen una estructura HTML más completa.

---

## 🧩 Tablas

- 📰 Las tablas permiten mostrar datos de forma estructurada, en filas y columnas. Son útiles para mostrar comparativas, horarios, datos personales, etc.

### 🔹 Contenedor principal

- Define el inicio y fin de una tabla en el documento:

```html
<table>...</table>
```

### 🔹 Fila de tabla

- Agrupa celdas horizontalmente formando una fila:

```html
<tr>...</tr>
```

### 🔹 Celda de encabezado

- Define celdas de título para columnas o filas:

```html
<th>Nombre</th>
```

### 🔹 Celda de datos

- Contiene los datos individuales de la tabla:

```html
<td>Ana</td>
```

### 🧪 Ejemplo de tabla básica

```html
<table border="1">
  <tr>
    <th>Nombre</th>
    <th>Edad</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>22</td>
  </tr>
  <tr>
    <td>Juan</td>
    <td>30</td>
  </tr>
</table>
```

---

## 🖼️ Manejo de imágenes

- 🎆 Las imágenes se insertan en HTML con la etiqueta `<img>`. Es importante usar el atributo `alt` para describir la imagen por accesibilidad.

### 🧪 Ejemplo de imagen

```html
<img src="ruta/imagen.jpg" alt="Descripción de la imagen" width="300">
```

- `src`: Ruta de la imagen.
- `alt`: Texto alternativo descriptivo.
- `width`/`height`: Tamaño de la imagen (opcional).

### 💡 Curiosidad: Comportamiento de imágenes y párrafos

- ¿Has notado que cuando colocas un párrafo `<p>` debajo de una imagen, el texto siempre aparece debajo, pero si escribes texto directamente después de la imagen, se coloca al lado? Esto ocurre porque:

- Las imágenes `<img>` son elementos inline por defecto (`display: inline`).
- Los párrafos `<p>` son elementos block por defecto (`display: block`).

- Los elementos block siempre comienzan en una nueva línea y ocupan todo el ancho disponible, mientras que los elementos inline solo ocupan el espacio necesario para su contenido y no fuerzan saltos de línea.

---

## 📝 Actividades

### 🧠 Actividad 1: Tabla de contactos

**📚 Objetivo**: Practicar la creación y estructura básica de tablas en HTML.

1. 📰 Crear un archivo llamado `tabla_contactos.html`.
2. 🧾 Crear una tabla de contactos con cinco columnas:
   - Nombre
   - Apellido
   - Dirección
   - Correo electrónico
   - Teléfono
3. 🙋🏻‍♂️ Completar la tabla con datos de al menos 3 personas (pueden ser ficticios).
4. Usar las etiquetas `<th>` para los encabezados y `<td>` para los datos.

**💡 Bonus**: Añadir el atributo `border="1"` a la tabla.

---

### 🧠 Actividad 2: Imágenes y enlaces

**📚 Objetivo**: Practicar la inserción de imágenes y la creación de diversos tipos de enlaces.

1. 🖼️ Crear un archivo llamado `galeria.html`.
2. 🎑 Crear una galería simple con:
   - Al menos 3 imágenes (usar URLs de internet si no tienes imágenes propias).
   - Cada imagen debe tener un texto alternativo descriptivo.
   - Debajo de cada imagen, añadir un enlace que abra la imagen en una nueva pestaña.
3. 📇 Al final de la página, crear una sección de "Contacto" con:
   - Un enlace para enviar un correo electrónico.
   - Un enlace a una red social.
   - Un enlace interno que regrese al principio de la página (usar el atributo `id`).

**💡 Bonus**: Organizar las imágenes en una tabla para que queden en filas de 2 imágenes.

## 📚 Recursos Adicionales

- [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-2.php)