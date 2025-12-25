# Glosario de GenAI & Data Governance

Este glosario compila los conceptos clave desarrollados durante mis prácticas, uniendo la ingeniería de modelos con la gestión ética y segura de datos.

---

#### **PII (Personally Identifiable Information)**: 
Cualquier dato que pueda ser utilizado para identificar a un individuo de manera única, como DNI, correos electrónicos, números de teléfono. Su protección es el núcleo de la Ley 25.326.
#### **Upstream Security**: 
Estrategia que consiste en implementar medidas de seguridad (como la anonimización) en la etapa más temprana posible del flujo de datos (río arriba), reduciendo el riesgo de exposición en sistemas posteriores (downstream).

#### **Temperature**: 
Parámetro que controla la aleatoriedad de la respuesta de un modelo. 
* **Baja (0.1 - 0.3):** Respuestas deterministas y precisas, ideal para tareas técnicas o legales.
* **Alta (0.7 - 1.0):** Respuestas creativas y variadas.
#### **Model Right-sizing (Modelos "lite")**: 
Práctica de elegir el modelo con la capacidad justa para una tarea específica, optimizando latencia y costos (FinOps) sin sacrificar la calidad necesaria.
#### **Triage Inteligente (AI-Powered Triage):** 
Proceso automatizado de revisión, categorización y priorización de entradas (como reclamos o reseñas) mediante Procesamiento de Lenguaje Natural (NLP), cuyo objetivo es identificar de forma inmediata casos críticos para su derivación estratégica, optimizando el tiempo de respuesta y la eficiencia operativa.
#### **Prompt Grounding (anclaje):** 
Técnica que consiste en "anclar" las respuestas del modelo a un conjunto de datos específico o reglas de negocio (como un manual de categorías), reduciendo significativamente las alucinaciones y asegurando que la IA se mantenga dentro de los límites del dominio permitido.

#### **Modularidad:** 
Principio de diseño que consiste en dividir un sistema en partes independientes (módulos), donde cada una tiene una responsabilidad única. Esto facilita la escalabilidad, el mantenimiento y la reutilización de código (ej. separar la capa de seguridad de la capa de lógica de negocio). 

#### **Web Scraping**: 
Técnica de extracción de datos de sitios web de forma automatizada. En un entorno de producto, permite la captura de feedback público en tiempo real para alimentar tableros de control y sistemas de alerta temprana sobre la salud del producto. 

#### **FastAPI**:
Framework moderno y de alto rendimiento para construir APIs con Python. Es la herramienta estándar para desplegar modelos de IA como servicios web consumibles por otras aplicaciones, permitiendo una integración ágil en entornos productivos.

#### **Privacy by Design**: 
Metodología y enfoque de ingeniería donde la privacidad se integra como un requisito funcional desde el diseño inicial del sistema, y no como una capa añadida posteriormente.

#### **Variables de Entorno (.env)**: 
Valores configurables externos al código fuente que se utilizan para gestionar datos sensibles, como API Keys o credenciales de bases de datos. Su uso es una práctica esencial de Data Governance para evitar la exposición de secretos en repositorios públicos.

#### **Uvicorn (ASGI Server)**: 
Un servidor de alto rendimiento encargado de "hacer correr" aplicaciones web construidas con FastAPI. Actúa como el motor que permite que un microservicio esté disponible para recibir peticiones a través de internet o una red local.

#### **Scope (alcance)**: 
Concepto de programación que define la visibilidad y vida de las variables. Un alcance "Global" permite que componentes como el modelo de IA estén disponibles para todas las funciones de la API, asegurando la modularidad y eficiencia del sistema.

#### **JSON (JavaScript Object Notation)**: 
El estándar de la industria para el intercambio de datos entre aplicaciones. Es un formato ligero, de fácil lectura para humanos y máquinas, que organiza la información en pares de "llave:valor". *En GenAI, es el formato preferido para recibir respuestas estructuradas de los LLMs.*

#### **Endpoint:** 
Una dirección URL específica (como /process-review) dentro de una API donde un cliente puede realizar una petición para obtener una respuesta del sistema. Es el punto de contacto entre el mundo exterior y la lógica de IA.
