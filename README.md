# Lenguaje de alto nivel con sistema de tipos para las tecnologías Docker y Kubernetes.

## Descripción

En infraestructura, con la llegada de la tecnología Docker y los contenedores, cada vez más los "servidores" y sus aplicaciones son objetos definidos virtualmente y configurados a través de un lenguaje que provee una capa de abstración sobre qué es es una máquina física, qué debe contener, por qué mecanismos se comunica, etc. 

Docker y Kubernetes son tecnologías basadas en esta idea. Ahora, esos lenguajes que especifican la infraestructura son muy primitivos, donde si existe un tabulador de más cambia la su semántica. Más aún, son lenguajes sin tipos. Lo que se traduce en la posiblidad de declaraste algo sin sentido, que aborta con error al momento de ejecutar (es decir, al momento de construir la infraestructura). 

## Objetivos Generales

El proyecto en una frase es diseñar un lenguaje bien hecho, con un sistema de tipos y varias validaciones estáticas, que detecte ciertos errores en tiempo de compilación, y que luego compile a estos lenguajes primitivos y orientas a máquinas (yaml, dockerfile, etc). 

Los entregables del proyecto de grado serán:
- Una especificación de un lenguaje de alto nivel con sistema de tipos para describir una infraestructura que transpile a los lenguajes especificados por las tecnologías Docker y Kubernetes.
 - El código fuente de la herramienta de generación. 
 - Un informe describiendo la arquitectura, interfaces y guía de instalación, configuración y utilización de la misma. También una comparación exhaustiva enumerando los errores que son detectados en tiempo de compilación y no en tiempo de ejecución, diferenciando cuáles ya eran detectados por las herramientas provistas por éstas tecnologías y cuáles no.

## Requisitos

Las siguientes habilidades son requeridas:
- Conocimientos básicos de teoría de lenguajes y compiladores.
- Habilidades de programación
Cursos o experiencia previa en las siguientes áreas temáticos NO es requerida, pero se considera un valor adicional:
- Lenguajes de Programación
- Teoría de la Computación
    
## Oferta

Se ofrece ser parte de un proyecto de investigación en innovación en curso sobre tecnologías de punta en infraestructura informática, en el cual participan universidades y empresas privadas, aportando resultados que serán divulgados internacionalmente. 

El trabajo se desarrollará en los locales de ICT4V, un centro tecnológico situado en el LATU en el cual participan las cuatro universidades uruguayas, empresas privadas y agencias de gobierno. Por más información: http://www.ict4v.org.
Posibilidades de financiamiento a través de becas otorgadas por ICT4V.
