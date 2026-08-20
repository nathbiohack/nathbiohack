# Kipu Portfolio Starter

Plantilla de portafolio personal para procesos de postulación a trabajos, posgrados, becas y oportunidades de investigación.

Está construida únicamente con **HTML y CSS**. No requiere instalar programas, librerías ni ejecutar comandos.

## Estructura

```text
kipu-portfolio-starter/
├── index.html
├── style.css
├── assets/
│   ├── documents/
│   │   └── REEMPLAZA-CON-TU-CV.txt
│   └── images/
│       └── recursos visuales del ejemplo
└── README.md
```

## Cómo abrirla

Haz doble clic en `index.html`. La página se abrirá en tu navegador.

## Qué debes reemplazar

1. **Nombre y objetivo:** busca `Nathaly` en `index.html`.
2. **Descripción breve:** reemplaza el párrafo debajo del título principal.
3. **Educación:** cambia fechas, programas, instituciones y descripciones.
4. **Proyectos:** conserva de dos a cuatro. Explica problema, aporte, herramientas y resultado.
5. **Experiencia:** prioriza los cargos relacionados con la postulación.
6. **Habilidades:** elimina etiquetas que no representen tu perfil y agrupa las restantes.
7. **Contacto:** reemplaza `tu.correo@ejemplo.com`, LinkedIn y GitHub.
8. **CV:** coloca tu PDF en `assets/documents/` y actualiza los dos enlaces del HTML.

## Reemplazar el CV

1. Copia tu archivo PDF dentro de `assets/documents/`.
2. Nómbralo `cv.pdf`.
3. En `index.html`, cambia `assets/documents/REEMPLAZA-CON-TU-CV.txt` por `assets/documents/cv.pdf`.

## Reemplazar imágenes

Guarda nuevas imágenes dentro de `assets/images/`. Después cambia el valor de `src` en las tarjetas de proyecto o en la sección de experiencia.

```html
<img src="assets/images/mi-proyecto.png" alt="Descripción clara de la imagen">
```

## Editar el diseño

Abre `style.css` y modifica las variables del inicio:

```css
:root {
  --ink: #111a2d;
  --blue: #315cf4;
  --paper: #ffffff;
}
```

La plantilla usa **Outfit** para títulos y navegación, y **Open Sans** para párrafos. Las tipografías se cargan desde Google Fonts; si no hay conexión, el navegador usa Arial como alternativa.

## Cambiar los iconos

Los iconos sociales y de experiencia usan Bootstrap Icons. Para reemplazar uno, cambia únicamente la clase `bi-...` en `index.html`.

```html
<i class="bi bi-linkedin"></i>
<i class="bi bi-github"></i>
<i class="bi bi-envelope"></i>
<i class="bi bi-instagram"></i>
<i class="bi bi-robot"></i>
<i class="bi bi-cpu"></i>
```

Puedes consultar otros nombres en `https://icons.getbootstrap.com/`.

## Las cuatro cards de proyectos

La sección Projects contiene cuatro ejemplos dentro de una fila horizontal. En computadora aparecen dos cards a la vez y se puede desplazar la fila para ver las demás. En celular se muestra una card principal y parte de la siguiente para indicar que hay más contenido.

Cada card repite la misma estructura editable:

- Fecha.
- Título del proyecto.
- Rol, área y año.
- Problema, contribución y resultado.
- Enlace para leer el caso completo.

## Antes de publicar

- Revisa que no queden textos de ejemplo.
- Comprueba todos los enlaces.
- Usa imágenes propias o con licencia.
- Exporta el CV como PDF.
- Ábrela en computadora y celular.
- Pide a otra persona que encuentre tu contacto y tu mejor proyecto en menos de un minuto.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube el contenido de esta carpeta.
3. Abre **Settings → Pages**.
4. Selecciona la rama principal y la carpeta raíz.
5. Guarda y espera la URL pública.

Los textos de esta plantilla son ejemplos y deben verificarse antes de usarlos en una postulación real.
