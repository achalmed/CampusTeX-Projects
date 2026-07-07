# 💼 git-projects — Biblioteca de Proyectos de Inversión

Biblioteca permanente de **formulación y evaluación de proyectos de inversión**: casos, planes de negocio, flujos de caja y análisis de sensibilidad.

> **Qué guarda:** modelos financieros en hoja de cálculo, documentos de casos, planes de negocio y material de evaluación de proyectos.

---

## 🎯 Filosofía (pensada para los próximos 20 años)

Esta carpeta **no es el repositorio de un solo curso**: es el hogar permanente de *todo* lo relacionado con Proyectos de Inversión, sin importar de dónde venga (INFOX, INEI, universidad, Udemy, autoestudio, un curso que compre mañana…).

Tres principios la gobiernan:

1. **El conocimiento manda sobre el origen.** El material se ordena por *tema* y por *tipo* (teoría, ejercicios, datos, presentaciones…), no por el curso que lo trajo. La procedencia se conserva como subcarpeta cuando aporta trazabilidad (`desde_<origen>/`, `INFOX_...`, `INEI_...`).
2. **Escalable e infinito.** Agregar un curso nuevo dentro de 10 años no obliga a reorganizar nada: se enchufa en la estructura existente.
3. **Nada se pierde ni se mezcla.** No se borran archivos; los duplicados se conservan; cada tecnología contiene únicamente sus propios recursos.

---

## 🗺️ Mapa de la biblioteca

Todas las bibliotecas (`git-python`, `git-R`, `git-stata`, …) comparten **el mismo esqueleto**. Solo existen las gavetas que se usan; el resto se crean cuando hagan falta.

| Carpeta | Para qué sirve | ¿En uso aquí? |
|---|---|:--:|
| `00_Inbox` | Bandeja de entrada. Material recién llegado o sin clasificar aún; incluye lo que llegó de otra tecnología en `desde_<origen>/`. **Debe quedar vacío** con el tiempo. | ✅ (5) |
| `01_Fundamentos` | Bases conceptuales de la tecnología: instalación, sintaxis mínima, primeros pasos independientes de cualquier curso. | — |
| `02_Curso_Base` | El o los cursos estructurados que sirven de columna vertebral de aprendizaje, con sus sesiones en orden. | ✅ (41) |
| `03_Temas` | Conocimiento organizado por tema (no por curso). Aquí converge material de distintas procedencias sobre un mismo asunto. | ✅ (36) |
| `04_Ejercicios` | Práctica aplicada: ejercicios resueltos y propuestos, prácticas, laboratorios y talleres. | ✅ (84) |
| `05_Proyectos` | Trabajos aplicados, casos de estudio, proyectos finales y trabajos colaborativos. | ✅ (284) |
| `06_Datasets` | Bases de datos y archivos de datos reutilizables entre cursos y temas. | ✅ (4) |
| `07_Presentaciones` | Diapositivas y material expositivo. | — |
| `08_Recursos` | Apoyo: información/sílabos de cursos, scripts base, utilidades y material de referencia interno. | ✅ (16) |
| `09_Plantillas` | Plantillas reutilizables listas para copiar y adaptar. | ✅ (2) |
| `10_Referencias` | Bibliografía, manuales, cheatsheets y fuentes externas de consulta. | ✅ (4) |
| `11_Evaluaciones` | Exámenes, parciales, sustitutorios y pruebas calificadas. | ✅ (11) |
| `12_Cursos_Completos` | Cursos completos que se conservan íntegros como unidad (con su estructura interna de sesiones/módulos). | — |
| `99_Historico` | Versiones antiguas, duplicados con valor histórico y material archivado. | — |

_La cifra entre paréntesis es la cantidad de archivos que hay hoy en esa gaveta._

---

## 📂 Qué hay hoy en este repositorio

### `00_Inbox` — 5 archivo(s)
Bandeja de entrada.

- `_por_clasificar`

### `02_Curso_Base` — 41 archivo(s)
El o los cursos estructurados que sirven de columna vertebral de aprendizaje, con sus sesiones en orden.

- `Unidades`

### `03_Temas` — 36 archivo(s)
Conocimiento organizado por tema (no por curso).

- `Ciclo_de_Proyecto_e_Inversion`
- `Sesiones`

### `04_Ejercicios` — 84 archivo(s)
Práctica aplicada: ejercicios resueltos y propuestos, prácticas, laboratorios y talleres.

- `Analisis_de_Sensibilidad`
- `Capital_de_Trabajo_y_Valor_de_Recupero`
- `Ejercicios_y_Casos`
- `Ejercicios_y_Casos_de_Sesion`
- `Homeworks`
- `Talleres`

### `05_Proyectos` — 284 archivo(s)
Trabajos aplicados, casos de estudio, proyectos finales y trabajos colaborativos.

- `Casos`
- `Planes_de_Negocio`
- `Promperu_2023_Inteligencia_Comercial`
- `Trabajos_Colaborativos`

### `06_Datasets` — 4 archivo(s)
Bases de datos y archivos de datos reutilizables entre cursos y temas.

- `Damodaran`

### `08_Recursos` — 16 archivo(s)
Apoyo: información/sílabos de cursos, scripts base, utilidades y material de referencia interno.

- `Informacion_del_Curso`
- `readme`

### `09_Plantillas` — 2 archivo(s)
Plantillas reutilizables listas para copiar y adaptar.

_(archivos directamente en la gaveta)_

### `10_Referencias` — 4 archivo(s)
Bibliografía, manuales, cheatsheets y fuentes externas de consulta.

_(archivos directamente en la gaveta)_

### `11_Evaluaciones` — 11 archivo(s)
Exámenes, parciales, sustitutorios y pruebas calificadas.

- `Examenes`
- `Test`


---

## 🔀 Relación con otras tecnologías (separación estricta)

Cada tecnología contiene **solo** sus propios recursos. Cuando un curso mezclaba varias herramientas, cada archivo viajó a la biblioteca de su tecnología:

- **Salió de aquí hacia:** `.tex` → `git-LaTex`.

El corazón está en `05_Proyectos` (casos y planes de negocio) y `04_Ejercicios` (talleres y análisis de sensibilidad).

---

## ➕ Cómo agregar un curso o material nuevo

Seguí siempre este flujo para que la biblioteca no se degrade:

1. **¿Es un curso completo y coherente?** → creá `12_Cursos_Completos/<Origen_Año_Tema>/` (p. ej. `Udemy_2027_Python_Avanzado/`) y volcá dentro su estructura de sesiones tal cual.
2. **¿Es material transversal suelto?** → mandalo a su gaveta temática: datos a `06_Datasets`, diapositivas a `07_Presentaciones`, ejercicios a `04_Ejercicios`, exámenes a `11_Evaluaciones`, plantillas a `09_Plantillas`, bibliografía a `10_Referencias`.
3. **¿No sabés todavía dónde va?** → dejalo en `00_Inbox/` y clasificalo después. Nunca lo dejes suelto en la raíz.
4. **¿Es de otra tecnología?** → no va aquí: llevalo a su biblioteca (`git-R`, `git-stata`, `git-spss`, `git-LaTex`, `git-geogebra`, `git-ofimatica`).

---

## ✍️ Convenciones de nombres

- Carpetas de tema: `NN_Tema_Descriptivo` con **dos dígitos** (`01_`, `02_`, … `10_`) para que el orden alfabético sea el correcto.
- Secuencias de clases: `Sesion_NN_...`, `Modulo_NN_...` o `Capitulo_NN_...`.
- Nombres **descriptivos**: nada de `sin titulo`, `nuevo1`, `final final`, `copia de...`.
- Preferí sin tildes ni espacios en nombres nuevos (guiones bajos) para máxima portabilidad.
- Mantené juntos los archivos relacionados (un PDF con su `.tex`, un análisis con su dataset).

---

## 🔒 Reglas de oro (nunca se rompen)

- **Nunca borrar** información. Los duplicados se conservan (a lo sumo van a `99_Historico/`).
- **Separación estricta por tecnología:** aquí solo vive lo propio de Proyectos de Inversión.
- **El origen no manda; el conocimiento sí.**
- **La raíz se mantiene limpia:** solo este README y las gavetas numeradas.

---

_Biblioteca de aprendizaje de Edison Achalma · estructura diseñada para crecer durante décadas._
