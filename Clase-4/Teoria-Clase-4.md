
# 📚 Clase 4 – Semántica HTML

> Curso de Desarrollo FullStack - Frontend 2025  
> Universidad Popular Gral. Levalle, Córdoba  
> [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-4.php)

---
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
  ```html
  <input type="password">
  ```

- `email`: Campo para correos electrónicos
  ```html
  <input type="email">
  ```

- `url`: Campo para URLs
  ```html
  <input type="url">
  ```

- `tel`: Campo para números telefónicos
   ```html
  <input type="tel">
  ```

- `search`: Campo de búsqueda
   ```html
  <input type="search">
  ```

### 📆 Inputs numéricos y de fecha/Hora:

- `number`: Campo para números
   ```html
  <input type="number" min="1" max="100">
  ```

- `range`: Selector de rango
   ```html
  <input type="range" min="0" max="100">
  ```

- `date`: Campo para fechas
  ```html
  <input type="date">
  ```
  
- `time`: Campo para hora
  ```html
  <input type="time">  
  ```

- `datetime-local`: Fecha y hora local
  ```html
  <input type="datetime-local">
  ```

- `month`: Selector de mes
  ```html
  <input type="month">
  ```

- `week`: Selector de semana
  ```html
  <input type="week">
  ```


### ☑️ Inputs de selección:

- `checkbox`: Casilla de verificación
  ```html
  <input type="checkbox">
  ```

- `radio`: Botones de opción
  ```html
  <input type="radio" name="grupo">
  ```

- `color`: Selector de color
  ```html
  <input type="color">
  ```

- `file`: Selector de archivos
  ```html
  <input type="file">
  ```

### 🔘 Inputs de Botones:

- `submit`: Botón de envío
  ```html
  <input type="submit">
  ```

- `reset`: Botón de reinicio
  ```html
  <input type="reset">
  ```

- `button`: Botón genérico
  ```html
  <input type="button">
  ```

### 🛠️  Inputs Especiales:

- `hidden`: Campo oculto (no visible), Este campo no es visible pero está presente en el formulario
  ```html
  <input type="hidden">
  ```

- `image`: Botón de imagen
  ```html
  <input type="image" src="imagen.png">
  ```

---

## 🛠️ Atributos importantes para inputs:

-- Los inputs en HTML pueden usar diversos atributos para mejorar la funcionalidad y experiencia del usuario. A continuación verás cada atributo con su explicación y ejemplo práctico:


- `required`: Campo obligatorio, Hace que el campo sea obligatorio para enviar el formulario. Si está vacío, el navegador mostrará un mensaje de error.
  ```html
  <input type="text" required>
  ```
  Intenta enviar sin llenar este campo

- `placeholder`: Texto de ayuda, Muestra un texto de ayuda dentro del campo que desaparece cuando el usuario empieza a escribir.
  ```html
  <input type="email" placeholder="ejemplo@correo.com">
  ```

- `min` / `max`: Valores límite, Define valores mínimo y máximo para campos numéricos y de fecha. El navegador validará automáticamente.
  ```html
  <input type="number" min="18" max="65">
  ```
  (Prueba ingresar un número fuera del rango)

- `step`: Incremento, Especifica el incremento en campos numéricos y de rango. Útil para precios, porcentajes, etc.
  ```html
  <input type="number" step="0.50">
  ```
  (Usa las flechas del campo para ver el incremento)

- `pattern`: Validación personalizada, Define un patrón de validación usando expresiones regulares para formatos específicos.
  ```html
  <input type="text" pattern="[0-9]{5}">
  ```
  (Solo acepta exactamente 5 números)

- `disabled`: Campo desactivado, Desactiva el campo, impidiendo la interacción del usuario. El valor no se envía en el formulario.
  ```html
  <input type="text" disabled>  
  ```
  (Este campo no es interactivo)

- `readonly`: Solo lectura, Hace el campo de solo lectura, visible pero no editable. A diferencia de disabled, el valor sí se envía.
  ```html
  <input type="text" readonly>
  ```
  (Puedes seleccionar el texto pero no editarlo)

- `multiple`: Selección múltiple, Permite seleccionar múltiples valores en campos de archivo o listas.
  ```html
  <input type="file" multiple>
  ```
  (Puedes seleccionar varios archivos a la vez)

- `accept`: Tipos de archivo permitidos, Especifica qué tipos de archivo son permitidos en inputs de tipo file.
  ```html
  <input type="file" accept=".pdf">
  ```
  (Solo permite seleccionar archivos PDF)

- `autocomplete`: Control de autocompletado, Controla si el navegador puede autocompletar el campo con datos guardados previamente.
  ```html
  <input type="text" autocomplete="off">
  ```

- `value`: Valor predeterminado, Establece un valor inicial que aparece cuando se carga la página.
  ```html
  <input type="text" value="España">
  ```
  (Valor predefinido que el usuario puede cambiar)

- `maxlength`: Límite de caracteres, Limita el número máximo de caracteres que se pueden escribir en el campo.
  ```html
  <input type="text" maxlength="50">
  ```
  (No podrás escribir más de 50 caracteres)

- `size`: Ancho visual, Define el ancho visual del campo en número de caracteres.
  ```html
  <input type="text" size="40">
  ```

- `autofocus`: Foco automático, Hace que el campo reciba el foco automáticamente cuando se carga la página.
  ```html
  <input type="text" autofocus>
  ```
  (Solo un elemento por página debe tener autofocus)

- `form`: Asociar con formulario, Permite asociar un input con un formulario específico aunque no esté dentro de él.
  ```html
  <input type="text" form="miFormulario">
  ```
  (Este input está fuera del form pero se enviará con él)

- `list`: Lista de sugerencias, Conecta el input con un datalist para mostrar opciones sugeridas.
  ```html
  <input type="text" list="navegadores">
  ```
  (Empieza a escribir para ver las sugerencias)

- `formnovalidate`: Omitir validación, En botones de envío, permite enviar el formulario sin validar los campos.
  ```html
  <input type="submit" formnovalidate>
  ```

---

## 💡Mejores Prácticas para Inputs

- 🎯 Usa el tipo correcto:
  Cada tipo de input tiene un propósito específico. Usar `type="email"` para emails activa la validación automática y mejora la experiencia en móviles.

- 📱 Piensa en móviles:
  Los tipos `tel`, `email` y `number` muestran teclados específicos en dispositivos móviles, facilitando la entrada de datos.

- ✅ Valida siempre:
  Combina validación HTML (required, pattern) con validación en el servidor. HTML es rápido pero no es seguro como única validación.

- 💡 Ayuda al usuario:
  Usa `placeholder` para ejemplos, `title` para instrucciones y `label` siempre asociados con el input.

- 🚀 Mejora la UX:
  Usa `autofocus` en el campo principal, `autocomplete` para datos comunes y `list` para sugerencias.

- 🔒 Seguridad:
  Nunca confíes solo en validación del cliente. Siempre valida y sanitiza datos en el servidor para evitar ataques.

---

## 📝 Actividades Prácticas:

### ✅ Actividad 1: Estructura semántica

## Objetivo: Aplicar etiquetas semánticas para estructurar adecuadamente una página web.

- 1 Crear un archivo llamado `pagina_semantica.html`
- 2 Construir una página con la siguiente estructura:
    - Un `<header>` que contenga un título y una pequeña descripción
    - Un `<nav>` con al menos 4 enlaces (pueden ser ficticios)
    - Un `<main>` dividido en 2 `<section>`:
        - Primera sección: 2 `<article>` con contenido breve
        - Segunda sección: Un formulario simple
        
    - Un `<aside>` con "contenido relacionado" o "publicidad"
    - Un `<footer>` con derechos de autor y año

Bonus: Utilizar `<time>`, `<figure>` y `<figcaption>` en alguna parte de la página.


### ✅ Actividad 2: Proyecto "Mi Blog Personal"


## Objetivo: Integrar todos los conocimientos adquiridos en un pequeño proyecto de blog o sitio de noticias personal.

- Descripción del proyecto:

- Crearás la primera versión de un blog personal donde podrás compartir artículos, noticias o temas de tu interés. Este proyecto lo iremos mejorando en clases posteriores añadiendo CSS y JavaScript.

    - 1 Crear una carpeta llamada `mi-blog` con los siguientes archivos:
        - `index.html` (página principal)
        - `articulo1.html` (un artículo completo)
        - `sobre-mi.html` (página con información personal)
        - `contacto.html` (formulario de contacto)

    - 2 En `index.html`:
        - Header con el nombre de tu blog y un lema
        - Menú de navegación con enlaces a todas las páginas
        - Sección principal con 3 tarjetas de artículos (cada una con título, fecha, imagen y resumen)
        - Barra lateral con "sobre mí" resumido y categorías (lista)
        - Pie de página con derechos, año y redes sociales
  
    - 3 En `articulo1.html`:
        - Mismo header y navegación que en index
        - Contenido del artículo completo:
            - Título principal y fecha
            - Imagen destacada
            - Texto dividido en párrafos
            - Una lista (ordenada o no)
            - Una tabla con datos relevantes
        - Sección de comentarios (simulada con un comentario ya hecho)
        - El mismo pie de página
    
    - 4 En `sobre-mi.html`:
        - Tu foto (o imagen de avatar)
        - Información personal (puede ser ficticia)
        - Lista de habilidades o intereses
        - Enlaces a redes sociales
    
    - 5 En `contacto.html`:
        - Formulario de contacto completo
        - Campos para nombre, email, asunto y mensaje
        - Casillas de verificación para suscripción
        - Botón de envío
        - Información alternativa de contacto

- Sugerencias:

    - Usa etiquetas semánticas para toda la estructura
    - No te preocupes aún por el diseño visual, nos enfocaremos en la estructura HTML
    - Puedes usar contenido ficticio o generado para los textos
    - Utiliza imágenes gratuitas de internet o tus propias imágenes
    - Revisa tu código en el validador de HTML para asegurarte de que es correcto

**💡 Bonus**: Añade metadatos en el `<head>` como autor, descripción y palabras clave.


## 📚 Recursos Adicionales

- [🔗 Ver clase online](https://qrsurcba.online/landing_cursos/pages/clases-front/clase-4.php)
---
