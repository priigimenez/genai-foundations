(notitas de 'Introduction to Responsible AI' (Google Skiil Boost)

##La base del gobierno
Porque no se trata solamente de la tecnología. Se trata de decisiones humanas, cuyas repercusiones presentes y futuras pueden exceder los resultados de un sólo análisis. 

**Conceptos clave** 
- La AI no es infalible: no es ni tiene una 'verdad absoluta'. En realidad, solo es un espejo de lo que somos como sociedad (incluyendo todos los defectos).
- La responsabilidad humana: la tecnología no toma decisiones éticas, las tomamos (o deberíamos) nosotros, los que diseñamos, entrenamos y desplegamos.
- Los pilares de Gobernanza:
      - Transparencia: ¿sabemos por qué el modelo dijo lo que dijo? 
      - Equidad (Fairness): evitar que el modelo 'discrimine' por sesgos presentes en los datos de entrenamiento.
      - Rendiciónd de cuentas (Accountability): si el modelo falla, ¿quién se hace cargo?

La AI responsable no es un 'check' más al final de un proyecto. Es un proceso continuo, que empieza en el diseño y permanece en el monitoreo. 
Porque sin confianza (Trust), no hay adopción del usuario. 

**La parte un poco más técnica**
La importancia de entender qué hay 'bajo el capó' para poder gobernarlo.

1. El 'árbol genealógico'
   a. AI: sistemas que razonan y aprenden.
   b. ML: aprender de los datos sin ser programados explícitamente. 
   c. DL: redes neuronales. Mayor complejidad. 
   d. GenAI: subconjunto de DL que crea contenido nuevo (no solo clasifica).

2. La revolución de los Transformers (2018): esta arquitectura (Encoder/Decoder) permitió que la GenAI alcanzara niveles de desarrollo mayores. Permite que el modelo 'entienda' todo el contexto de una frase completa, y no sólo palabra por palabra.
(La cuestión del contexto, o la contextualización, es fundamental). 

3. Las alucionaciones, el gran riesgo: sucenden cuando el modelo 'inventa' con muchas seguridad cosas que no son ciertas o que no tienen sentido en el contexto determinado.
   a. Causas (foco en Data Quality): datos de entrenamiento sucios o ruidosos, falta de contexto suficiente en el prompt, o falta de restricciones (constraints) en el modelo.

**Relación con Data Governance**
Concepto Técnico / Desafío de Gobierno
Modelos Fundacionales / Propiedad intelectual: ¿con qué datos se entrenó? ¿Tengo permiso para usarlos?
Prompt Design / Seguridad de datos: ¿estamos enviando PII (información sensible) en los prompts?
Training Data / Calidad de datos: si el dataset es sesgado, el modelo será sesgado.
Hallucinations / Veracidad y confianza: ¿cómo validamos que la respuesta es real antes de dársela, por ejemplo, a un cliente?

*Próximos pasos*
- Profundizar en técnicas de RAG para reducir alucinaciones usando datos gobernados.
- Explorar Vertex AI Safety Filters para aplicar las políticas de "Responsible AI" de forma práctica.
