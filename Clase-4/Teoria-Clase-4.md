
# 📚 Clase 4 – Semántica HTML

## 🎯 Etiquetas semánticas

- Las etiquetas semánticas en HTML5 ayudan a dar significado al contenido de la página, facilitando la comprensión tanto para los desarrolladores como para los navegadores y motores de búsqueda.


- `<header>` : Encabezado principal de la página o sección.
- `<nav>` : Menú de navegación.
- `<main>` : Contenido principal del documento.
- `<section>` : Sección temática del contenido.
- `<article>` : Contenido independiente y auto-contenido.
- `<aside>` : Información complementaria o lateral.
- `<footer>` : Pie de página.
- `<figure>` : Contenedor para ilustraciones, diagramas, fotos u otro contenido independiente.
- `<figcaption>` : Descripción o leyenda para el contenido de un elemento `<figure>`.
- `<time>` : Descripción o leyenda para el contenido de un elemento 

#### Ejemplo visual de estructura semántica:

```html
<header>Encabezado</header>
<nav>Menú</nav>
<main>
  <section>
    <article>Artículo independiente</article>
  </section>
  <aside>Contenido complementario</aside>
</main>
<footer>Pie de página</footer>
```

#### Ejemplo de estructura semántica (código):

```html
<header>Encabezado</header>
<nav>Menú</nav>
<main>
  <section>Sección principal</section>
  <aside>Publicidad</aside>
</main>
<footer>Pie de página</footer>
```

---

## ⌨️ Tipos de Inputs en HTML

- HTML ofrece una amplia variedad de tipos de inputs que permiten capturar diferentes tipos de datos del usuario. Cada tipo tiene características específicas y se adapta a diferentes necesidades.

### 📄 Inputs de texto:

- `text`: Campo de texto básico
  ```html
  <input type="text">
  ```

- `password`: Campo para contraseñas
  `<input type="password">`

- `email`: Campo para correos electrónicos
  `<input type="email">`

- `url`: Campo para URLs
  `<input type="url">`

- `tel`: Campo para números telefónicos
  `<input type="tel">`

- `search`: Campo de búsqueda
  `<input type="search">`


### 📆 Inputs numéricos y de fecha/Hora:

- `number`: Campo para números
  `<input type="number" min="1" max="100">`

- `range`: Selector de rango
  `<input type="range" min="0" max="100">`

- `date`: Campo para fechas
  `<input type="date">`

- `time`: Campo para hora
  `<input type="time">`

- `datetime-local`: Fecha y hora local
  `<input type="datetime-local">`

- `month`: Selector de mes
  `<input type="month">`

- `week`: Selector de semana
  `<input type="week">`


### ☑️ Inputs de selección:

- `checkbox`: Casilla de verificación
  `<input type="checkbox">`

- `radio`: Botones de opción
  `<input type="radio" name="grupo">`

- `color`: Selector de color
  `<input type="color">`

- `file`: Selector de archivos
  `<input type="file">`

### 🔘 Inputs de Botones:

- `submit`: Botón de envío
  `<input type="submit">`

- `reset`: Botón de reinicio
  `<input type="reset">`

- `button`: Botón genérico
  `<input type="button">`


### 🛠️  Inputs Especiales:

- `hidden`: Campo oculto (no visible), Este campo no es visible pero está presente en el formulario
  `<input type="hidden">`

- `image`: Botón de imagen
  `<input type="image" src="imagen.png">`

---

## 🛠️ Atributos importantes para inputs:

-- Los inputs en HTML pueden usar diversos atributos para mejorar la funcionalidad y experiencia del usuario. A continuación verás cada atributo con su explicación y ejemplo práctico:


- `required`: Campo obligatorio, Hace que el campo sea obligatorio para enviar el formulario. Si está vacío, el navegador mostrará un mensaje de error.
  `<input type="text" required>` Intenta enviar sin llenar este campo

- `placeholder`: Texto de ayuda, Muestra un texto de ayuda dentro del campo que desaparece cuando el usuario empieza a escribir.
`<input type="email" placeholder="ejemplo@correo.com">`

- `min` / `max`: Valores límite, Define valores mínimo y máximo para campos numéricos y de fecha. El navegador validará automáticamente.
  `<input type="number" min="18" max="65">` (Prueba ingresar un número fuera del rango)

- `step`: Incremento, Especifica el incremento en campos numéricos y de rango. Útil para precios, porcentajes, etc.
  `<input type="number" step="0.50">` (Usa las flechas del campo para ver el incremento)

- `pattern`: Validación personalizada, Define un patrón de validación usando expresiones regulares para formatos específicos.
  `<input type="text" pattern="[0-9]{5}">` (Solo acepta exactamente 5 números)

- `disabled`: Campo desactivado, Desactiva el campo, impidiendo la interacción del usuario. El valor no se envía en el formulario.
  `<input type="text" disabled>` (Este campo no es interactivo)

- `readonly`: Solo lectura, Hace el campo de solo lectura, visible pero no editable. A diferencia de disabled, el valor sí se envía.
  `<input type="text" readonly>` (Puedes seleccionar el texto pero no editarlo)

- `multiple`: Selección múltiple, Permite seleccionar múltiples valores en campos de archivo o listas.
  `<input type="file" multiple>`  (Puedes seleccionar varios archivos a la vez)

- `autocomplete`
  ``

- `autofocus`
  ``



- `form`
  ``

- `list`
  ``

- `formnovalidate`
  ``

- `value`
  ``

- `maxlength`
  ``

- `size`
  ``


---

## 💡 Buenas Prácticas

- Usa el tipo adecuado según el dato.
- Aplica validaciones HTML y del lado del servidor.
- Mejora la experiencia con `placeholder`, `autofocus`, `autocomplete`.
- Piensa en la accesibilidad y dispositivos móviles.

---

## 📝 Actividades

### ✅ Actividad 1: Estructura semántica

Crear una página HTML con etiquetas como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`.

### ✅ Actividad 2: Proyecto "Mi Blog"

Construir un blog personal con estructura semántica, artículos, formulario de contacto, y navegación.

---

🔗 Ver contenido completo online: [Clase 4 – Semántica HTML](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-4.php)
