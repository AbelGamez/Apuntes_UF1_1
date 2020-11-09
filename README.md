# 1.- Entornos de Desarrollo.
### 1.1-Tipos de software
- **De Sistema** (Sistema operativos,Drivers)
- **De aplicación**(Suite ofimática,Navegador,Edición de imagen.)
- **De desarrollo**(Editores,Compiladores,Inerpretes...)
### 1.2-Relación Hardware-Software
- **Disco duro** Almacena de forma permanente los archivos ejecutables y los archivos de datos.
- **Memoria Ram** Almacena de forma temporal el código binario de los archivos ejecutables y los archivos de datos necesarios.
- **CPU** Lee y ejecuta instrucciones almacenadas en memoria RAM , así como los datos necesarios.
- **E/S** Recoge nuevos datos desde la entrada,se muestran los resultados,se leen/guardan a disco.
### 1.2.1-Códigos fuente,objeto y ejecutable
- **Código fuente** Archivo de texto legible escritorio en un lenguaje de programación
- **Código objeto** (Intermedio) Archivo binario no ejecutable.
- **Código ejecutable** Archivo binario ejecutable.
## 1.3-Ciclo de vida del software
### 1.3.1 Ingeniería de software 
>Disciplina que estudia los principios y metodologías para el desarrollo y mantenimiento de sistemas software. 
- Algunos autores consideran que "desarrollo de software" es un término más apropiado que "ingeniería de software" 
### 1.3.2 Desarrollo de software
### 1.3.3 Fases principales
- **Análisis**
    - Se definien claramente las necesidades a cumplir del software que necesita el cliente y se especifica los requisitos que debe cumplir el software.
        - La especificación de requisitos debe:
            - Ser completa y sin omisiones
            - Ser concisa y sin trivalidades
            - Evitar ambigüedades
            - Evitar detalles de diseño o implementación
            - Ser entendible por el cliente
            - Separar requisitos funcionales y no funcionales
            - Dividir y herarquizar el modelo 
            - Fijar criterios de validación
- **Diseño**
    - Se descompone los elementos  que pueden ser dearrollados por separado
    - Se especifica la interrelacción y funcionalidad de los elementos
    - Las actividades habituales son las siguientes:
      - Diseño arquitectónico
      - Diseño detallado
      - Diseño de datos
      - Diseño de interfaz
- **Codificación**
  - Se escribe el código fuente de cada componente.
  - Pueden utilizarse distintos lengajes informáticos:
    - **Lenguajes de programación :** C,C++,Jaba,Javascript, ...
    - **Lenguajes de otro tipo :** HTML,XML,JSON, ...
- **Pruebas**
  - El principal objetivo de las pruebas debe ser conseguir que el programa funcione incorrectamente para encontrar errores.
  - Deberemos someter al programa al máximo número de situaciones diferentes para asegurarnos de que todo funciona bien .
- **Mantenimiento**
    - Durante la explotación del sistema es necesario realizar combios para ello hay que rehacer parte del trabajo realizado.
    - **Tipos de mantenimiento**
        - **Correctivo:** Se corrigen defectos.
        - **Perfectivo:** Se mejora la funcionalidad
        - **Evolutivo:** Se añade funcionalidades nuevas.
        - **Adaptativo:** Se adapta a nuevos enotrnos.
### 1.3.4  Resultados tras cada fase
- Ingeniería de sistemas: **Especificación del sistema**
- Análisis:**Espacificación** de requisitos del software
- Diseño arquitectónico:**Espacificación** de módulos y funciones
- Codificación:  **Código fuente**
- Pruebas de unidades: **módulos utilizables**
- Pruebas de integración:**Sistema utilizable**
- Pruebas del sistema:**Sistema aceptado**
- Documentación:**Documentación técnica y de usuario**
- Mantenimiento:**Informes de errores y control de cambios**

### 1.3.5 Modelos de desarrollo de software
- Modelos clásicos (predictivos)
    - Modelos en cascada
    - Modelo en V
- modelo de construcción de prototipos
- Modelos evolutivos o incrementales
    - Modelo en espiral (iterativos)
    - Metodologías ágiles (adaptativos)
### 1.3.6 Modelo en cascada
- foto
- Es el modelo con mayor antigüedad
- Identifica las fases principales de desarrollo de software.
- Las dases han de realizarse en el orden indicado.
- El resultado de una fase es la entrada de la siguente fase.
- Es un modelo bastante rígido que se adapta mal al cambio continuo de especificaiones.
- Existen diferentes variantes con mayor o menor cantidad de actividades.
### 1.3.7 Modelo en V
- foto
- Modelo muy parecido al modelo en cascada.
- Visión jerarquizada con distintos niveles.
- Los niveles superiores indican mayor abstracción
- Los niveles inferiores indican mayor nivel de detalle.
- El resultado de una fase es la entrada de la siguiente.
- Existen diferentes variantes con mayor o menor cantidad de actividades.

### 1.3.8 Prototipos
-foto
- A menudo los requisitos no están especificados claramente :
    - Por no existor experiencia previa.
    - Por omisión o falta de concreción del usuario/cliente.
- Proceso:
    - Se crea un prototipo durante la **fase de análisis** y es probado por el usuario/cliente para refinar los requisitos del software a desarrollar.
    - Se repite el paso anterior las veces necesarias.
- Tipos de prototipos:
    - **Prototipos rápidos**
        -  El prototipo puede estar desarrollado usando otro lenguaje y/o herramientas.
        -  Finalmente el prototipo se desecha.
    - **Prototipos evolutivos**
        - Elprototipo está diseñado en el mismo lenguaje y herraminetas de proyecto.
        - El prototipo se usa como base para desarrolllar el proyecto.
###1.3.9 Modelo en espiral
- Desarrollado por Boehm en 1988
- La actividad de **ingeniería** corresponde a las fases de los modelos clásicos: análisis,diseño,codificación...
- En la actividad de **ingeniería** se da gran importanica a la reutulicación de código.
- foto
### 1.3.10 Metodologías ágiles
- Son métodos de ingenierí adel software basados en el desarrollo intertivo e incremental.
- Los requisitos y soluciones evolucionan con el tiempo según la necesidad del proyecto.
- El trabajo realizado mediante la colaboracioón de equipos auto-organizados y multidisciplinarios,inmersos en un proceso compartido de toma de decisiones a corto plazo.
- Las metodologías más conocidas son:
    - **Kanban**
        - También se denomina "sistema de tarjetas".
        - Desarrollado inicialmente por Toyota para la industria de fabricación de productos.
        - Controla por demanda la fabricación de los productos necesarios en la cantidad y tiempo necesarios.
        - Enfocado a entregar el máximo valor para los clientes, utilizando los recursos justos.
    - foto
    - **Scrum**
        - Modelo de desarrollo incremental.
        - iteraciones (**sprint) regulares** cada 2, 3 o 4 semanas.
        - Al principio de cada iteración se establecen sus **objetivos proorizados (sprint backlog**)
        - Al final cada iteración se obtiene una **entrega parcial utilizable por el cliente.**
        - Existen reuniones diarias para tratar la marcha del sprint.
        - **Roles principales**
            - **Product Owner** Es "La voz del cliente".Define criterios de aceptación y asegura de que se cumplan.
            - **Scrum Master** Asegura que se sigue la metodología Scrum.Motiva y facilita el trabajo del equipo.c
            - **Team** Equipo de desarrollo auto-organizado y multifuncucional.Entre 6 y 10 miembros.
        - **Artefactos**
            - **product Backlog** Lista ordenada con los requisitos del producto.
            - **Sprint Backlog** Lista de requisitos scados del backlog para su desarrollo durante el sprint.
            - **Incremento** Estado del producto después de cada sprint.
        - **Eventos**
            - **Sprint** Evento principal, que contiene al resto de eventos.Durección máxim: 1 mes.
            - **Spring Planning** Reunión inicial donde se planifica el trabajo del Sprint.Dureción máxima:8 horas.
            - **Daily Scrum** Reunión diaria de puesta en común sobre la marcha del sprint.Duración máxima: 15 minutos.
            - **Scrum Review** Reunión final para evaluar el incremento obtenido. Duración máxima: 4h .
            - **Scrum Retrospective** Reuniín final para evaluar la correcta aplicación de la metodología Scrum. Duración máxima: 3 horas.
        - foto
    - XP (eXtreme Programming)
        - **Valores**
            - **Simplicidad**
            - **Comunicación**
            - **Retroalimentación**
            - **Valentía o coreje**
            - **Respeto o humildad**.
        - **Características**
            - Diseño sencillo
            - Pequeñas mejoras continuas
            - Pruebas y refactoricación
            - Integración continua
            - **Programación por parejas**
            - **El cliente se integra en el equipo de desarrollo**
            - Propiedad del código compartida
            - Estándares de codificación
            - 40 horas semanales
### 1.4 Lenguajes de programación


