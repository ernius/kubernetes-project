# Typed Kubernetes.

## Descripción

En infraestructura, con la llegada de la tecnología Docker y los contenedores, cada vez más los "servidores" y sus aplicaciones son objetos definidos virtualmente y configurados a través de un lenguaje que provee una capa de abstracción que permite describir qué es es una máquina física, qué bibliotecas debe contener, por qué mecanismos se comunica con otras máquinas, etc. Docker y Kubernetes son tecnologías basadas en esta idea. En estas tecnologías, la infraestructura es algo que se especifica y se programa a través de lenguajes de descripción de contenedores como Dockerfile, para luego ser desplegada, controlada y gestionada mediante orquestadores como Kubernetes. El objetivo de estas tecnologías es ofrecer sistemas resilientes e interoperables, distribuidos en una nube de servidores físicos que proveen recursos elásticos y escalables (esto es, extensibles a demanda y en tiempo de ejecución), que a la vez encapsulen y sigan patrones para diferentes tipos de servicios.

Sin embargo, estos lenguajes de especificación de infraestructura se basan en archivos YAML y carecen de parsers robustos, sistemas de tipos o analizadores estáticos. Como resultado, simples errores sintácticos en la definición de la infraestructura como la introducción de un tabulador de más o la incorrecta ubicación de una estructura gramatical en el archivo que la especifica pueden resultar en errores de ejecución al momento de desplegar la infraestructura. De manera similar a lo que ocurre con los lenguajes de programación clásicos, para los ingenieros de DevOps resulta difícil identificar el origen de esos errores en tiempo de ejecución y remontar hasta el error de especificación que los produjo.

## Objetivos Generales

El objetivo principal del proyecto es diseñar un sistema de tipos para el lenguaje Dockerfile (descripción de imágenes de contenedores) y para Kubeconfig (descripción de clusters en Kubernetes). Este sistema de tipos será la base de un conjunto de herramientas de análisis estático de estos lenguajes, como por ejemplo parsers robustos y algoritmos de inferencia o verificación de tipos. Estas herramientas detectarán errores en tiempo de compilación y luego eventualmente compilarán a lenguajes de más bajo nivel, como YAML.

Como un objetivo secundario y a más largo plazo del proyecto marco, se estudiará también cómo demostrar la corrección del sistema de tipos, esto es, como asegurar que todo archivo Dockerfile o Kubeconf que pase las verificaciones estáticas permite desplegar la infraestructura definida sin errores.

Los entregables del proyecto de grado serán:
- Una especificación de un lenguaje de alto nivel con sistema de tipos para describir una infraestructura que pueda ser compilado a los lenguajes especificados por las tecnologías Docker y Kubernetes.
- El código fuente del compilador, incluyendo parser, verificador de tipos y generador de salida.
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

El trabajo se desarrollará en ORT y en los locales de ICT4V, un centro tecnológico situado en el Parque del LATU en el cual participan las cuatro universidades uruguayas, empresas privadas y agencias de gobierno. Por más información: http://www.ict4v.org. Posibilidades de financiamiento a través de becas otorgadas por ICT4V.

