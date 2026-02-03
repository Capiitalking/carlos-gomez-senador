# 📝 Instrucciones para Editar el Brochure de Campaña

## Archivos Incluidos

| Archivo | Descripción |
|---------|-------------|
| `brochure_senado.html` | Brochure principal editable |
| `flyer2_con_carlos.png` | Imagen del flyer original |
| `INSTRUCCIONES_EDICION.md` | Este archivo de instrucciones |

---

## Cómo Editar el Brochure

### Paso 1: Abrir el archivo
Abre el archivo `brochure_senado.html` con cualquier editor de texto:
- **Windows**: Notepad, Notepad++, Visual Studio Code
- **Mac**: TextEdit, Visual Studio Code, Sublime Text
- **Online**: Puedes usar editores como CodePen o JSFiddle

### Paso 2: Buscar las secciones editables
En el archivo encontrarás comentarios que indican qué puedes editar:
```html
<!-- EDITA TU PERFIL AQUÍ -->
<!-- EDITA TU FORMACIÓN AQUÍ -->
<!-- EDITA TU EXPERIENCIA AQUÍ -->
```

### Paso 3: Modificar el contenido
Simplemente cambia el texto entre las etiquetas HTML. Por ejemplo:

**Para cambiar el nombre:**
```html
<h1 class="nombre-candidato">Dr. Carlos Alberto<br>Gómez Portocarrero</h1>
```
Cambia "Dr. Carlos Alberto Gómez Portocarrero" por tu nombre.

**Para cambiar el teléfono:**
```html
<div class="contact-value">947 376 878</div>
```

**Para cambiar el lema:**
```html
<div class="lema">"REGLAS CLARAS Y OPORTUNIDAD PARA TODOS"</div>
```

---

## Cómo Cambiar la Foto del Candidato

1. Coloca tu nueva foto en la misma carpeta que el archivo HTML
2. Busca esta línea en el código:
```html
<img src="flyer2_con_carlos.png" alt="Carlos Gómez" class="foto-candidato">
```
3. Cambia `flyer2_con_carlos.png` por el nombre de tu nueva imagen

---

## Cómo Cambiar los Colores

Los colores están definidos al inicio del archivo CSS en la sección `:root`:

```css
:root {
    --color-azul-oscuro: #1a237e;    /* Azul principal */
    --color-azul-medio: #283593;      /* Azul secundario */
    --color-amarillo: #ffc107;        /* Amarillo/Dorado */
    --color-amarillo-claro: #ffecb3;  /* Amarillo claro */
    --color-blanco: #ffffff;          /* Blanco */
}
```

Simplemente cambia los códigos de color hexadecimales por los que prefieras.

---

## Cómo Ver los Cambios

1. Guarda el archivo después de hacer cambios
2. Abre el archivo `brochure_senado.html` en cualquier navegador web (Chrome, Firefox, Edge)
3. Presiona F5 para actualizar y ver los cambios

---

## Cómo Imprimir el Brochure

1. Abre el archivo en un navegador web
2. Presiona `Ctrl + P` (Windows) o `Cmd + P` (Mac)
3. Selecciona "Guardar como PDF" o tu impresora
4. Ajusta los márgenes a "Ninguno" o "Mínimo" para mejor resultado

---

## Secciones del Brochure

El brochure incluye las siguientes secciones que puedes personalizar:

1. **Encabezado**: Logo del partido y número de candidato
2. **Sección Hero**: Foto, nombre y lema de campaña
3. **Perfil Profesional**: Tu experiencia y trayectoria
4. **Formación Académica**: Tus estudios y títulos
5. **Experiencia Destacada**: Cargos y posiciones anteriores
6. **Competencias Clave**: Habilidades principales
7. **Propuesta de Valor**: Tu mensaje principal a los votantes
8. **Contacto**: Teléfono y redes sociales
9. **Pie de página**: Logo del partido y slogan

---

## Soporte

Si necesitas ayuda adicional para editar el brochure, puedes:
- Buscar tutoriales de HTML básico en YouTube
- Usar herramientas de edición visual como Adobe Dreamweaver
- Contactar a un diseñador web local

---

**¡Éxito en tu campaña!** 🗳️
