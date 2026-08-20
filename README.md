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

# ✨ Editar esta plantilla con Claude, Codex u otro asistente de código

Si no sabes HTML o CSS, puedes utilizar un asistente de programación como **Claude Code, Codex, Cursor o GitHub Copilot** para personalizar esta plantilla.

Abre la carpeta completa del proyecto en la herramienta que quieras utilizar y pega el siguiente prompt.

---

## Prompt para empezar a personalizar tu website

### Copia este prompt

```text
Quiero que me ayudes a personalizar este portfolio website.

Antes de modificar código, revisa completamente los archivos del proyecto, especialmente:

- index.html
- style.css
- assets/

IMPORTANTE:

No quiero que reconstruyas el website desde cero.

Quiero conservar la estructura general, responsive design, componentes, navegación y estilo visual existente.

Tu trabajo será ayudarme a adaptar esta plantilla a mi perfil.

Primero analiza el website y explícame brevemente:

1. Qué secciones existen actualmente.
2. Qué contenido debo reemplazar.
3. Qué imágenes o archivos debo cambiar.
4. Qué enlaces debo actualizar.
5. Qué información necesitas de mí antes de editarlo.

Después hazme preguntas para recopilar mi información.

Necesito definir:

NOMBRE
Mi nombre completo.

OBJETIVO DEL WEBSITE
Por ejemplo:
- conseguir un internship
- aplicar a un trabajo
- aplicar a un PhD
- mostrar proyectos de investigación
- crear un portfolio de diseño
- mostrar proyectos de software

PERFIL
Mi carrera, profesión o área principal.

3–5 KEYWORDS
Palabras que definan mi perfil profesional.

Ejemplos:
Bioengineering · Medical AI · Computational Science

Data Science · Economics · Policy

UX Design · Product · Research

HEADLINE
Una frase corta de aproximadamente 5–12 palabras que explique qué hago o qué tipo de problemas quiero resolver.

INTRODUCTION
Una descripción breve de aproximadamente 30–50 palabras.

ABOUT
Una descripción de aproximadamente 50–100 palabras explicando:
- quién soy
- mi formación
- mis principales áreas de interés
- qué problemas me interesa resolver
- hacia dónde quiero orientar mi carrera

EDUCATION
Para cada formación:
- año inicial y final
- grado o programa
- universidad o institución
- ciudad y país
- especialización, tesis o información relevante si corresponde

PROJECTS
Seleccionaremos entre 3 y 6 proyectos.

Para cada proyecto necesito:
- título
- año
- problema
- qué hice específicamente yo
- herramientas o métodos
- resultado
- 3–5 keywords
- enlace si existe
- imagen si existe

EXPERIENCE
Para cada experiencia:
- fechas
- rol
- organización
- ubicación
- 1–2 frases describiendo mi contribución

SKILLS
Organiza mis habilidades en categorías.

Por ejemplo:

Programming
Research
Design
Data
Communication

CONTACT
Necesito actualizar:
- email
- LinkedIn
- GitHub
- otras redes profesionales
- CV

Cuando tengas esta información:

1. Propón el contenido final antes de cambiarlo.
2. No inventes experiencias, premios, publicaciones, universidades, resultados o habilidades.
3. Si falta información, pregúntame.
4. Mantén los textos breves y adecuados para un portfolio.
5. Prioriza evidencia concreta sobre adjetivos.
6. No llenes el website con texto innecesario.
7. Conserva el diseño responsive.
8. No elimines funcionalidades existentes sin preguntarme.
9. Mantén HTML y CSS simples y fáciles de editar.
10. Antes de terminar, revisa que no queden textos de ejemplo de la plantilla.
```

---

# Prompt para editar una sección específica

Si no quieres modificar todo el website, puedes pedir cambios únicamente en una sección.

Por ejemplo:

### Hero

```text
Revisa únicamente la sección HERO de index.html.

No cambies todavía el diseño.

Quiero adaptar el contenido a mi perfil profesional.

Ayúdame primero a definir:

- 3–5 keywords
- headline de máximo 12 palabras
- introducción de 30–50 palabras
- botones principales
- redes profesionales que debería mostrar

Hazme las preguntas necesarias.

No inventes información sobre mí.

Cuando aprobemos el texto, actualiza únicamente esa sección del HTML.
```

---

### About

```text
Quiero editar únicamente la sección ABOUT de mi portfolio.

Mantén el diseño actual.

Ayúdame a escribir un texto de entre 50 y 100 palabras que explique:

- quién soy
- mi formación
- mis áreas principales
- qué tipo de problemas me interesa resolver
- hacia dónde quiero orientar mi carrera

No repitas literalmente el Hero.

Evita palabras genéricas como passionate, motivated, innovative o hard-working si no aportan información.

Primero propón el texto.

No modifiques el código hasta que lo apruebe.
```

---

### Education

```text
Quiero actualizar únicamente la sección EDUCATION.

Mantén el formato de timeline existente.

Te voy a dar mi información académica.

Para cada experiencia utiliza:

YEAR – YEAR
DEGREE / PROGRAM
UNIVERSITY / INSTITUTION
CITY, COUNTRY
OPTIONAL DESCRIPTION

La descripción debe tener máximo 1–2 frases y solo debe aparecer si explica algo relevante como:

- especialización
- tesis
- scholarship
- research focus
- academic distinction

No inventes información.

Después actualiza las cards o entradas existentes sin cambiar el estilo visual.
```

---

### Projects

```text
Quiero actualizar únicamente la sección PROJECTS de mi portfolio.

No quiero una lista de todo lo que he hecho.

Ayúdame a seleccionar entre 3 y 6 proyectos que mejor demuestren mis capacidades.

Para cada proyecto utiliza esta estructura:

PROJECT TITLE

ROLE / AREA / YEAR

Breve descripción del problema.

Qué hice específicamente yo.

Resultado o impacto, si existe.

3–5 keywords.

Link.

Cada card debe poder entenderse rápidamente.

No inventes métricas, resultados ni tecnologías.

No utilices frases genéricas como:
"This innovative project leverages cutting-edge AI."

Prefiere descripciones concretas.

Una vez definido el contenido, actualiza las cards existentes manteniendo el diseño actual.
```

---

### Experience

```text
Quiero editar únicamente la sección EXPERIENCE.

Para cada experiencia incluye:

YEAR – YEAR
ROLE
ORGANIZATION
LOCATION
1–2 frases sobre mi contribución

No copies todas las responsabilidades de mi CV.

Prioriza las experiencias relacionadas con el objetivo de mi website.

Mantén el timeline y los estilos actuales.
```

---

### Skills

```text
Quiero reorganizar la sección SKILLS.

No quiero una lista enorme de tecnologías.

Ayúdame a agrupar mis habilidades en categorías coherentes.

Por ejemplo:

Programming
AI & Data
Research
Design
Communication

Incluye únicamente habilidades que realmente pueda demostrar mediante mis proyectos, estudios o experiencia.

Después modifica únicamente esta sección.
```

---

# Prompt para cambiar el diseño sin destruir la plantilla

Si quieres cambiar colores, tipografías o componentes, utiliza un prompt específico.

```text
Quiero mejorar el diseño visual de este portfolio sin reconstruirlo desde cero.

Conserva:

- estructura HTML
- contenido
- responsive design
- navegación
- secciones
- enlaces
- funcionalidad

Puedes mejorar:

- tipografía
- paleta de colores
- spacing
- botones
- borders
- cards
- hierarchy
- hover states

Quiero un diseño:

- limpio
- profesional
- editorial
- moderno
- fácil de leer
- con suficiente espacio en blanco

Evita:

- gradients innecesarios
- glow effects
- glassmorphism excesivo
- animaciones llamativas
- estética genérica de website generado por AI
- demasiados border-radius
- sombras fuertes
- demasiados colores

Antes de modificar el CSS:

1. analiza la paleta actual
2. analiza la tipografía
3. identifica 5 mejoras concretas
4. explícame qué cambiarías

Después espera mi aprobación.
```

---

# Prompt para adaptar el website a una referencia visual

También puedes mostrarle una captura de Pinterest, Behance, Figma, Awwwards u otro website.

Utiliza este prompt:

```text
Quiero utilizar esta imagen únicamente como REFERENCIA VISUAL para mejorar mi portfolio.

No quiero copiarla exactamente.

Analiza:

- typography
- hierarchy
- spacing
- grid
- navigation
- buttons
- cards
- color palette
- visual rhythm

Después identifica qué principios visuales podemos trasladar a mi website actual.

IMPORTANTE:

No reconstruyas el website desde cero.

Trabaja sobre los archivos existentes.

Conserva el contenido y las secciones actuales.

Antes de modificar código explícame qué elementos tomarías como inspiración y cuáles no.
```

---

# Prompt para revisar el website antes de publicarlo

Cuando termines de editarlo, copia este prompt:

```text
Haz una revisión final de este portfolio antes de publicarlo.

Revisa todos los archivos.

Comprueba:

CONTENT
- que no queden textos placeholder
- que no haya información inventada
- que títulos y descripciones sean consistentes
- que los proyectos expliquen claramente mi contribución

LINKS
- navegación
- botones
- LinkedIn
- GitHub
- email
- CV
- links de proyectos

HTML
- estructura semántica
- alt text
- headings
- enlaces
- accesibilidad básica

CSS
- responsive design
- mobile
- desktop
- spacing
- overflow
- tamaños de texto

UX
- que mi perfil se entienda rápidamente
- que mi mejor proyecto sea fácil de encontrar
- que sea fácil contactarme
- que el CV sea fácil de descargar

PERFORMANCE
- imágenes demasiado grandes
- archivos innecesarios
- recursos que puedan optimizarse

No hagas cambios todavía.

Primero dame una checklist indicando:

PASS
WARNING
FIX

Después pregúntame si quiero que implementes las correcciones.
```

---

# Regla importante al utilizar AI

Claude, Codex u otros asistentes pueden ayudarte a escribir y modificar el website, pero **tú debes controlar el contenido**.

Nunca permitas que la herramienta invente:

```text
publications
awards
research results
companies
universities
scholarships
job titles
project metrics
programming skills
conference presentations
```

Si algo no existe, no debería aparecer en tu portfolio.

Un buen portfolio no necesita parecer impresionante en cada línea.

Necesita ser **claro, verificable y fácil de entender**.

1. Crea un repositorio en GitHub.
2. Sube el contenido de esta carpeta.
3. Abre **Settings → Pages**.
4. Selecciona la rama principal y la carpeta raíz.
5. Guarda y espera la URL pública.

Los textos de esta plantilla son ejemplos y deben verificarse antes de usarlos en una postulación real.
