# Carpeta Prana

Entregables y material de trabajo del proyecto social universitario con **PRANA Incubadora de Empresas Culturales e Industrias Creativas** (Bogotá), desarrollado en el periodo académico 2026-3 de Ingeniería de Sistemas, Pontificia Universidad Javeriana.

## Contexto

PRANA acompaña a emprendedores, artistas, gestores culturales y empresas en etapa temprana de las industrias culturales y creativas (audiovisual, música, editorial, diseño, moda, artes escénicas, videojuegos y animación). El proyecto se divide en dos líneas de trabajo:

1. **Asesoría técnica – Ecosistema digital y posicionamiento en buscadores.** Diagnóstico y rediseño del sitio web `pranainc.org`, su arquitectura de páginas, el contenido de sus secciones y la estrategia de posicionamiento (SEO).
2. **Analítica de la incubadora.** Tablero de indicadores (KPIs) del programa de incubación, con diagnóstico y priorización de casos.

Las etapas del trabajo siguen el backlog del proyecto (Fase 3, Etapa 3: arquitectura y contenido). Los documentos hacen referencia a las tareas numeradas de ese backlog.

## Contenido de la carpeta

| Archivo | Tipo | Qué es | Para qué sirve |
|---|---|---|---|
| `DocumentoPrana_corregido.pdf` | PDF (10 págs.) | Documento formal del proyecto social universitario: datos de los estudiantes, de la organización (PRANA), del proyecto y del interlocutor. | Ficha de entrega del proyecto a la Facultad de Ingeniería (corregida). Describe la línea de acción (asesoría técnica), el título del proyecto y el alcance: ecosistema digital y posicionamiento en buscadores. |
| `webPrana.pdf` | PDF (4 págs.) | **Diagnóstico técnico** del sitio `pranainc.org` (agosto 2026). Incluye la auditoría manual de la navegación, la jerarquía de contenido, los enlaces y los llamados a la acción. | Etapa 1 del proyecto. Lista qué funciona bien (home clara, botón de WhatsApp, diseño consistente, sección de aliados) y los hallazgos que se deben corregir, cada uno con su página e impacto. Es la base del backlog de tareas. |
| `anidacion.pdf` | PDF (4 págs.) | **Anidación y estructura de páginas** del sitio (tarea 11 del backlog). | Define cómo se agrupan las páginas en niveles. Propone reorganizar el menú plano actual (Inicio, Nosotros, Silver Economy, Servicios, ESAL, Emprender Futuro), que mezcla programas con servicios. Es la estructura sobre la que se redactan los contenidos. |
| `nosotros_prana.pdf` | PDF (2 págs.) | **Estructura y contenido de la página “Nosotros”** (tarea 13 del backlog). | Detalla los ocho bloques de la página (encabezado, narrativa, trayectoria por años, portafolio, aliados, etc.), el texto propuesto para cada uno y lo que debe validarse con el director ejecutivo antes de implementarlo. |
| `PRANA_Base_Dashboards_v5.xlsx` | Excel (11 hojas) | **Tablero de indicadores** del programa de incubación (versión 5). | Analítica descriptiva y operativa. Incluye el dashboard principal con filtro por año, los gráficos de volumen, resultados, finanzas y perfil de emprendedores, las metas y semáforos (`KPIs_y_Metas`), la calidad de datos y el diagnóstico con priorización de casos. |

### Detalle de las hojas del Excel

| Hoja | Función |
|---|---|
| `Dashboard` | Tablero principal: tarjetas de resumen y gráficos por año, sector, género, estado de matrícula, edad y nivel de formación. |
| `Dashboard_G2_G6` | Diagnóstico de desviaciones (Guía 2) y priorización operativa basada en reglas (Guía 6): puntaje por caso y niveles de prioridad alta, media y baja. |
| `KPIs_y_Metas` | Indicadores clave y OKRs (Guía 5): línea base (promedio de 3 años previos), valor del año y meta, con semáforo de cumplimiento. |
| `Calidad_Datos` | Reglas de validación de los datos (Guía 6), con cumplimiento global y reglas en rojo o verde. |
| `Modelo_Datos` | Modelo de datos (Guía 7): entidades del negocio, relaciones y guía de uso del libro. |
| `Estudiantes` | Registro de emprendedores: edad, rango de edad, género, nivel educativo, sector, estado frente a Fondo Emprender y fondos obtenidos. |
| `Matriculas` | Inscripciones a cursos: fecha, canal, ciudad, estado de matrícula, módulo máximo alcanzado, asistencia y calificación. |
| `Finanzas` | Transacciones por año (ingresos, por ejemplo del Curso Plan de Negocios) y montos. |
| `FondoEmprender` | Ganadores del Fondo Emprender: convocatoria, año de inicio, año de fin de ejecución y monto obtenido. |
| `Resumen_Anual` | Resumen por año: inscritos, finalizados, retirados, ganadores, recursos apalancados, ingresos y su relación por inscrito. |
| `Calculos_Dashboard` | Cálculos auxiliares que alimentan los gráficos del dashboard. No se debe editar. |

## Cómo usar el tablero

- Los datos se escriben **solo** en las hojas `Estudiantes`, `Matriculas`, `Finanzas` y `FondoEmprender`. Las demás hojas se calculan solas.
- Use las listas desplegables para llenar las columnas; los códigos (por ejemplo, `EST080`) se mantienen tal cual.
- Use la lista **Año** en la hoja `Dashboard` para filtrar las tarjetas y los gráficos de sector, género y estado de Fondo Emprender. Los gráficos por año siempre muestran la serie completa.
- Las cifras se actualizan solas al cargar datos nuevos en las hojas `Estudiantes`, `Matriculas`, `Finanzas` y `FondoEmprender`.
- Para que los gráficos de perfil se llenen, complete las columnas **Edad** y **NivelEducativo** de `Estudiantes` (tienen listas desplegables).
- El año 2026 es un año parcial.
- Los datos personales (nombres, documentos y contactos) **no** están en este archivo; se gestionan por separado de forma confidencial.

## Reglas de negocio usadas en el tablero

- **Fondo Emprender:** requiere 18 años o más, y nivel de formación profesional, especialización, maestría o doctorado. Bachiller, técnico y tecnólogo quedan como “No aptos”.
- Si faltan la edad o el nivel educativo, el estudiante aparece como “Falta dato”.
- Rangos de edad: 18–25, 26–40 y 41–60.

## Notas

- Los archivos `.DS_Store` y los archivos temporales de Excel (`~$…`) no se incluyeron; son archivos auxiliares del sistema.
- Los PDFs son documentos de trabajo; las cifras y propuestas de contenido deben validarse con el equipo de PRANA antes de implementarse.
