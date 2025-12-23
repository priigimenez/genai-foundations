# Glosario de GenAI & Data Governance

Este glosario compila los conceptos clave desarrollados durante mis prácticas, uniendo la ingeniería de modelos con la gestión ética y segura de datos.

---

### Privacidad y Seguridad

#### **PII (Personally Identifiable Information)**: 
Cualquier dato que pueda ser utilizado para identificar a un individuo de manera única, como DNI, correos electrónicos, números de teléfono. Su protección es el núcleo de la Ley 25.326.
#### **Upstream Security**: 
Estrategia que consiste en implementar medidas de seguridad (como la anonimización) en la etapa más temprana posible del flujo de datos (río arriba), reduciendo el riesgo de exposición en sistemas posteriores (downstream).

---

## Ingeniería de modelos (GenAI)

#### **Temperature**: 
Parámetro que controla la aleatoriedad de la respuesta del modelo. 
* **Baja (0.1 - 0.3):** Respuestas deterministas y precisas, ideal para tareas técnicas o legales.
* **Alta (0.7 - 1.0):** Respuestas creativas y variadas.
#### **Model Right-sizing (Modelos "lite")**: 
Práctica de elegir el modelo con la capacidad justa para una tarea específica, optimizando latencia y costos (FinOps) sin sacrificar la calidad necesaria.

---

## Ética y Gobernanza

#### **Privacy by Design**: 
Metodología y enfoque de ingeniería donde la privacidad se integra como un requisito funcional desde el diseño inicial del sistema, y no como una capa añadida posteriormente.
