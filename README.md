# Ruta Agéntica · Fundamentos de IA

**Una guía personal, gratuita y autoguiada para comprender y practicar los fundamentos del desarrollo de software con agentes de inteligencia artificial.**

La propuesta acompaña a personas con conocimientos técnicos básicos, incluso si no programan habitualmente. El objetivo es aprender a plantear una necesidad, trabajar con un agente de IA y comprobar el resultado antes de aceptarlo. No pretende sustituir una formación completa de programación ni certificar competencias profesionales.

## Abrir la formación

1. Descarga `index.html` o clona este repositorio.
2. Abre el archivo en un navegador actual. El contenido y las visualizaciones están integrados en el HTML; para leerlo no necesitas un servidor ni acceso a Internet.
3. Empieza por el **capítulo cero**, que explica el propósito, los conceptos iniciales y las herramientas.
4. Selecciona la plataforma y la metodología cuando llegues a esa etapa. Continúa a tu ritmo; las actividades y preguntas permiten registrar el avance, pero no bloquean capítulos.

> **Nota:** para realizar las prácticas de desarrollo sí necesitarás instalar y configurar algunas herramientas. Determinados enlaces y servicios externos (por ejemplo, documentación oficial o conexiones MCP) requieren Internet, cuentas o permisos propios.

## Qué aprenderás

El itinerario combina explicaciones, ejemplos interactivos y un proyecto didáctico progresivo llamado **MiniSolicitudes**. Incluye:

- Modelos de IA, límites de sus respuestas e instrucciones comprobables.
- Preparación del entorno, nociones básicas de Git y desarrollo guiado por especificaciones (**SDD**, OpenSpec o Spec Kit).
- Uso de agentes, skills y subagentes, reglas de seguridad y hooks.
- Diseño de un harness de proyecto, grafos de capacidades y organización del conocimiento.
- Integraciones mediante **MCP** y recuperación de información mediante **RAG**.
- Flujos agénticos y orquestación, puntos de control (**quality gates**), evaluaciones (**evals**) y evidencias.
- Diagnóstico, un laboratorio integral de aplicación y recursos para seguir explorando.

La guía ofrece rutas adaptadas a GitHub Copilot, OpenAI Codex y Claude Code. OpenCode se menciona como opción de configuración dentro de VS Code. **No requiere que el estudiante utilice todas las herramientas:** una parte importante del aprendizaje consiste en elegir solo las necesarias.

## Cómo se guarda el progreso

Los avances y las respuestas se guardan **localmente en el navegador** mediante almacenamiento del dispositivo. El HTML no incorpora un servicio de cuentas ni un backend para compartir el progreso. Cambiar de navegador, limpiar los datos del sitio o abrir una copia con un origen distinto puede hacer que ese progreso no aparezca.

La formación incluye una opción para reiniciar el avance. Los ejemplos, diagramas y simuladores integrados son recursos didácticos: no deben interpretarse como ejecución real de agentes o verificación de un sistema de producción.

## Estructura del repositorio

```text
ruta-agentica-fundamentos-ia/
├── index.html    # Guía interactiva y autocontenida
├── README.md     # Descripción y uso
└── LICENSE.md    # Condiciones de uso y redistribución
```

No se incluyen en este repositorio notas de desarrollo ni documentación editorial privada.

## Proponer una mejora o enviar feedback

Si has completado parte del recorrido, encuentras una explicación confusa o detectas un fallo, puedes [abrir un issue](https://github.com/joseangelsosa/ruta-agentica-fundamentos-ia/issues). Resulta especialmente útil que indiques el capítulo, la etapa, la herramienta que estabas usando y qué esperabas que ocurriera. **No compartas claves API, secretos, información personal ni código confidencial.**

Las propuestas de mejora son bienvenidas, pero su incorporación y redistribución deben respetar la licencia del material.

## Autoría y referencias

**José Ángel Sosa Ramírez** es el autor de la **propuesta y del planteamiento de la experiencia de aprendizaje**: su organización, estructura y forma de presentación. Los materiales didácticos han sido elaborados con **ChatGPT (OpenAI), coautor de los textos**. Los conceptos y las tecnologías explicados no son creaciones exclusivas de los autores de la guía.

- [LinkedIn de José Ángel Sosa Ramírez](https://www.linkedin.com/in/joseangelsosa/)
- [GitHub y repositorios](https://github.com/joseangelsosa?tab=repositories)

La guía incluye enlaces a documentación oficial y referencias formales de las herramientas, agrupadas en el módulo final. Las marcas, productos y sitios enlazados pertenecen a sus respectivos titulares.

## Licencia

El **material didáctico original y la presentación de Ruta Agéntica** se ofrecen bajo **[Creative Commons Atribución-NoComercial-SinDerivadas 4.0 Internacional (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.es)**, hasta donde exista un derecho de autor aplicable sobre dicho material.

Puedes descargar y compartir la guía **sin modificarla, sin fines comerciales y con atribución**. **No se autoriza la redistribución de adaptaciones** (incluidos cambios de logotipo, autoría o identidad visual) sin permiso adicional. Esta licencia **no garantiza una prohibición absoluta de uso dentro de empresas**, porque «NoComercial» describe la finalidad del uso. Tampoco modifica los derechos y licencias de software, marcas o documentación de terceros.

Consulta [LICENSE.md](LICENSE.md) para la declaración completa de licencia y su enlace oficial.

---

**Versión de la guía:** 0.23.1 · **Idioma:** español · **Formato:** HTML autocontenido.