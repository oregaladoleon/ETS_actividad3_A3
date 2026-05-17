# Etapas del desarrollo de software
> Autor: Óscar Regalado León.  
> Fecha: Mayo 2026.
---
## Objeto del documento:
Este documento responde a la actividad marcada en el módulo de Entornos de Desarrollo, se especifican las definiciones de las diferentes etapas del proceso de elaboración de un software.
## Definiciones:
### 1. Análisis de requisitos:
Podemos identificar una fase previa, denominada de planificación que establece los objetivos y el alcance del proyecto de desarrollo de software.
Luego, durante la fase de análisis, el equipo de desarrollo recopila y analiza la información sobre los **requisitos** del proyecto. Gracias a este análisis, el equipo puede avanzar en el trabajo que comenzó en la fase de planificación y pasar de una idea general a un plan de implementación práctico.
#### 1.1 Funcionales:
Definen los servicios, funciones o comportamientos específicos que el sistema debe ejecutar. Describen la interacción entre el sistema y su entorno.
#### 1.2 No funcionales:
Especifican criterios de operación, propiedades emergentes y restricciones del sistema. Definen cualidades de calidad como el rendimiento, la seguridad, la fiabilidad y la usabilidad.

![Análisis de Requisitos](https://cms.boardmix.com/images/es/articles/examples/sistema-de-restaurante.png)

### 2. Diseño:
En la fase de diseño, los requisitos abstractos se transforman en una arquitectura técnica tangible. Se define la estructura del software, la arquitectura del sistema, el modelo de datos (esquemas de bases de datos), las interfaces de usuario (UI/UX) y las interacciones entre los diferentes módulos o componentes utilizando estándares como los diagramas UML.

![Diseño de Software](https://www.justinmind.com/wp-content/webp-express/webp-images/uploads/2018/06/justinmind-user-flow-sequence-diagram.png.webp)

### 3. Codificación y compilación:
Esta etapa consiste en traducir las especificaciones de diseño en código fuente ejecutable utilizando un lenguaje de programación (como Java, Python o C++). Adicionalmente, se realiza el proceso de **compilación** (o interpretación), que traduce este código de alto nivel legible por humanos a un lenguaje máquina que el hardware del ordenador pueda procesar directamente, detectando errores de sintaxis en el proceso.

![Codificación y compilación](https://www.calamoycran.com/wp-content/uploads/Blog-Procesamiento-del-lenguaje-natural-%C2%BFQue-es-Python-y-por-que-te-interesa-aprenderlo.jpg)
### 4. Pruebas:
La fase de pruebas tiene como finalidad asegurar la calidad del software identificando fallos, bugs o desviaciones respecto a los requisitos iniciales antes de que el producto sea entregado al usuario final.
#### 4.1 Unitarias:
Se centran en verificar de manera aislada el correcto funcionamiento de una unidad mínima de código fuente (una función, un método o una clase específica). Suelen automatizarse con herramientas como `pytest`.
#### 4.2 De integración:
Evalúan cómo interactúan y se comunican entre si los diferentes módulos o unidades de código previamente probados de forma individual, garantizando que el ensamblaje de las piezas funciona sin conflictos de compatibilidad ni pérdida de datos.

![Pruebas de Software](https://devits.io/wp-content/uploads/2025/06/software-testing.webp)
### 5. Explotación:
La explotación o despliegue (Deployment) consiste en poner el software a disposición de los usuarios finales en su entorno de producción real. Incluye actividades de configuración de servidores, instalación en la nube (AWS, Azure, etc.), aprovisionamiento de bases de datos y la monitorización inicial para asegurar la estabilidad operativa del entorno activo.

![Explotación y Servidores](https://static.platzi.com/media/user_upload/FAS_DiagramaEjemplo-eda07055-ccfb-441f-a85f-5588db3f486f.jpg)

### 6. Mantenimiento:
Una vez desplegado, el software entra en un ciclo continuo de mantenimiento para asegurar su ciclo de vida útil. Existen cuatro tipos principales de acciones:
* **Correctivo:** Corrección de fallos y bugs reportados por los usuarios.
* **Evolutivo:** Incorporación de nuevas funcionalidades solicitadas con el tiempo.
* **Adaptativo:** Modificaciones para que el sistema funcione en nuevos entornos (nuevos sistemas operativos, actualizaciones de hardware).
* **Perfectivo:** Mejoras internas para optimizar el rendimiento o la mantenibilidad sin cambiar su comportamiento externo.

![Mantenimiento de Software](https://www.evaluandosoftware.com/wp-content/uploads/2020/12/GSA-Mantenimiento-de-software-grafico-05.jpg)

### 7. Documentación. Tipos de documentos:
La documentación recoge toda la información generada a lo largo del ciclo de vida del proyecto. Es vital para garantizar que el sistema sea entendible, transferible y fácil de mantener en el futuro.

1. **Documentación de Requisitos (SRS / ERS):** Especificación formal de lo que el sistema debe hacer.
2. **Documentación Técnica / Arquitectura:** Diagramas del sistema, diccionarios de datos, diseño de la base de datos y documentación de APIs (como Javadoc o Swagger) destinada a desarrolladores.
3. **Documentación de Usuario:** Manuales de instalación, guías de usuario y preguntas frecuentes (FAQs) destinadas a los clientes finales.
4. **Documentación de Gestión de Proyecto:** Cronogramas, presupuestos, metodologías (Scrum/Agile) y actas de reuniones.

![Documentación Técnica](https://www.northware.mx/wp-content/uploads/2021/04/especificacion-de-operacion-y-funcionalidad-diseno-de-software-a-detalle-1030x781.png)

### 8. Vídeo resumen:
En el siguiente vídeo se hace una revisión general de las diferentes etapas:  
[![Aprende qué es Desarrollo de Software y sus etapas]](https://www.youtube.com/watch?v=s5ABwHaN7as&t=520s)
