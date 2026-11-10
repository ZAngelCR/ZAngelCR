# FASE DE ANALISIS 
## 1. A quiénes revisé

| # | Usuario | Link a sus perfiles |
|---|---|---|
| 1 | rossjrw (Ross Williams) | [github.com/rossjrw/rossjrw](https://github.com/rossjrw/rossjrw) |
| 2 | Xx-Ashutosh-xX (Ashutosh Saxena) | [github.com/Xx-Ashutosh-xX/Xx-Ashutosh-xX](https://github.com/Xx-Ashutosh-xX/Xx-Ashutosh-xX) |
| 3 | CyrisXD | [github.com/CyrisXD/CyrisXD](https://github.com/CyrisXD/CyrisXD) |

---

## 2. Comparación rápida de los tres perfiles

| Criterio | 1. rossjrw | 2. Xx-Ashutosh-xX | 3. CyrisXD |
|---|---|---|---|
| **Primera impresión (10 segundos)** | Es un juego: el Juego Real de Ur, partida n.º 31, y te invita a jugar. Cuesta saber quién es la persona y a qué se dedica; eso solo está en la barra lateral de GitHub. | Un «Konichiwa» con un GIF. Enseguida dice que tiene 19 años, es de India y le gustan el Machine Learning y la IA. Es cercano y relajado, pero no cuenta qué ha construido. | Banner con su nombre y una frase («building tools for AI agents»). Abajo se presenta como desarrollador full-stack de Nueva Zelanda con 17 años de experiencia. Se entiende de una. |
| **Cómo está organizado** | Bienvenida, tablero, jugadas posibles, secciones desplegables (partida actual y anteriores), reglas y unas insignias al final. Se siente que todo gira alrededor del juego, no de él. | Saludo, About ME, Languages & Tools, Contact Me y una tarjeta de estadísticas. Secciones cortas con emojis y en buen orden, pero sin apartado de proyectos. | Banner, insignias sociales, Hi there, What I'm building (tabla), blog, My toolbox y Stats. Va de «quién soy» a «qué hago» y luego «con qué lo hago». |
| **Habilidades** | No tiene sección de habilidades. Lo que sabe se nota en cómo armó el juego (GitHub Actions e Issues), pero no lo dice. | Iconos con texto (Python, Java, Bash, Google Cloud, VS Code). Mezcla tecnologías con cosas como PC, Edge y PlayStation. Las lista sin mostrar dónde las usó. | Cuadrícula de iconos (TypeScript, JavaScript, Node, React, Docker...) sin texto. Se reconocen rápido, pero hay que saberse los logos. Sus proyectos y su blog respaldan lo que muestra. |
| **Proyectos** | El proyecto es el perfil en sí. En su página de GitHub tiene fijados notifier, pr-preview-action, scp, Black-Highlighter y un gist de cheatsheets. | Ninguno en el README. En su página tiene fijados Real-Time-Face-Mask-Detection-Model, CNN-TA, Neural-Style-Transfer y web-site, pero solo dos tienen descripción (y una solo repite el nombre). | Una tabla «Proyecto / Qué hace» con tres proyectos (Pilot Light, agent-notify y block-clankers), cada uno con una línea y su enlace. También menciona que colabora en un proyecto open source. |
| **Contacto** | En el README, ninguno. Pide que le escriban por Issues con `cc @rossjrw`. Su web está en la barra lateral. | Botones de Gmail y LinkedIn con un mensajito amistoso. | Mastodon y su sitio web al final, y botones de Follow y Sponsor arriba. Correo no se ve. |
| **Accesibilidad y móvil** | El tablero es una imagen externa sin texto alternativo, pero lo que pasa en el juego también está escrito en las tablas. Esas tablas son anchas para el celular. En la captura hay una imagen rota. | Las imágenes tienen texto alternativo (nombre del icono; «GIF» en los GIF, que dice poco). Los iconos están en su propio repo, pero la tarjeta de estadísticas depende de otro servicio y en la captura sale rota. Los GIF pesan y el texto de contacto es pequeño. | Mucho contenido visual (banner, insignias, iconos, estadísticas) que depende de servicios externos. La tabla y las listas se leen bien. Si tienen texto alternativo en la versión de tu captura: falta confirmar (en una versión anterior que pude abrir, sí lo tenían). |


### Lo que me llevo de cada uno

- **rossjrw:** una idea original puede ser un perfil muy llamativo, pero si no cuenta quién eres, el visitante se queda sin saber con quién está hablando. Me quedo con la idea de poner en texto lo mismo que se muestra en imágenes.
- **Ashutosh:** el tono cercano y las secciones simples funcionan. Le falta mostrar proyectos y sobran cosas como Edge o PlayStation.
- **Cyris:** es el más completo. Se entiende rápido quién es, tiene proyectos explicados con enlace y todo sigue un orden claro.
- **Lo que no quiero repetir:** imágenes rotas, depender de servicios externos para cosas importantes, habilidades solo con iconos y GIF pesados.

---

## 3. Tres repositorios fijados bajo la lupa

Elegí estos tres:

- [rossjrw/pr-preview-action](https://github.com/rossjrw/pr-preview-action), fijado en el perfil de rossjrw.
- [CyrisXD/love-lock-card](https://github.com/CyrisXD/love-lock-card), destacado en su sección «Past work».
- [Xx-Ashutosh-xX/CNN-TA](https://github.com/Xx-Ashutosh-xX/CNN-TA), fijado en el perfil de Ashutosh.

| Caracteristicas | pr-preview-action | love-lock-card | CNN-TA |
|---|---|---|---|
| **Descripción corta** | Sí. Una acción de GitHub que publica una vista previa de cada pull request y se limpia sola. | Sí. Una tarjeta de Home Assistant para bloquear otras tarjetas con contraseña o confirmación. | Sí, cortita y con una errata («procesing»). |
| **Enlace a demo o sitio** | Sí, a su página en GitHub Marketplace. | No. | No. |
| **README: para qué sirve** | Sí, con lista de características. | Sí. Avisa que ya no le agrega funciones pero acepta pull requests. | Sí, pero suena a resumen de un estudio académico. |
| **README: tecnologías** | GitHub Actions y GitHub Pages (el lenguaje principal es Shell). | Home Assistant y JavaScript. | TA-Lib, PIL y una red neuronal convolucional, explicadas en el texto. |
| **README: instalación y uso** | Muy completo: pasos de configuración, ejemplos, tablas de opciones y salidas, errores comunes y consejos. | Instalación con HACS o a mano, tabla de opciones y tres ejemplos. | No vi cómo instalarlo ni usarlo. Es como un informe. |
| **README: capturas** | Sí, dos. | Sí, un GIF que muestra los tres tipos de bloqueo. | No. |
| **Licencia** | Sí, MIT. | Sí, MIT. | Sí, MIT. |
| **.gitignore** | Sí. | No. | No. |
| **Commits** | 190. Repositorio que se actualiza constantemente. Gran parte de los commits son merge pull requests. | 21 commits. | 7 commits.  |
| **Issues, PR, ramas y Releases** | 20 Issues y 12 pull requests abiertos, y Discussions activadas. Rama `main`. Releases: falta confirmar (el README usa `@v1`, así que seguramente hay versiones). | 19 Issues y 1 pull request abiertos. Rama `master`. No vi Releases. | Falta confirmar. |
| **Carpetas** | Ordenadas: `.github`, `lib`, `test`, `action.yml`, `package.json`, `LICENSE` y `README.md`. | Mínimas: `LICENSE`, `README.md`, `hacs.json` y `love-lock-card.js`. Para un proyecto de un solo archivo está bien. | Muchos archivos sueltos que podrian estar mas ordenados en carpetas. Carpetas: `Data`, `Graphs`, `MODEL/type_1`, `Results`. Parece que solo lo organizo por tipos de archivo (.csv en Data, .png en Graphs, etc) |
| **Popularidad** | 448 estrellas y 72 forks. | 153 estrellas y 15 forks. | 9 estrellas y 6 forks. |


### Lo que me llevo de los repos

- **pr-preview-action** es el ejemplo a seguir: tiene descripción, topics, enlace, README con ejemplos, licencia, `.gitignore`, pruebas y carpetas ordenadas.
- **love-lock-card** cumple lo básico para un proyecto pequeño (README con instalación y uso, GIF y licencia MIT), pero le faltan topics y `.gitignore`.
- **CNN-TA** es un recordatorio: de nada sirve explicar la teoría si nadie sabe cómo instalar y usar el proyecto.

---

## 4. Qué quiero que tenga mi perfil

### 4.1 Lo que tiene que mostrar (requisitos funcionales)

| Código | Requisito |
|---|---|
| RF-01 | Que en 10 segundos se sepa mi nombre, a qué me dedico o quiero dedicarme, y una frase sobre lo que hago. |
| RF-02 | Una sección «Sobre mí» cortita: formación, intereses y qué busco. |
| RF-03 | Mis habilidades y tecnologías agrupadas por tipo y siempre escritas con su nombre (Quizá le meta íconos). |
| RF-04 | Entre 2 y 4 proyectos destacados, cada uno con: nombre, qué problema resuelve, tecnologías, funciones principales, enlace al repo y a la demo si hay. |
| RF-05 | Al menos dos formas de contactarme a la vista (por ejemplo, LinkedIn y correo). |
| RF-06 | Un orden fijo y fácil de seguir: presentación, sobre mí, habilidades, proyectos y contacto. |
| RF-07 | Solo enlaces que funcionen y que valgan la pena. |

### 4.2 Cómo tiene que verse y portarse (requisitos no funcionales)

| Código | Tema | Requisito |
|---|---|---|
| RNF-01 | Lectura | Títulos claros, párrafos cortos, listas y tablas. Nada de paredes de texto. |
| RNF-02 | Lectura | Un tono coherente y cuidado, sin adornos que no aporten (GIF pesados, insignias que no vienen al caso). |
| RNF-03 | Accesibilidad | Texto alternativo descriptivo en cada imagen e insignia. |
| RNF-04 | Accesibilidad | Que nada importante dependa solo de una imagen o un emoji: siempre debe haber su versión en texto. |
| RNF-05 | Accesibilidad | Buen contraste y que se vea bien en el celular (tablas de máximo tres columnas e imágenes que no se salgan de la pantalla). |
| RNF-06 | Que no se rompa | No depender de servicios externos para lo importante. Si uso alguno, que el perfil se entienda igual cuando falle. |
| RNF-07 | Mantenimiento | Solo Markdown (sin HTML ni CSS) y mis imágenes en una carpeta `assets/`. |
| RNF-08 | Mantenimiento | Commits pequeños y con mensajes claros (`docs:`, `fix:`, `feat:`). |
| RNF-09 | Privacidad | Decidir con calma qué datos de contacto muestro (por ejemplo, correo a la vista o solo LinkedIn). |
| RNF-10 | Repos destacados | Que cada uno tenga, como mínimo, descripción, topics, README con instalación y uso, licencia y `.gitignore`. |

---

## 5. Referencias

- rossjrw. (s. f.). *rossjrw/rossjrw* [Repositorio]. GitHub. https://github.com/rossjrw/rossjrw
- rossjrw. (s. f.). *rossjrw/pr-preview-action* [Repositorio]. GitHub. https://github.com/rossjrw/pr-preview-action
- Xx-Ashutosh-xX. (s. f.). *Xx-Ashutosh-xX/Xx-Ashutosh-xX* [Repositorio]. GitHub. https://github.com/Xx-Ashutosh-xX/Xx-Ashutosh-xX
- Xx-Ashutosh-xX. (s. f.). *Xx-Ashutosh-xX/CNN-TA* [Repositorio]. GitHub. https://github.com/Xx-Ashutosh-xX/CNN-TA
- CyrisXD. (s. f.). *CyrisXD/CyrisXD* [Repositorio]. GitHub. https://github.com/CyrisXD/CyrisXD
- CyrisXD. (s. f.). *CyrisXD/love-lock-card* [Repositorio]. GitHub. https://github.com/CyrisXD/love-lock-card