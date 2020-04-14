# PP III
Presentación general del proyecto
Dada a que en los últimos ciclos lectivos el Instituto de Formación Técnica Superior Nº 11, ha detectado un aumento sostenido en la cantidad de alumnos matriculados.
Se planteó la necesidad de optimizar los procedimientos actuales de registro diario de asistencias y el de comunicación de resultados de los exámenes a los alumnos.
Para el registro de asistencia actualmente posee un sistema manual, al que destina entre la mitad y la totalidad del personal disponible, debiendo éste tener que recorrer las aulas de ambas plantas del edificio. El proceso manual tiene como desventaja la alta posibilidad de errores.
El objetivo del proyecto es brindarle una solución que automatice ambos procesos, liberando al personal para que pueda desarrollar el resto de tareas administrativas. También se proyecta ofrecer la posibilidad para que se puedan realizar consultas de calificaciones durante las 24hs, todos los días del año.
Las autoridades del IFTS Nº 11 deben dar cumplimiento a diversas resoluciones y reglamentaciones que establecen la obligatoriedad de la identificación de los alumnos en condición de presentes dentro del establecimiento, mientras transcurra el horario de clases.
Esta condición aplica para las siguientes situaciones:
•	Obtención de la regularidad de cada materia
•	En caso de un siniestro es exigido por los seguros tomados por el GCBA
•	En caso de una evacuación poder contar con una lista de presentes
•	En caso de una inspección o auditoría también poder contar con una lista de presentes
La APP, cumplirá los cuatro puntos anteriores, además de permitir a los alumnos realizar consultas de notas todos los días del año y en cualquier horario.
Definición de alcance y los límites del proyecto
Limites:
•	Limite Inicial: Completar los datos del Usuario. (Al ingresar en el dispositivo a utilizar.)
•	Límite Final Modulo Presentismo: Registrar el Presente.
•	Límite Final Modulo Notas: Visualizar Notas.
Alcances:
•	Valida que el Usuario sea Alumno del IFTS 11(Existencia del Alumno en la Base)
•	No se realiza Alta, Baja ni Modificación de Alumnos. Esta tarea es exclusiva del Plantel Administrativos. La APP solo toma los datos de la Base. 
•	No se realiza Alta, Baja ni Modificación de Docentes. Esta tarea es exclusiva del Plantel Administrativos. La APP solo toma los datos de la Base. 
•	No se realiza Alta, Baja ni Modificación de Administrativos. Esta tarea es exclusiva del Plantel Administrativos. La APP solo toma los datos de la Base.  
•	Valida el horario del presente ( Lunes a Viernes 18 a 22 Hs - Identifica Clases Virtuales y Feriados) 
•	Registra Ingreso y Egreso en un anexo a la Base en tiempo real.
•	Proporciona listado Parcial de Alumnos que ingresaron al Instituto en horarios determinados. 
•	No se realiza Alta, Baja ni Modificación de Materias. Esta tarea es exclusiva del Plantel Administrativos. La APP solo toma los datos de la Base. 
•	El Alumno puede consultar todas las Notas de las Materias que pertenecen a la Carrera.
•	Indica Finales Pendientes.
Para una Segunda Etapa se evalúan las siguientes funcionalidades: 
•	El Profesor podrá Consultar las Inasistencias por Alumno y recibir un aviso en el caso de que el mismo no haya asistido 4 clases seguidas. 
•	El Alumno podrá visualizar las Fechas de Finales y Vencimiento de las materias que debe rendir.
•	El Profesor podrá visualizar cuantos alumnos se encuentran inscriptos a los finales por materia. 
Análisis de los requerimientos establecidos en la lista inicial
•	La aplicación podrá ser instalada en dispositivos Android e IOS
•	Al abrir por primera vez la misma se le solicitara los datos de autenticación del alumno, esto sucederá por única vez mientras no desinstale la app.
Una vez autenticado el alumno podrá realizar las siguientes acciones:

•	En la pantalla principal, presionar el botón “ingreso” al ingresar al IFTS 11, de esta manera registra fecha y hora de ingreso al establecimiento.
•	En la pantalla principal presionar el botón “salida” al retirarse del mismo, registrando asi fecha y hora de egreso del establecimiento.
•	Si selecciona el botón notas en la pantalla principal se mostrara las notas de las materias en curso y las ya cursadas. Siendo esta pantalla de carácter informativo.
