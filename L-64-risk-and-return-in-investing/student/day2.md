# L-64: Riesgo y Rendimiento en las Inversiones - Laboratorio de Aprendizaje

> **Implementation Note:**
> Use the standardized header template (templates/student-header-template.html) for consistent styling.

## Resumen del Laboratorio de Aprendizaje
- **Capítulo L:** L-64: Riesgo y Rendimiento en las Inversiones
- **Duración:** 55 minutos
- **Enfoque:** Análisis práctico de las compensaciones riesgo-rendimiento a través de la construcción de carteras y cálculos de métricas de riesgo
- **Formato de Aprendizaje:** 90% actividades, 10% facilitación y reflexión

## Materiales Necesarios
- Analizador de Inversiones Riesgo-Rendimiento (accesible a través de la plataforma de aprendizaje)
- Hojas de trabajo de construcción de cartera
- Calculadora de métricas de riesgo
- Visualizaciones de datos históricos del mercado
- Herramienta de evaluación de tolerancia personal al riesgo

## Configuración Pre-Clase
1. Completar la revisión del contenido del Día 1
2. Pensar en tu propia tolerancia al riesgo y horizonte temporal
3. Considerar tus metas financieras (de lecciones anteriores)

## Actividades del Laboratorio de Aprendizaje

### Actividad 1: Evaluación y Análisis de Tolerancia al Riesgo (12 minutos)
**Objetivo:** Determinar tu tolerancia personal al riesgo y entender cómo debería informar las decisiones de inversión

**Instrucciones:**
1. Completa la Evaluación Interactiva de Tolerancia al Riesgo con tres componentes:

   **PARTE A: Preguntas de Horizonte Temporal**
   - ¿Cuándo esperas necesitar este dinero? (Corto plazo: <5 años, Mediano: 5-15 años, Largo plazo: 15+ años)
   - ¿Qué tan estable es tu fuente de ingresos?
   - ¿Tienes un fondo de emergencia adecuado?
   - ¿Qué porcentaje de tu patrimonio neto es esta inversión?

   **PARTE B: Preguntas de Situación Financiera**
   - Nivel de ahorros actual (adecuado, en construcción, mínimo)
   - Situación de deuda (ninguna, manejable, alto interés)
   - Estabilidad de ingresos (muy estable, moderadamente estable, incierto)
   - Otras inversiones o activos

   **PARTE C: Preguntas de Temperamento Emocional**
   - Si tu inversión de $10,000 cayera a $7,000 en seis meses, ¿tú:
     - Entrarías en pánico y venderías inmediatamente
     - Te sentirías incómodo pero mantendrías
     - Te mantendrías calmado y mantendrías
     - Lo verías como una oportunidad de compra
   - ¿Cómo reaccionarías al ver fluctuaciones diarias del valor de tu cartera?
   - ¿Alguna vez has tomado una decisión financiera que lamentaste basada en miedo o emoción?
   - ¿Cuánta volatilidad de cartera puedes tolerar sin perder el sueño?

2. La herramienta calcula tu puntuación de tolerancia al riesgo:
   - **Conservador (0-30 puntos):** Baja tolerancia al riesgo
     - Inversiones apropiadas: Cuentas de ahorro, CDs, bonos gubernamentales, fondos de valor estable
     - Cartera típica: 20% acciones, 80% bonos/efectivo
     - Rendimiento esperado: 3-5% anualmente con baja volatilidad

   - **Moderado (31-60 puntos):** Tolerancia al riesgo equilibrada
     - Inversiones apropiadas: Fondos equilibrados, fondos de bonos, acciones de gran capitalización, REITs
     - Cartera típica: 50-60% acciones, 40-50% bonos
     - Rendimiento esperado: 6-8% anualmente con volatilidad moderada

   - **Agresivo (61-100 puntos):** Alta tolerancia al riesgo
     - Inversiones apropiadas: Fondos indexados de acciones, acciones de crecimiento, mercados emergentes, pequeña capitalización
     - Cartera típica: 80-100% acciones, 0-20% bonos
     - Rendimiento esperado: 8-12% anualmente con alta volatilidad

3. Reflexiona sobre tus resultados:
   - ¿Tu tolerancia al riesgo calculada coincide con tu autopercepción?
   - ¿Qué te sorprendió de la evaluación?
   - ¿Cómo podría cambiar tu tolerancia al riesgo en 10, 20 o 30 años?
   - ¿Hay factores específicos (horizonte temporal, situación financiera, temperamento) que te jalan en diferentes direcciones?

4. **Percepción importante:** Tu tolerancia al riesgo debería ser el MÍNIMO de tus tres componentes. Si tienes un horizonte temporal largo (alta capacidad de riesgo) pero entras en pánico durante las caídas (baja tolerancia emocional), tu tolerancia real al riesgo es baja. Invierte en consecuencia.

### Actividad 2: Calculadora de Métricas de Riesgo de Inversión (15 minutos)
**Objetivo:** Calcular e interpretar la desviación estándar, beta y ratio de Sharpe para diferentes inversiones

**Instrucciones:**
1. Analizarás seis opciones de inversión diferentes usando la Calculadora de Métricas de Riesgo:

   **Inversión A: Bonos del Tesoro de EE.UU.**
   - Rendimientos históricos: Años 1-5: [3.2%, 2.8%, 3.5%, 3.0%, 3.1%]
   - Calcular rendimiento promedio: 3.12%
   - Calcular desviación estándar: ~0.25% (volatilidad muy baja)
   - Beta: 0.05 (correlación mínima con el mercado)
   - Tasa libre de riesgo: 2.5%
   - Calcular ratio de Sharpe: (3.12% - 2.5%) / 0.25% = 2.48 (excelente rendimiento ajustado por riesgo)

   **Inversión B: Índice de Acciones de Gran Capitalización (S&P 500)**
   - Rendimientos históricos: Años 1-5: [12%, -8%, 22%, 15%, 8%]
   - Calcular rendimiento promedio: 9.8%
   - Calcular desviación estándar: ~10.2% (volatilidad moderada)
   - Beta: 1.0 (por definición, sigue al mercado)
   - Calcular ratio de Sharpe: (9.8% - 2.5%) / 10.2% = 0.72

   **Inversión C: Acciones de Crecimiento de Pequeña Capitalización**
   - Rendimientos históricos: Años 1-5: [18%, -15%, 35%, 22%, -5%]
   - Calcular rendimiento promedio: 11%
   - Calcular desviación estándar: ~19.4% (alta volatilidad)
   - Beta: 1.4 (40% más volátil que el mercado)
   - Calcular ratio de Sharpe: (11% - 2.5%) / 19.4% = 0.44 (más bajo debido a alta volatilidad)

   **Inversión D: Mercados Emergentes**
   - Rendimientos históricos: Años 1-5: [25%, -22%, 40%, 18%, -8%]
   - Calcular rendimiento promedio: 10.6%
   - Calcular desviación estándar: ~25.1% (volatilidad muy alta)
   - Beta: 1.6 (60% más volátil que el mercado)
   - Calcular ratio de Sharpe: (10.6% - 2.5%) / 25.1% = 0.32 (el más bajo—alto riesgo no bien compensado)

   **Inversión E: Fondo Equilibrado (60/40 acciones/bonos)**
   - Rendimientos históricos: Años 1-5: [8%, -3%, 14%, 10%, 5%]
   - Calcular rendimiento promedio: 6.8%
   - Calcular desviación estándar: ~6.2% (volatilidad moderada-baja)
   - Beta: 0.6 (40% menos volátil que el mercado)
   - Calcular ratio de Sharpe: (6.8% - 2.5%) / 6.2% = 0.69

   **Inversión F: Cuenta de Ahorro de Alto Rendimiento**
   - Rendimientos históricos: Años 1-5: [2.1%, 2.3%, 2.0%, 2.2%, 2.4%]
   - Calcular rendimiento promedio: 2.2%
   - Calcular desviación estándar: ~0.15% (volatilidad mínima)
   - Beta: 0.0 (sin correlación con el mercado)
   - Calcular ratio de Sharpe: (2.2% - 2.5%) / 0.15% = -2.0 (negativo—por debajo de la tasa libre de riesgo)

2. Usando la calculadora, calcula cada métrica:
   - **Rendimiento Promedio:** Suma todos los rendimientos ÷ número de años
   - **Desviación Estándar:** Muestra cuánto varían los rendimientos del promedio
     - Fórmula: √[Σ(rendimiento - promedio)² ÷ (n-1)]
     - Interpretación: Mayor = más volátil
   - **Beta:** Mide la sensibilidad al mercado
     - La calculadora usa análisis de regresión contra los rendimientos del mercado
     - Interpretación: >1.0 = más volátil que el mercado, <1.0 = menos volátil
   - **Ratio de Sharpe:** Medida de rendimiento ajustado por riesgo
     - Fórmula: (Rendimiento Promedio - Tasa Libre de Riesgo) ÷ Desviación Estándar
     - Interpretación: Mayor = mejor rendimiento por unidad de riesgo

3. Responde preguntas de análisis:
   - ¿Qué inversión tiene el ratio de Sharpe más alto? ¿Qué significa esto?
   - ¿Qué inversión tiene el rendimiento bruto más alto? ¿Mayor riesgo?
   - ¿Es la inversión de mayor rendimiento también la de mejor rendimiento ajustado por riesgo? ¿Por qué o por qué no?
   - ¿Cómo afecta el beta tu interpretación del riesgo de una inversión?
   - Para una persona de 25 años invirtiendo para la jubilación, ¿qué inversiones parecen más apropiadas?
   - Para una persona de 62 años acercándose a la jubilación, ¿qué inversiones parecen más apropiadas?

4. **Percepción clave:** La "mejor" inversión no es la que tiene el rendimiento más alto—es la que tiene el mejor rendimiento ajustado por riesgo (ratio de Sharpe) que coincide con tu tolerancia al riesgo y horizonte temporal. A veces una inversión de menor rendimiento es la mejor elección.

### Actividad 3: Construcción de Cartera para Diferentes Perfiles de Riesgo (18 minutos)
**Objetivo:** Construir carteras diversificadas alineadas con diferentes perfiles de inversor y analizar sus características de riesgo-rendimiento

**Instrucciones:**
1. Construirás tres carteras diferentes usando el Analizador de Inversiones Riesgo-Rendimiento, cada una para un perfil de inversor diferente:

   **PERFIL 1: MARÍA (Edad 25, Crecimiento Agresivo)**
   - **Situación:** Acaba de comenzar su carrera, $45,000 de salario, contribuyendo $300/mes al 401(k)
   - **Horizonte temporal:** 40 años hasta la jubilación
   - **Tolerancia al riesgo:** Alta (puede soportar volatilidad, necesita crecimiento a largo plazo)
   - **Metas:** Máxima acumulación de riqueza a largo plazo

   **Construye la Cartera de María (Total: 100%)**
   - Asigna porcentajes a través de las seis opciones de inversión
   - Asignación agresiva sugerida:
     - Bonos del Tesoro: 0%
     - Acciones de Gran Capitalización: 50%
     - Crecimiento de Pequeña Capitalización: 25%
     - Mercados Emergentes: 15%
     - Fondo Equilibrado: 10%
     - Cuenta de Ahorro: 0%

   **Calcula las Métricas de la Cartera:**
   - Rendimiento promedio ponderado: (0.50 × 9.8%) + (0.25 × 11%) + (0.15 × 10.6%) + (0.10 × 6.8%) = 9.98%
   - Desviación estándar de la cartera: ~12.4% (calculada usando correlación)
   - Beta de la cartera: ~1.12 (ligeramente más volátil que el mercado)
   - Ratio de Sharpe de la cartera: (9.98% - 2.5%) / 12.4% = 0.60

   **Proyección:** $300/mes durante 40 años al 9.98% = aproximadamente $1,623,000

   **PERFIL 2: DAVID (Edad 45, Balance Moderado)**
   - **Situación:** Carrera establecida, $78,000 de salario, tiene $150,000 ahorrados ya
   - **Horizonte temporal:** 20 años hasta la jubilación
   - **Tolerancia al riesgo:** Moderada (necesita crecimiento pero no puede permitirse contratiempos importantes)
   - **Metas:** Crecimiento constante con volatilidad manejable

   **Construye la Cartera de David (Total: 100%)**
   - Asignación moderada sugerida:
     - Bonos del Tesoro: 20%
     - Acciones de Gran Capitalización: 40%
     - Crecimiento de Pequeña Capitalización: 10%
     - Mercados Emergentes: 5%
     - Fondo Equilibrado: 20%
     - Cuenta de Ahorro: 5%

   **Calcula las Métricas de la Cartera:**
   - Rendimiento promedio ponderado: (0.20 × 3.12%) + (0.40 × 9.8%) + (0.10 × 11%) + (0.05 × 10.6%) + (0.20 × 6.8%) + (0.05 × 2.2%) = 7.31%
   - Desviación estándar de la cartera: ~7.8% (volatilidad moderada)
   - Beta de la cartera: ~0.68 (menos volátil que el mercado)
   - Ratio de Sharpe de la cartera: (7.31% - 2.5%) / 7.8% = 0.62

   **Proyección:** $500/mes durante 20 años al 7.31% = aproximadamente $262,000 (más crecimiento de los $150,000 existentes → $597,000 total)

   **PERFIL 3: SHARON (Edad 63, Preservación Conservadora)**
   - **Situación:** Se jubila en 2 años, $620,000 ahorrados, necesita ingresos y estabilidad
   - **Horizonte temporal:** 2 años hasta la jubilación, luego 20+ años en jubilación
   - **Tolerancia al riesgo:** Baja (no puede permitirse pérdidas significativas antes de la jubilación)
   - **Metas:** Preservación del capital con crecimiento modesto, generación de ingresos

   **Construye la Cartera de Sharon (Total: 100%)**
   - Asignación conservadora sugerida:
     - Bonos del Tesoro: 40%
     - Acciones de Gran Capitalización: 25%
     - Crecimiento de Pequeña Capitalización: 0%
     - Mercados Emergentes: 0%
     - Fondo Equilibrado: 25%
     - Cuenta de Ahorro: 10%

   **Calcula las Métricas de la Cartera:**
   - Rendimiento promedio ponderado: (0.40 × 3.12%) + (0.25 × 9.8%) + (0.25 × 6.8%) + (0.10 × 2.2%) = 5.62%
   - Desviación estándar de la cartera: ~4.5% (baja volatilidad)
   - Beta de la cartera: ~0.43 (mucho menos volátil que el mercado)
   - Ratio de Sharpe de la cartera: (5.62% - 2.5%) / 4.5% = 0.69 (el más alto—excelente rendimiento ajustado por riesgo)

   **Proyección:** $620,000 creciendo al 5.62% durante 20 años = aproximadamente $1,844,000

2. Compara las tres carteras:
   - ¿Cuál tiene el rendimiento esperado más alto? ¿Mayor riesgo (desviación estándar)?
   - ¿Cuál tiene el mejor ratio de Sharpe (rendimiento ajustado por riesgo)?
   - ¿Cómo afecta la edad/horizonte temporal la asignación apropiada?
   - ¿Qué pasa si usas la cartera de María para Sharon? (Calcula las pérdidas potenciales en un mal año)
   - ¿Qué pasa si usas la cartera de Sharon para María? (Calcula el costo de oportunidad durante 40 años)

3. Experimenta con cambios en la asignación:
   - Aumenta los mercados emergentes de María del 15% al 30%—¿qué pasa con el riesgo y el rendimiento?
   - Agrega 10% de acciones de pequeña capitalización a la cartera de Sharon—¿está esto justificado?
   - Haz la cartera de David más conservadora (70% bonos/efectivo)—¿cómo afecta esto los ahorros proyectados para la jubilación?

4. **Lección crítica:** No hay cartera "mejor"—solo la cartera mejor adaptada a TU situación. Una cartera agresiva que es perfecta para una persona de 25 años sería imprudente para alguien que se jubila en dos años. La inversión apropiada para la edad es esencial.

### Actividad 4: Análisis de Volatilidad Histórica y Toma de Decisiones (10 minutos)
**Objetivo:** Analizar la volatilidad histórica del mercado y tomar decisiones de inversión bajo incertidumbre

**Instrucciones:**
1. Revisa la visualización de Rendimiento Histórico del Mercado que muestra los rendimientos del mercado de valores de los últimos 30 años:

   **Períodos notables:**
   - 2000-2002: Caída de las puntocom (-37% durante 3 años)
   - 2003-2007: Recuperación y crecimiento (+102% durante 5 años)
   - 2008: Crisis financiera (-37% en un solo año)
   - 2009-2019: El mercado alcista más largo de la historia (+400% durante 11 años)
   - 2020: Caída por pandemia (-34% en 1 mes) luego rápida recuperación (+65% para fin de año)
   - 2022: Inflación/subidas de tasas (-18% para el año)

   **Rendimiento anual promedio durante 30 años:** ~10.2%
   **Desviación estándar:** ~18%
   **Mejor año:** +37.6%
   **Peor año:** -37.0%

2. Completa el escenario "¿Qué Harías Tú?":

   **Escenario:** Invertiste $10,000 en enero de 2008 en un fondo indexado de acciones. Para diciembre de 2008, vale $6,300 (caída del 37%). Necesitas este dinero en 5 años para el pago inicial de una casa.

   **Tus opciones:**
   - **Opción A:** Vender ahora, bloquear pérdida de $3,700, mover a bonos seguros
   - **Opción B:** Mantener y esperar la recuperación
   - **Opción C:** Invertir más (comprar mientras está "en oferta")
   - **Opción D:** Cambiar a fondo equilibrado menos volátil

   **Preguntas de análisis:**
   - ¿Cuáles son los riesgos y beneficios de cada opción?
   - ¿Qué sugieren los datos históricos que típicamente sucede después de caídas importantes?
   - ¿Cómo afecta tu horizonte temporal de 5 años tu decisión?
   - ¿Qué harías diferente si necesitaras el dinero en 1 año vs. 15 años?

3. Ve el resultado: Si mantuviste durante 2008, tus $6,300 crecieron a:
   - 2010: $8,100 (acercándose)
   - 2012: $10,300 (de vuelta al punto de equilibrio)
   - 2013: $13,400 (30% de ganancia)
   - 2019: $22,900 (129% de ganancia desde el mínimo de 2008)

4. **Lecciones clave:**
   - El timing del mercado es casi imposible—incluso los profesionales se equivocan
   - El tiempo EN el mercado supera al timing del mercado
   - La volatilidad es el precio que pagas por los rendimientos a largo plazo
   - Tu horizonte temporal determina cuánta volatilidad puedes tolerar
   - Vender durante las caídas bloquea pérdidas y pierde la recuperación

5. Preguntas de reflexión:
   - Conociendo esta historia, ¿cómo reaccionarías ante una caída similar hoy?
   - ¿Qué estrategias podrían ayudarte a evitar vender en pánico durante las caídas?
   - ¿Cómo cambia tu enfoque de inversión entender los patrones históricos?
   - ¿Invertirías diferente a los 25 años vs. a los 60 años dada esta volatilidad?

## Reflexión y Cierre (3 minutos)
1. **Compromiso personal:** Basándote en las actividades de hoy, ¿cuál es tu enfoque personal de inversión?
   - Mi tolerancia al riesgo es: [Conservadora / Moderada / Agresiva]
   - Mi horizonte temporal actual es: ___ años
   - Mi asignación de activos apropiada es: ___% acciones, ___% bonos, ___% efectivo
   - Una cosa que haré diferente en mis inversiones: ________________________________

2. **Percepción clave:** ¿Cuál fue tu mayor momento "ajá" hoy sobre riesgo y rendimiento?

3. **Elemento de acción:** ¿Qué paso específico tomarás en la próxima semana para aplicar lo que aprendiste?

## Puntos Clave
- La tolerancia al riesgo depende de tres factores: horizonte temporal, situación financiera y temperamento emocional—tu tolerancia real es el mínimo de estos tres
- Los rendimientos más altos requieren aceptar mayor riesgo, pero la "mejor" inversión se determina por los rendimientos ajustados por riesgo (ratio de Sharpe), no solo por los rendimientos brutos
- La construcción de cartera debería coincidir con tu etapa de vida—crecimiento agresivo para inversores jóvenes con décadas por delante, preservación conservadora para aquellos cerca de la jubilación
- La desviación estándar, beta y ratio de Sharpe son herramientas objetivas para medir y comparar el riesgo de inversión
- La volatilidad histórica del mercado muestra oscilaciones dramáticas a corto plazo pero tendencias positivas a largo plazo—el horizonte temporal determina si la volatilidad es tu amiga o enemiga
- La inversión apropiada para la edad es esencial—lo que es perfecto para una persona de 25 años puede ser imprudente para una de 60 años, y viceversa
