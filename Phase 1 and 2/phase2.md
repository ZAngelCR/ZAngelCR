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
