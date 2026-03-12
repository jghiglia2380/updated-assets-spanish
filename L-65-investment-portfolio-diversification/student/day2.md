# L-65: Diversificación de Portafolios de Inversión - Laboratorio de Aprendizaje

> **Implementation Note:**
> Use the standardized header template (templates/student-header-template.html) for consistent styling.
> This includes:
> - Purple header with navigation menu (Home, Curriculum, Resources, Profile)
> - Left navigation with blue vertical indicators for active items and green checkmarks for completed items
> - Content styling using the standard component classes

## Descripción General del Laboratorio de Aprendizaje
**Capítulo L:** 65 - Diversificación de Portafolios de Inversión
**Duración:** 55 minutos
**Enfoque:** Construcción práctica de portafolios, análisis de correlación, optimización de asignación de activos y práctica de rebalanceo
**Formato de Aprendizaje:** Estaciones basadas en actividades con herramientas de construcción de portafolios y simulaciones de mercado

## Materiales Necesarios
- Constructor de Diversificación de Portafolios (herramienta digital)
- Analizador de Matriz de Correlación (herramienta digital)
- Optimizador de Asignación de Activos (herramienta digital)
- Simulador de Rebalanceo (herramienta digital)
- Calculadora (integrada o separada)

## Preparación Previa a la Clase
Antes de comenzar el laboratorio de aprendizaje de hoy:
1. Asegúrate de poder acceder a las cuatro herramientas digitales
2. Ten disponibles tus notas del Día 1 para referencia
3. Prepárate para construir y analizar múltiples estrategias de portafolio
4. Ten lista la calculadora o herramienta de cálculo

## Actividades del Laboratorio de Aprendizaje

### Actividad 1: Desafío del Detective de Correlación (13 minutos)

**Objetivo:** Entender cómo la correlación entre inversiones afecta el riesgo del portafolio

**Instrucciones:**
1. Usando el Analizador de Matriz de Correlación, examinarás datos históricos de correlación entre diferentes clases de activos:
   - Acciones de Gran Capitalización EE.UU.
   - Acciones de Pequeña Capitalización EE.UU.
   - Acciones de Mercados Desarrollados Internacionales
   - Acciones de Mercados Emergentes
   - Bonos del Gobierno EE.UU.
   - Bonos Corporativos
   - Bienes Raíces (REITs)
   - Oro
   - Materias Primas (canasta amplia)
2. La herramienta muestra una matriz de correlación que indica cómo cada par de activos se ha movido históricamente juntos (-1.0 a +1.0):
   - **+0.8 a +1.0:** Correlación muy alta (se mueven juntos muy de cerca)
   - **+0.5 a +0.8:** Correlación moderada-alta (usualmente se mueven juntos)
   - **+0.2 a +0.5:** Correlación baja-moderada (alguna relación)
   - **-0.2 a +0.2:** Correlación muy baja/nula (movimiento independiente)
   - **-0.5 a -0.2:** Correlación negativa baja-moderada
   - **-1.0 a -0.5:** Correlación negativa moderada-alta (tienden a moverse en direcciones opuestas)
3. Analiza la matriz para responder:
   - ¿Qué dos activos tienen la **correlación positiva más alta**? (se mueven más juntos)
   - ¿Qué dos activos tienen la **correlación más baja o negativa**? (se mueven más independientemente u opuestamente)
   - ¿Cuál es la correlación entre **acciones EE.UU. y bonos del gobierno EE.UU.**? ¿Qué significa esto para el riesgo del portafolio?
   - ¿Cuál es la correlación entre **gran capitalización EE.UU. y mercados desarrollados internacionales**? ¿Combinarlos proporcionaría diversificación significativa?
4. **Prueba de Escenarios:**
   - Construye Portafolio A: 100% Acciones de Gran Capitalización EE.UU.
   - Construye Portafolio B: 50% Gran Capitalización EE.UU., 50% Bonos del Gobierno EE.UU.
   - Construye Portafolio C: 40% Gran Capitalización EE.UU., 20% Internacional, 20% Bonos, 10% Bienes Raíces, 10% Oro
   - La herramienta simula cada portafolio a través de períodos históricos del mercado y muestra:
     - Máxima reducción (mayor pérdida de pico a valle)
     - Volatilidad (desviación estándar de rendimientos)
     - Rendimiento anual promedio
5. Compara los tres portafolios:
   - ¿Cuál tuvo la menor máxima reducción?
   - ¿Cuál tuvo la menor volatilidad?
   - ¿La diversificación redujo significativamente el riesgo comparado con tener solo acciones?
6. **Desafío:** Crea un cuarto portafolio que minimice la volatilidad mientras mantiene al menos 7% de rendimiento anual promedio. ¿Qué combinación logra esto?

**Asignación de Tiempo:**
- Examinar matriz de correlación y responder preguntas: 5 minutos
- Construir y probar tres portafolios: 5 minutos
- Crear desafío de portafolio optimizado: 2 minutos
- Breve discusión con compañero sobre hallazgos: 1 minuto

---

### Actividad 2: Constructor de Estrategia de Asignación Basada en Edad (15 minutos)

**Objetivo:** Diseñar asignaciones de activos apropiadas para inversores en diferentes etapas de vida

**Instrucciones:**
1. Usando el Optimizador de Asignación de Activos, crearás portafolios para tres inversores de diferentes edades:
   - **Inversor 1 - Maya (Edad 25):** Recién graduada universitaria, $400/mes para invertir, objetivo de jubilación a los 65
   - **Inversor 2 - David (Edad 45):** Profesional a mitad de carrera, $800/mes para invertir, objetivo de jubilación a los 67
   - **Inversor 3 - Patricia (Edad 60):** Planea jubilarse en 7 años, $500/mes para invertir, necesita ingresos a partir de los 67
2. Para cada inversor, determina una asignación de activos apropiada considerando:
   - **Horizonte temporal:** Años hasta la jubilación
   - **Capacidad de riesgo:** Capacidad de recuperarse de pérdidas basada en el tiempo disponible
   - **Necesidades de ingresos:** Cuándo necesitarán retirar dinero
3. Construye asignaciones seleccionando porcentajes entre:
   - **Acciones EE.UU.** (Gran Capitalización, Pequeña Capitalización)
   - **Acciones Internacionales** (Mercados Desarrollados, Mercados Emergentes)
   - **Bonos** (Gobierno, Corporativos)
   - **Bienes Raíces** (REITs)
   - **Efectivo/Valor Estable**
4. La herramienta proporciona orientación:
   - **Asignación sugerida de acciones:** regla "120 menos edad" (120 - 25 = 95% acciones para Maya)
   - **Evaluación de riesgo:** Muestra máxima reducción potencial y volatilidad para tu asignación
   - **Rendimientos esperados:** Proyecta rendimiento anual promedio basado en datos históricos
5. Para cada inversor, crea una asignación y la herramienta proyectará:
   - Riqueza total a la edad de jubilación
   - Pérdida máxima que podrían experimentar durante caídas del mercado
   - Tiempo de recuperación requerido después del peor caso de caída
6. **Preguntas de Análisis:**
   - ¿Por qué Maya puede tolerar 90% en acciones mientras Patricia solo debería tener 35-40%?
   - Si David usa una asignación excesivamente conservadora (40% acciones), ¿cuánta riqueza potencial sacrifica para la jubilación?
   - Si Patricia usa una asignación excesivamente agresiva (80% acciones), ¿qué riesgo enfrenta si una caída del mercado ocurre a los 65-66 años?
7. **Aplicación del Mundo Real:**
   - Si actualmente tienes 18-20 años y comenzaras a invertir $200/mes, ¿qué asignación elegirías?
   - ¿Cómo ajustarías esta asignación cuando llegues a los 35? ¿50? ¿65?

**Asignación de Tiempo:**
- Revisar tres perfiles de inversores: 2 minutos
- Construir asignación para Inversor 1 (Maya): 4 minutos
- Construir asignación para Inversor 2 (David): 4 minutos
- Construir asignación para Inversor 3 (Patricia): 4 minutos
- Responder preguntas de análisis: 1 minuto

---

### Actividad 3: Simulación de Supervivencia a Crisis del Mercado (14 minutos)

**Objetivo:** Experimentar cómo la diversificación protege la riqueza durante caídas del mercado

**Instrucciones:**
1. Usando el Constructor de Diversificación de Portafolios, construirás dos portafolios contrastantes y verás cómo se desempeñan durante una crisis de mercado simulada:
   - **Portafolio A - Concentrado:** 100% en una clase de activo (tu elección: todo acciones, todo bonos, o todo en un sector)
   - **Portafolio B - Diversificado:** Distribuido entre múltiples clases de activos usando principios de asignación del Día 1
2. Cada portafolio comienza con $50,000
3. La simulación recorre un escenario de **Crisis Mayor del Mercado**:
   - **Mes 1-3:** Comienza la caída del mercado, acciones bajan 15%, bonos se mantienen estables
   - **Mes 4-6:** La crisis se profundiza, acciones bajan otro 20% (total -32% desde el inicio), bonos suben 5%
   - **Mes 7-9:** Pico de pánico, acciones bajan otro 15% (total -41% desde el inicio), mercados emergentes bajan 50%, oro sube 15%, bonos suben otro 3%
   - **Mes 10-18:** Comienza la recuperación, acciones suben 25% desde el fondo, bonos devuelven algunas ganancias
   - **Mes 19-30:** Mercado alcista, acciones suben otro 35%, de vuelta a nuevos máximos
4. Observa la simulación y registra:
   - **Pérdida Máxima:** Valor más bajo del portafolio durante la crisis
   - **Tiempo de Recuperación:** Meses hasta que el portafolio regresa a los $50,000 iniciales
   - **Valor Final:** Valor del portafolio en el mes 30
5. La simulación te permite tomar decisiones en puntos clave:
   - **Durante la caída (Mes 9):** ¿Qué haces?
     - ¿Vender todo en pánico a efectivo (asegurando pérdidas)?
     - ¿Mantener estable y no hacer nada?
     - ¿Rebalancear (vender bonos que se mantuvieron, comprar acciones en oferta)?
   - **Durante la recuperación (Mes 15):** ¿Qué haces?
     - ¿Empezar a tomar ganancias en acciones?
     - ¿Continuar manteniendo o rebalanceando?
     - ¿Agregar nuevas contribuciones?
6. Compara resultados:
   - ¿Cuánto perdió el Portafolio A (concentrado) en el peor punto?
   - ¿Cuánto perdió el Portafolio B (diversificado) en el peor punto?
   - ¿Cuál se recuperó más rápido?
   - Si tomaste decisiones de pánico (vendiendo en el fondo), ¿cuánta riqueza permanente destruiste?
   - Si rebalanceaste durante la crisis (vendiendo bonos, comprando acciones), ¿cuál fue tu resultado final?
7. **Reflexión:**
   - ¿Podrías manejar emocionalmente ver un portafolio concentrado caer 40-50%?
   - ¿Cómo cambió la diversificación tu pérdida máxima y tiempo de recuperación?
   - ¿Qué rol jugó el rebalanceo en el resultado final?

**Asignación de Tiempo:**
- Construir Portafolio A (Concentrado): 2 minutos
- Construir Portafolio B (Diversificado): 3 minutos
- Ejecutar simulación de crisis y tomar decisiones: 6 minutos
- Comparar resultados y reflexionar: 3 minutos

---

### Actividad 4: Laboratorio de Práctica de Rebalanceo (8 minutos)

**Objetivo:** Practicar el rebalanceo de portafolios para mantener asignaciones objetivo

**Instrucciones:**
1. Usando el Simulador de Rebalanceo, gestionarás un portafolio durante 10 años con decisiones anuales de rebalanceo
2. **Portafolio Inicial:** $100,000 con asignación objetivo 70/30 acciones/bonos
   - $70,000 en fondo índice de acciones
   - $30,000 en fondo índice de bonos
3. Cada año, la herramienta muestra:
   - Cómo se desempeñaron las acciones y los bonos (diferentes rendimientos cada año)
   - Valores actuales del portafolio y porcentajes de asignación
   - Cuánto se ha desviado tu asignación del objetivo 70/30
4. Debes decidir:
   - **Rebalancear:** Vender algo de lo que creció más, comprar más de lo que se quedó atrás, para restaurar 70/30
   - **No Rebalancear:** Dejar que el portafolio se desvíe, aceptando cualquier asignación que resulte
5. La simulación muestra tres universos paralelos:
   - **Tus Decisiones:** El camino basado en tus elecciones de rebalanceo
   - **Siempre Rebalancear:** Lo que sucede si rebalanceas cada año sin falta
   - **Nunca Rebalancear:** Lo que sucede si nunca rebalanceas
6. Ejemplos de años clave de decisión:
   - **Año 3:** Las acciones han subido 65% total desde el inicio mientras los bonos ganaron 12%. Tu portafolio ahora es 78% acciones / 22% bonos. ¿Rebalanceas?
   - **Año 7:** Las acciones cayeron 35% el año pasado mientras los bonos subieron 8%. Tu portafolio ahora es 58% acciones / 42% bonos. ¿Rebalanceas?
7. Al final de 10 años, compara:
   - Valor final de cada estrategia (Tus Decisiones vs. Siempre Rebalancear vs. Nunca Rebalancear)
   - Máxima reducción (peor pérdida) experimentada por cada una
   - Cuánto se desvió la asignación en el escenario "Nunca Rebalancear"
8. **Análisis:**
   - ¿El rebalanceo anual mejoró los rendimientos, redujo el riesgo, o ambos?
   - ¿Fue más difícil rebalancear después de que las acciones subieron (vendiendo ganadores) o después de que cayeron (comprando perdedores)?
   - ¿Con qué asignación terminó el portafolio "Nunca Rebalancear"? ¿Fue más arriesgado de lo previsto?
9. **Aplicación del Mundo Real:**
   - Establece una regla personal: "Rebalancearé mi portafolio [anualmente / cuando la asignación se desvíe 5+ puntos porcentuales] para mantener mi asignación objetivo."

**Asignación de Tiempo:**
- Revisar portafolio inicial y reglas: 1 minuto
- Tomar decisiones de rebalanceo para 10 años simulados: 5 minutos
- Comparar tres estrategias y analizar resultados: 2 minutos

---

## Reflexión y Cierre (5 minutos)

**Preguntas de Discusión Grupal:**
1. ¿Cuál fue la perspectiva más sorprendente sobre la diversificación de las actividades de hoy?
2. Después de experimentar la simulación de crisis del mercado, ¿qué tan confiado te sientes sobre permanecer invertido durante caídas reales?
3. ¿Qué estrategia de asignación de activos usarás cuando comiences a invertir (o si ya lo estás haciendo)?
4. ¿Cuál es tu compromiso personal de rebalanceo? ¿Con qué frecuencia y bajo qué condiciones?

**Reflexión Individual:**
Toma 2 minutos para escribir respuestas a:
- Una cosa que aprendí sobre la diversificación de portafolios que no entendía completamente antes
- Una estrategia específica de asignación o rebalanceo que usaré en mis futuras inversiones
- Una acción que tomaré en los próximos 30 días relacionada con la diversificación de portafolios

## Puntos Clave

Al final de este laboratorio de aprendizaje, deberías poder:

1. **Analizar Correlación:** Identificar qué activos se mueven juntos y cuáles se mueven independientemente, entendiendo que combinar activos de baja correlación reduce la volatilidad del portafolio

2. **Diseñar Asignaciones Apropiadas para la Edad:** Crear asignaciones adecuadas de acciones/bonos para diferentes etapas de vida, entendiendo por qué los inversores jóvenes pueden aceptar más riesgo mientras los inversores mayores necesitan más estabilidad

3. **Construir Portafolios Diversificados:** Construir portafolios distribuidos entre múltiples clases de activos, evitando el riesgo de concentración mientras capturas crecimiento en diferentes mercados

4. **Aplicar Disciplina de Rebalanceo:** Restaurar portafolios a asignaciones objetivo periódicamente, mecánicamente "comprando bajo y vendiendo alto" sin toma de decisiones emocionales

5. **Evaluar Compensaciones Riesgo-Rendimiento:** Equilibrar el deseo de altos rendimientos con la necesidad de riesgo manejable, encontrando el punto óptimo en la frontera eficiente para tu situación

6. **Sobrevivir Crisis del Mercado:** Entender que los portafolios diversificados reducen las caídas de devastadoras a manejables, y que el rebalanceo durante crisis te posiciona para la recuperación

7. **Implementar Estrategias Sistemáticas:** Comprometerte con enfoques de asignación y rebalanceo basados en evidencia en lugar de reaccionar emocionalmente a las oscilaciones del mercado

Las habilidades de diversificación de portafolios practicadas hoy—análisis de correlación, asignación basada en edad, gestión de crisis y rebalanceo disciplinado—son la base de la inversión exitosa a largo plazo. Estos no son conceptos teóricos; son herramientas prácticas que separan a los inversores que construyen riqueza de manera constante de aquellos que experimentan ciclos de auge y caída y errores impulsados por el pánico. Cada dólar que inviertas a lo largo de tu vida se beneficiará de los principios de diversificación practicados en este laboratorio de aprendizaje.
