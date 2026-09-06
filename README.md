# AE1 - Ingeniería de Requerimientos
**ESCENARIO 4 – "Un equipo de desarrollo trabaja durante varios meses en un sistema de gestión 
académica sin mantener reuniones periódicas con los usuarios finales".**

**Sistema principal:** Sistema de gestión académica. Dicho sistema sirve para digitalizar, organizar y administrar todo el funcionamiento de la universidad, encargándose se gestionar trámites de inscripción de los alumnos, cobro de cuotas, registro de las notas de los exámenes y crear informes para las autoridades de la institución.

**Subsistemas:** Son módulos dentro del programa principal, donde cada uno se encarga de realizar un grupo de tareas especificas de la organización.
**Subsistema de inscripciones y matriculación:** Gestiona las inscripciones y alumnos a carreras, cursadas, materias y comisiones.
**Subsistemas de actas y calificaciones:** Administra la carga de notas, cursadas y exámenes finales.
**Subsistema de gestión económica:** Controla el cobro de cuotas, matrículas y aranceles institucionales.
**Subsistema de comunicación y notificaciones:** Maneja la distribución de avisos y novedades hacia la comunidad educativa.
**Subsistema de reportes:** Genera informes estadísticos y métricas académicas para coordinadores de carreras y directivos.

**Componentes:** Son partes específicas del software ubicados dentro de los subsistemas. Pueden ser una herramienta, pantalla o funciones concretas de código que realizan una tarea puntual.
**Módulo de carga y consulta de notas:** Permite a los docentes ingresasr a las calificaciones de parciales o exámenes finales y a los alumnos consultar con su historial académico.
**Motor de generación de actas:** Se encarga de procesar, formatear y cerrar los documentos oficales.
**Interfaz de pago:** Conecta el sistema con la plataforma externa para procesar los cobros de matrículas y cuotas.
**Panel de coordinación de carreras:** Muestra métricas e informes visuales para que los directivos y coordinadores monitoreen el estado académico.
**Módulo de autogestión para alumnos:** Interfaz donde el estudiante realiza sus trámites, como inscribirse a materias.
**Módulo de notificaciones:** Se encarga de enviar alertas automáticas de eventos específicos.

**Limite:** Es la línea invisible que separa lo que está dentro y fuera del software.
**Dentro del límite:**
Gestión de inscripciones a carreras, materias y comisiones.
Carga de notas, generación de actas de examen y registro de historial académico.
Cálculo de cuotas, matrículas y emisión de deudas de los alumnos.
Envío de avisos y la creación de reportes y estadísticas para los directivos.

**Fuera del límite:**
Pasarelas de pago externas: El sistema calcula la cuota, pero el procesamiento del dinero y el cobro en sí lo hace una plataforma bancaria externa.
Servidores e infraestructura física: Las computadoras físicas o la nube donde se aloja el software.

**Ambiente:** Son los elementos que se encuentran fuera de límite del software, pero que influyen directamente en como se debe diseñar, como se usa o que requerimientos debe cumplir para funcionar bien en la vida real.
**Usuarios de la institución**: Alumnos, docentes, personal administrativo y directivos que interactúan diariamente con la plataforma.
Infraestructura tecnológica y hardware: Computadoras de la universidad, dispositivos de los usuarios, la red interna y los servidores en la nube donde corre el sistema.
**Sistemas externos:** Las plataformas bancarias/pasarelas de pago, el aula virtual y la biblioteca.
**Usuarios o actores involucrados:** Son todas las personas o roles que interactuan directamente con el programa o que se ven afectados por su funcionamiento.
**Estudiantes:** Utilizan el sistema para inscribirse a materias o examens, consultar sus notas, pagar cuotas y recibir avisos.
**Docentes:** Utilizan la plataforma para cargar calificaciones, tomar asistencia y cerrar actas de cursada o examen.
Personal administrativo: Gestionan las actas, habilitan comisiones, resuelven trámites de alumnos y verifican pagos.
**Directivos:** consultan reportes, estadísticas y métricas para la toma de decisiones institucionales. 
**Equipo de desarrollo de software:** Los analistas y programadores que diseñan, construyen y mantienen el sistema.

**Características relevantes del software:**
**Evolución constante:** El software académico no es estático, ya que los procesos universitarios (fechas de exámenes, cierres de actas, períodos de matriculación) cambian en base a el calendario institucional.
**Complejidad:** El sistema de gestión academica no funciona de manera aislada, sino que integra múltiples subsistemas internos y depende de integraciones con plataformas externas(pasarelas de pago biblioteca, digital, campus virtual).
**Intangibilidad de los requerimientos:** No son elementos físicos que se puedan ver o tocar, sino ideas que tienen los usuarios sobre lo que va a hacer el sistema. En este escenario, la falta de comunicación directa genera que esas necesidades reales permanezcan invisibles para el equipo de desarrollo al no tener una comunicación fluida para extraer y validar esa información, por lo que los programadores terminan construyendo el sistema basándose en suposiciones, lo que provoca una desalineación funcional entre el producto entregado y los requerimientos reales de la institución, haciendo que el software no responda a los procesos previstos por la universidad.
**El software se deteriora:** El software no sufre un desgaste físico como el hardware, pero se deteriora cuando se desincroniza de la realidad operativa. Al no mantener una comunicación continua con la universidad, el sistema de gestión académica pierde utilidad práctica para los usuarios y se llena de parches o funciones que son inservibles. 

**Problemas relacionados con el desarrollo del sistema:**
**Falta de comunicación:** El equipo de desarrollo dejó de interactuar con los actores clave (alumnos, administrativos, docentes), programando en función de suposiciones y no de la realidad operativa.
**Impresición en los requerimientos:** Al no existir actividades continuas de obtención y validación, los requerimientos quedaro incompletos o mal interpretados.
**Generación de un producto inviable:** El código se desarrolla, pero el software no cumple con las expectativas ni resuelve las necesidades de la universidad, provocando resistencia al uso, reprocesos y pérdida de recursos.
**Degradación funcional prematura:** El sistema se vuelve obsoleto antes de ser utilizado, porque la falta de comunicación constante con el cliente no permite recibir una retroalimentación durante el proyecto lo que impide ajustar el código a lo que ellos realmente neceistan en su trabajo diario.




