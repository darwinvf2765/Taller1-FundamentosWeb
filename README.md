
**Nombre:** Darwin Valencia  
**Asignatura:** Fundamentos WEB  
**Grupo:** 4303  
**Institucion:** UNICAMACHO

## Estructura

- `index.html`
- `README.md`
- `multimedia/`

## Verificación de código

### Caso A
**Problema identificado:** `<img>` no utiliza `href`. Para imágenes se utiliza el atributo `src`.

**Corrección realizada:**
```html
<img src="multimedia/imagen1.jpg" alt="Fotografía del estudiante">
```

**Fuente consultada:** MDN Web Docs.

### Caso B
**Problema identificado:** `<a>` utiliza `href` para indicar el destino del enlace. `src` no es el atributo correcto.

**Corrección realizada:**
```html
<a href="https://developer.mozilla.org/">Consultar MDN</a>
```

**Fuente consultada:** MDN Web Docs.

### Caso C
**Problema identificado:** `<source>` utiliza `src`, no `href`, para indicar el archivo multimedia.

**Corrección realizada:**
```html
<video controls>
    <source src="multimedia/video.mp4" type="video/mp4">
</video>
```

**Fuente consultada:** MDN Web Docs.

### Caso D
**Problema identificado:** `correo` no es un valor válido para `type`.

**Corrección realizada:**
```html
<input type="email" name="correo">
```

**Fuente consultada:** MDN Web Docs.

### Caso E
**La afirmación es:** Incorrecta.

**Justificación:** La etiqueta estándar para insertar imágenes es `<img>`, no `<image>`. Además, `<img>` es un elemento vacío y no requiere una etiqueta de cierre `</img>`.

**Ejemplo funcionando:**
```html
<img src="multimedia/imagen1.jpg" alt="Imagen de ejemplo">
```

**Fuente consultada:** MDN Web Docs.

## Diferencia entre video e iframe

`<video>` permite reproducir un archivo de video como parte del documento HTML. `<iframe>` permite insertar otro recurso o documento externo dentro de la página.

## Diferencia entre progress y meter

`<progress>` representa el avance de una tarea. `<meter>` representa una medida dentro de un rango conocido, por ejemplo un nivel o valoración.

## Preguntas de la estructura inicial

### ¿Qué información aparece dentro de la ventana del navegador?
Aparece el contenido ubicado dentro de `<body>`. El contenido de `<title>` no aparece normalmente dentro de la página.

### ¿Dónde se observa el contenido de `<title>`?
Se observa principalmente en la pestaña o título de la ventana del navegador.

## Multimedia

Coloque dentro de `multimedia/` sus archivos autorizados:

- `imagen1.jpg`
- `imagen2.jpg`
- `audio.mp3`
- `video.mp4`

No se deben inventar archivos multimedia que no estén disponibles. Los nombres deben coincidir exactamente con los utilizados en `index.html`.
