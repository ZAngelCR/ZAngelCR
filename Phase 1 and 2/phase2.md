## 🗺️ 1. Esquema del README

```text
README.md
├── 👋 Presentación          → nombre, carrera, frase corta y qué busco
├── 🙋 Sobre mí              → 3 o 4 líneas + "Aprendiendo ahora" y "Siguiente objetivo"
├── 🛠️ Habilidades           → tabla por categoría
├── 🚀 Proyectos destacados  → 3 fichas (problema, tecnologías, funciones, repo, demo)
├── 🎓 Experiencia           → opcional: ayudantías, hackathons, voluntariado
└── 📫 Contacto              → LinkedIn, correo y GitHub
```

**Por qué este orden:** primero quién soy, luego lo que sé hacer, después las pruebas (proyectos) y al final cómo encontrarme.

---

## 🧩 2. Diseño del contenido

### Sección por sección

| Sección | ✅ Incluyo | 🚫 Evito | Formato | 🔗 Enlaces |
|---|---|---|---|---|
| **👋 Presentación** | Nombre, carrera y universidad, una frase y qué busco (por ejemplo, prácticas). | GIF pesados, animaciones, edad y datos que no aportan. | Título grande, una o dos líneas y botones de contacto con texto. | LinkedIn y GitHub. |
| **🙋 Sobre mí** | Qué estudio, qué me interesa, qué estoy aprendiendo y mi siguiente objetivo. | Listas largas de hobbies, textos de más de 5 líneas y frases de cliché. | Un párrafo corto y dos citas (`>`). | Ninguno. |
| **🛠️ Habilidades** | Lenguajes, frontend, backend, bases de datos y herramientas, y una línea de dónde las usé. | Cosas no técnicas, iconos sin nombre y tecnologías que apenas toqué. | Tabla «Categoría / Tecnologías» con insignias que muestran el nombre. | shields.io (el nombre va escrito en la insignia). |
| **🚀 Proyectos** | Máximo 3, con su ficha completa y mi aporte. | Repos sin README, proyectos sin demo ni explicación y tutoriales copiados. | Una ficha por proyecto (ver sección 3). | Repositorios y demos. |
| **🎓 Experiencia** | Ayudantías, hackathons o voluntariado, con una frase de lo que aprendí. | Relleno. Si no tengo nada sólido, la quito. | Lista de 2 o 3 viñetas. | Ninguno. |
| **📫 Contacto** | LinkedIn, correo y GitHub. | Demasiados canales y texto pequeño. | Botones y, debajo, el correo en texto plano por si no se puede hacer clic. | LinkedIn y `mailto`. |

### ⚡ Reglas de lectura rápida

- Lo más importante va **arriba** (que en 10 segundos se entienda quién soy).
- Cada sección empieza con un título con emoji, para ubicarse al vuelo.
- Párrafos de máximo 3 o 4 líneas, y tablas de máximo 3 columnas para que se lean bien en el celular.
- Separo los bloques grandes con `---`.
- **Toda** imagen e insignia lleva texto alternativo, y lo importante nunca depende solo de una imagen.
- Solo Markdown (sin HTML ni CSS), y mis imágenes propias en una carpeta `assets/`.

---

## 🧾 3. Fichas de proyectos
### Plantilla (la copio tal cual para cada proyecto)
 
```md
### 🏛️ Nombre del proyecto
 
> Una línea que diga qué es.
 
🎯 **Problema:** qué necesidad resuelve.
 
✨ **Funcionalidades:** las 3 o 4 cosas principales que hace.
 
🙋 **Mi aporte:** qué hice yo.
 
![Tecnología 1](https://img.shields.io/badge/Tecnología-color) ![Tecnología 2](https://img.shields.io/badge/Tecnología-color)
 
[![Repositorio](https://img.shields.io/badge/Repositorio-GitHub-181717?style=for-the-badge&logo=github)](URL-del-repo) [![Demo](https://img.shields.io/badge/Demo-Ver%20sitio-2ea44f?style=for-the-badge)](URL-de-la-demo)
```
 
### Mis tres proyectos (fichas listas para pegar)
  
**Por qué estos tres:** cubren una app completa en equipo (Django y Flutter), un prototipo web y un proyecto de electrónica con Arduino. Los pongo de más completo a más sencillo.
 
#### 🏫 Communitly (ESPOL Communities)
 
> Plataforma web para descubrir y gestionar los clubes y comunidades estudiantiles de ESPOL.
 
🎯 **Problema:** encontrar y administrar clubes y comunidades de ESPOL en un solo lugar.
 
✨ **Funcionalidades:** las y los estudiantes buscan comunidades, las siguen, ven eventos y envían solicitudes de ingreso; quienes gestionan una comunidad crean, editan y cancelan eventos, y aprueban o rechazan solicitudes.
 
🙋 **Mi aporte:** `Fui el encargado de las funcionalidades de Crear, Editar y Eliminar actividad, junto con todo lo que su apartado conlleva`
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
 
[![Repositorio](https://img.shields.io/badge/Repositorio-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/GrupAP/Communitly) **Demo:** no tiene en línea; se prueba en local o con Docker.
 
---
 
#### 🧭 Atrapados en la ruta
 
> Simulación de una app, publicada como página web con GitHub Pages.
 
🎯 **Problema:** El transporte universaritario es un caos. Buses que van más llenos de lo que deberían, malos tratos, impuntualidad, etc. Por eso inventamos DEVIO.
 
✨ **Funcionalidades:** simulación de la app en el navegador desde una sola página (`index.html`). 
 
🙋 **Mi aporte:** `Fui el segundo desarrollador a cargo del proyecto, actualizando constantemente las rutas, las opciones de pago con Balance de la app, verificacion por correo institucional, etc.`
 
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white)
 
[![Repositorio](https://img.shields.io/badge/Repositorio-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/esegarra2006-arch/esegarra2006-arch.github.io) [![Demo](https://img.shields.io/badge/Demo-Ver%20sitio-2ea44f?style=for-the-badge)](https://esegarra2006-arch.github.io/)
 
---
 
#### 🤖 DISPENSADOR
 
> Dispensador controlado con Arduino, con servomotor, módulo MP3 y parlante.
 
🎯 **Problema:** Proyecto de Fundamentos de Electricidad y Sistemas Digitales. Dispensador de comida de animales ecológico y fácil de construir
 
✨ **Funcionalidades:** movimiento con servomotor, sonido por parlante con módulo MP3, control de diodos y señales, y guardado de datos en la memoria EEPROM (con opción de borrarla).
 
🙋 **Mi aporte:** `Me encargue de hacer que la dispensasión de la comida sea automática y que suene una voz que atraiga al animal a la comida`
 
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
 
[![Repositorio](https://img.shields.io/badge/Repositorio-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/ZAngelCR/DISPENSADOR) **Demo:** no tiene.
 
---
 
### 🛠️ Antes de destacarlos, les falta esto
 
| Repositorio | Qué le falta |
|---|---|
| **Communitly** | Topics, enlace a una demo y licencia. Hay un `backend.rar` en la raíz que sobra (ya existe la carpeta `backend`). Lo demás está muy bien: README completo, `.gitignore` y 42 commits. |
| **Atrapados en la ruta** | El README tiene solo dos líneas: falta decir qué es, cómo usarlo y una captura. También topics y licencia. |
| **DISPENSADOR** | Descripción y topics. El README solo tiene notas de pines (y el pin 12 aparece para el servo y para el MP3, hay que revisarlo). Falta explicar qué hace, el montaje, una foto o video, y la licencia. |
---

## 🔀 4. Estrategia de commits

### Tipos que voy a usar

| Tipo | Para qué | Ejemplo |
|---|---|---|
| `docs` | Contenido y textos del README | `docs: Add some personal information and skill set` |
| `feat` | Algo nuevo y grande (un proyecto, una sección) | `feat: Add a link to the demo` |
| `fix` | Corregir errores (ortografía, enlaces rotos) | `fix: Correct gramatical and spelling errors` |
| `style` | Formato sin cambiar el contenido | `style: Order blank spaces and titles` |
| `chore` | Archivos de apoyo | `chore: Add picture of the banner to assets` |

### Mi hoja de ruta

1. `docs: Create README with title and presentation`
2. `docs: Add About Me section`
3. `feat: Add skill sets and technologies`
4. `feat: add project 1 entry with a link to the demo`
5. `feat: add project 2 entry`
6. `feat: add project 2 entry`
7. `docs: add experience section`
8. `docs: Add contact button and email`
9. `style: adjust the order and spacing of sections`
10. `fix: check links and correct spelling`

### Reglas

- Un commit por cambio importante, nada de subirlo todo junto.
- Formato `tipo: qué hice`, en ingles (solamente para practicar) con verbo en presente («agrega», «corrige») y corto.
- Después de cada commit, reviso cómo se ve en GitHub antes de seguir.
- Meta: que el historial se lea como la historia de cómo fue creciendo el perfil.
