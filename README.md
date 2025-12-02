Este repositorio contiene los modelos de simulación en MATLAB y el código fuente de las estrategias de control evaluadas para un sistema de páncreas artificial.
El estudio se centra en un enfoque bioinspirado basado en la Teoría de Dinámicas Poblacionales (DP) para la regulación de la glucosa en pacientes con Diabetes Mellitus tipo 1 (DM1). 
El objetivo es comparar el desempeño clínico y la eficiencia computacional de la estrategia DP contra controladores tradicionales.


Contribución Principal
La principal contribución de este trabajo es la implementación de una estrategia de control novedosa basada en dinámicas poblacionales. 
Esta estrategia modela la interacción cooperativa entre glucosa e insulina como una competencia entre especies biológicas , utilizando una modificación de las ecuaciones de Replicator Dynamics.
El controlador de Dinámicas Poblacionales fue diseñado para ofrecer una regulación adaptativa y lograr un uso estándar de la insulina con una menor carga computacional, comparado con los controladores tradicionales estudiados.

Modelos Fisiológicos
Para el diseño y la validación de las estrategias de control, se emplearon dos de los modelos más usados en la literatura para describir el sistema glucosa-insulina:
Modelo Modificado de Bergman: Este modelo describe la dinámica de la glucosa y la acción retardada de la insulina en los tejidos periféricos.
Fue seleccionado por su simplicidad estructural y su capacidad para capturar los mecanismos esenciales del metabolismo con un número reducido de estados.
Modelo de Hovorka: Este modelo constituye una representación fisiológica más detallada del metabolismo de la glucosa en pacientes con DM1, siendo ampliamente utilizado como estándar de simulación.

Metodología y Escenarios de Simulación
El desempeño de los controladores se evaluó en seis escenarios de simulación a lo largo de 24 horas para analizar el comportamiento bajo diferentes condiciones fisiológicas y clínicas en pacientes con DM1:
Estándar: Simula una jornada típica con 3 comidas principales de CHO moderado (40g, 60g, 50g).
Ayunas: Simula 24 horas sin ingesta de carbohidratos para evaluar la acción basal.
Ingesta Alta en CHO: Simula 3 comidas principales con ingesta alta de carbohidratos (70g, 80g, 90g) para evaluar la compensación ante grandes perturbaciones.
Ingesta de Refrigerios: Simula ingestas adicionales de 20g CHO entre comidas principales.
Hiperglucemia Severa: Evalúa la capacidad del controlador partiendo de una glucosa inicial de 300 mg/dL.
Hipoglucemia Severa: Evalúa la seguridad del sistema partiendo de una glucosa inicial de 50 mg/dL.

Autores y Contacto
Manuela María Muriel Tobar - murieltmanu@udenar.edu.co 
Germán Darío Obando Bravo - gdobando@udenar.edu.co 
David Andrés Ojeda Guzmán - daojedag@udenar.edu.co 
Andrés Fernando Arciniegas Mejía - arciandres@gmail.com



