# L-50: Oferta y Demanda en Finanzas Personales
## Día 2: Análisis de Mercado y Aplicaciones - Laboratorio de Aprendizaje

> **Implementation Note:**
> Use the standardized header template for consistent styling.

### Objetivos de Aprendizaje
Al final del Laboratorio de Aprendizaje de hoy, podrás:
- Aplicar análisis de oferta y demanda a los mercados de vivienda y trabajo de {{STATE_NAME}}
- Evaluar cómo los cambios del mercado afectan las decisiones financieras personales
- Usar señales de precios para tomar decisiones informadas de consumo y carrera
- Analizar elasticidad para comprender cuándo los precios son flexibles vs. rígidos

---

## Reflexión de Apertura (5 minutos)

**Escribe:** Piensa en una compra que harás en los próximos 6 meses (teléfono, auto, boletos de concierto, libros de texto universitarios, alquiler de apartamento, etc.).

**Preguntas:**
- ¿Cuándo es el mejor momento para comprar y obtener el precio más bajo?
- ¿Qué factores de oferta y demanda afectan el precio?
- ¿Cómo puedes usar el conocimiento del mercado para ahorrar dinero?

Mantén esta compra en mente mientras trabajamos en las actividades de hoy.

---

## Actividades del Laboratorio de Aprendizaje

### Actividad 1: Análisis del Mercado de Vivienda de {{STATE_NAME}} (20 minutos)

**Objetivo:** Aplicar análisis de oferta y demanda para comprender los precios de vivienda de {{STATE_NAME}} y tomar decisiones informadas.

#### Datos de Fondo

**Mercado de Vivienda de {{STATE_NAME}}:**
- Precio mediano de vivienda: {{STATE_MEDIAN_HOME_PRICE}}
- Alquiler mediano: {{STATE_MEDIAN_RENT}}/mes
- Tendencia del mercado de vivienda: {{STATE_HOUSING_MARKET_TRENDS}}

#### Parte A: Identificar Factores de Oferta y Demanda (5 min)

**Factores de Demanda en {{STATE_NAME}}:**

| Factor | Efecto en Demanda | Fuerza (Baja/Media/Alta) | Tendencia Actual |
|--------|-------------------|--------------------------|------------------|
| Crecimiento poblacional | Aumenta / Disminuye | _____________ | Creciendo / Estable / Declinando |
| Niveles de ingreso | Aumenta / Disminuye | _____________ | Subiendo / Estable / Bajando |
| Tasas de interés hipotecario | Aumenta / Disminuye | _____________ | Subiendo / Estable / Bajando |
| Tasa de empleo | Aumenta / Disminuye | _____________ | Fuerte / Moderada / Débil |
| **EFECTO NETO EN DEMANDA:** | → → → | **Desplazamiento: Derecha / Izquierda / Estable** |

**Factores de Oferta en {{STATE_NAME}}:**

| Factor | Efecto en Oferta | Fuerza (Baja/Media/Alta) | Tendencia Actual |
|--------|------------------|--------------------------|------------------|
| Costos de construcción | Aumenta / Disminuye | _____________ | Subiendo / Estable / Bajando |
| Disponibilidad de tierra | Aumenta / Disminuye | _____________ | Abundante / Limitada / Escasa |
| Regulaciones de zonificación | Aumenta / Disminuye | _____________ | Restrictivas / Moderadas / Permisivas |
| Número de construcciones nuevas | Aumenta / Disminuye | _____________ | Muchas / Moderadas / Pocas |
| **EFECTO NETO EN OFERTA:** | → → → | **Desplazamiento: Derecha / Izquierda / Estable** |

#### Parte B: Predecir Equilibrio del Mercado (5 min)

Basándote en tu análisis:

1. **Presión general del mercado:**
   - La demanda se está desplazando: ☐ Derecha (aumentando) ☐ Izquierda (disminuyendo) ☐ Estable
   - La oferta se está desplazando: ☐ Derecha (aumentando) ☐ Izquierda (disminuyendo) ☐ Estable

2. **Predicción de precio:**
   - Los precios probablemente: ☐ Subirán ☐ Bajarán ☐ Se mantendrán estables
   - Razonamiento: _______________________________________

3. **Condiciones del mercado:**
   - Actualmente: ☐ Mercado de vendedores (demanda > oferta) ☐ Mercado de compradores (oferta > demanda) ☐ Equilibrado

#### Parte C: Aplicación Personal (10 min)

**Escenario 1: Estás Planeando Alquilar**

Dadas las condiciones del mercado de {{STATE_NAME}}:

**Mejor Estrategia:**
- ☐ Firmar contrato ahora (precios subiendo, asegurar tarifa actual)
- ☐ Esperar (precios bajando, mejores ofertas por venir)
- ☐ Negociar (mercado equilibrado, hay apalancamiento)

**Razonamiento:** _______________________________________

**Escenario 2: Estás Planeando Comprar una Casa (en 5-10 años)**

**Preguntas de Planificación Financiera:**

1. **Trayectoria de precio:**
   - Si las casas en {{STATE_NAME}} actualmente cuestan {{STATE_MEDIAN_HOME_PRICE}}, ¿cuánto costarán en 5 años?
   - Asumiendo _____% de apreciación anual basado en tendencias de oferta/demanda
   - Estimación de precio futuro: $_______________

2. **Planificación de pago inicial:**
   - Pago inicial típico del 20%: $_______________
   - Ahorros mensuales necesarios para alcanzar esto en 5 años: $_______________

**Escenario 3: Estás Considerando Invertir en Bienes Raíces**

**Análisis de Inversión:**

1. **Análisis de flujo de caja (propiedad de alquiler):**
   - Precio de compra: {{STATE_MEDIAN_HOME_PRICE}}
   - Alquiler mensual esperado: {{STATE_MEDIAN_RENT}}
   - Pago hipotecario mensual (estimado): $_______________
   - Flujo de caja mensual neto: $_______________

---

### Actividad 2: Análisis del Mercado Laboral de {{STATE_NAME}} (15 minutos)

**Objetivo:** Usar oferta y demanda para tomar decisiones de carrera más inteligentes.

#### Parte A: Analizar Campos de Carrera en {{STATE_NAME}} (8 min)

**Elige 3 campos de carrera que te interesen. Investiga y completa la tabla:**

| Campo de Carrera | Factores de Demanda (↑/↓) | Factores de Oferta (↑/↓) | Perspectiva del Mercado | Salario Inicial en {{STATE_NAME}} | Salario a 10 Años |
|------------------|---------------------------|--------------------------|-------------------------|----------------------------------|-------------------|
| Ejemplo: Ingeniero de Software | Industria tech creciendo (↑), Trabajo remoto (↑) | Bootcamps de código (↑), Competencia (↑) | Demanda > Oferta = Salarios subiendo | $85,000 | $140,000 |
| 1. _____________ | | | | | |
| 2. _____________ | | | | | |
| 3. _____________ | | | | | |

**Preguntas de Análisis:**

1. **¿Qué carrera tiene la demanda más fuerte relativa a la oferta?**
   - Carrera: _______________________
   - Evidencia: _______________________
   - Trayectoria salarial esperada: _______________________

2. **¿Cómo puedes aumentar tu valor en el mercado laboral?**
   - Reducir oferta de "ti": Desarrollar habilidades raras, especialización
   - Aumentar demanda de "ti": Trabajar en industrias en crecimiento, networking, construir reputación
   - Tu estrategia: _______________________

#### Parte B: Análisis de Escenarios de Cambios del Mercado Laboral (7 min)

**Escenario 1: Revolución de IA**

La inteligencia artificial se vuelve altamente capaz, afectando muchos trabajos.

**Efectos en Demanda:**
- Demanda DISMINUYE para: Tareas rutinarias, entrada de datos, análisis básico, servicio al cliente
- Demanda AUMENTA para: Desarrollo de IA, gestión de IA, trabajo creativo, conexión humana, oficios especializados

**Estrategia de Carrera:**
- Evitar: Carreras fácilmente automatizables
- Perseguir: Carreras que requieren juicio humano, creatividad, habilidad física, inteligencia emocional
- En {{STATE_NAME}}, ¿qué carreras son resistentes a la IA? _______________________

**Escenario 2: Auge Económico de {{STATE_NAME}}**

La economía de {{STATE_NAME}} crece rápidamente (nuevas industrias, afluencia de población).

**Efectos en el Mercado Laboral:**
- La demanda de trabajadores aumenta en todos los sectores
- Los salarios suben
- El desempleo baja

**Tu Oportunidad:**
- Negociar salarios más altos (la demanda de trabajadores es fuerte)
- Cambiar de trabajo más fácilmente (los empleadores compiten por talento)
- Considerar emprendimiento (el mercado creciente crea oportunidades)

---

### Actividad 3: Elasticidad de Precio y Programación de Compras (10 minutos)

**Objetivo:** Comprender cuándo los precios son flexibles (elásticos) vs. rígidos (inelásticos), y usar esto para ahorrar dinero.

#### Parte A: Concepto de Elasticidad

**Elasticidad Precio de la Demanda:** ¿Qué tan sensible es la cantidad demandada a los cambios de precio?

**Demanda Elástica** (sensible al precio):
- Pequeño aumento de precio → Gran disminución en cantidad demandada
- Ejemplos: Bienes de lujo, bienes con muchos sustitutos, no esenciales
- **Implicación:** Los vendedores no pueden subir mucho los precios sin perder clientes

**Demanda Inelástica** (insensible al precio):
- Aumento de precio → Pequeña disminución en cantidad demandada
- Ejemplos: Necesidades, bienes con pocos sustitutos, productos adictivos
- **Implicación:** Los vendedores pueden subir precios sin perder muchos clientes

**Por Qué Esto Importa:**
- **Bienes elásticos:** Espera ofertas, negocia, encuentra alternativas
- **Bienes inelásticos:** Tienes menos apalancamiento; enfócate en reducir consumo

#### Parte B: Clasificar Bienes y Planificar Compras (10 min)

**Para cada categoría, identifica elasticidad y estrategia:**

| Compra | ¿Elástica o Inelástica? | Razonamiento | Estrategia para Ahorrar |
|--------|-------------------------|--------------|------------------------|
| **Gasolina** | Inelástica (corto plazo) | Necesitas llegar al trabajo/escuela; pocos sustitutos corto plazo | Reducir conducción, compartir auto, comprar auto eficiente largo plazo |
| **Boletos de concierto** | Elástica | Entretenimiento, muchas alternativas | Comprar temprano, esperar mercado de reventa, asistir shows menos populares |
| **Medicamentos recetados** | Inelástica | Necesidad médica | Usar genéricos, comparar farmacias, verificar cobertura de seguro |
| **Smartphone** | _____________ | | |
| **Libros de texto universitarios** | _____________ | | |
| **Alquiler de apartamento en {{STATE_NAME}}** | _____________ | | |
| **Comidas de restaurante** | _____________ | | |
| **Abrigo de invierno** | _____________ | | |

---

### Actividad 4: Herramienta Analizadora de Mercado - Skill Builder (10 minutos)

**Objetivo:** Usar herramienta interactiva para analizar mercados y hacer predicciones.

#### Elige un Mercado para Analizar:

☐ Mercado de vivienda de {{STATE_NAME}} (decisión comprar vs. alquilar)
☐ Mercado laboral de {{STATE_NAME}} (elección de carrera)
☐ Electrónica de consumo (timing de compra de teléfono, laptop)
☐ Mercado de autos usados (cuándo comprar)
☐ Otro: _______________________

#### Marco del Analizador de Mercado:

**Paso 1: Equilibrio Actual**
- Precio actual: $_______________________
- Descripción del mercado: _______________________

**Paso 2: Análisis de Demanda**
| Factor de Demanda | Efecto (↑/↓/→) | Fuerza (Baja/Med/Alta) |
|-------------------|----------------|------------------------|
| 1. _____________ | ______ | ______ |
| 2. _____________ | ______ | ______ |
| **Desplazamiento Neto de Demanda:** | **Derecha / Izquierda / Estable** | |

**Paso 3: Análisis de Oferta**
| Factor de Oferta | Efecto (↑/↓/→) | Fuerza (Baja/Med/Alta) |
|------------------|----------------|------------------------|
| 1. _____________ | ______ | ______ |
| 2. _____________ | ______ | ______ |
| **Desplazamiento Neto de Oferta:** | **Derecha / Izquierda / Estable** | |

**Paso 4: Predecir Nuevo Equilibrio**
- **El precio:** ☐ Aumentará ☐ Disminuirá ☐ Se mantendrá estable
- **La cantidad:** ☐ Aumentará ☐ Disminuirá ☐ Se mantendrá estable

**Paso 5: Decisión Personal**
- **¿Qué debes hacer?** _______________________
- **¿Cuándo debes actuar?** _______________________
- **Ahorros/ganancias potenciales:** $_______________________

---

## Resumen y Puntos Clave

### Lo Que Aplicamos Hoy:

✓ **Análisis del mercado de vivienda** - Comprender los factores de oferta y demanda de {{STATE_NAME}} ayuda a predecir precios y programar decisiones

✓ **Análisis del mercado laboral** - Las elecciones de carrera deben considerar el crecimiento de la demanda y las restricciones de oferta

✓ **Elasticidad** - Saber la sensibilidad al precio te ayuda a identificar dónde tienes poder de negociación

✓ **Timing del mercado** - Compra cuando la oferta es alta y la demanda es baja; evita precios pico

✓ **Monitoreo continuo** - Los mercados cambian; las decisiones financieras exitosas requieren análisis continuo

---

## Conexión al Próximo Capítulo

**Mañana: L-51 - Estructuras de Mercado y Elección del Consumidor**

Ahora que comprendes cómo funcionan la oferta y demanda en mercados competitivos, exploraremos:

- **¿Qué pasa cuando la competencia es limitada?** - Monopolios, oligopolios, competencia monopolística
- **Cómo la estructura del mercado afecta precios y calidad** - Más competencia = mejor para consumidores
- **Cómo identificar el poder de mercado** - Cuando los negocios pueden cobrar precios por encima del mercado
- **Estrategias del consumidor en diferentes estructuras de mercado** - Cómo obtener el mejor valor en cada tipo

**Pregunta de Vista Previa:**
- ¿Por qué Comcast cobra más de lo que cobraría un mercado competitivo?
- ¿Por qué solo hay 3 grandes operadores de telefonía celular?
- ¿Por qué las gasolineras en la misma esquina cobran precios similares?

Mañana comprenderás cómo la estructura del mercado moldea tus opciones como consumidor y cómo navegar cada tipo.

¡Nos vemos mañana!
