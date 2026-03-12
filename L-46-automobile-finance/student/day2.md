# L-46: Finanzas Automotrices - Comprar vs. Arrendar - Laboratorio de Aprendizaje

> **Implementation Note:**
> Use the standardized header template (templates/student-header-template.html) for consistent styling.

## Resumen del Laboratorio de Aprendizaje
- **Capítulo L:** L-46: Finanzas Automotrices - Comprar vs. Arrendar
- **Duración:** 55 minutos
- **Enfoque:** Análisis práctico de escenarios reales de financiamiento de vehículos con herramientas de toma de decisiones
- **Formato de Aprendizaje:** 90% actividades, 10% facilitación y reflexión

## Materiales Necesarios
- Calculadora de Decisiones de Financiamiento Automotriz (accesible a través de la plataforma de aprendizaje)
- Datos de investigación de vehículos (acceso a internet)
- Calculadora de amortización de préstamos
- Hoja de trabajo de Matriz de Decisión de Financiamiento de Vehículos
- Hoja de trabajo de integración de presupuesto

## Preparación Antes de Clase
1. Completar la revisión de contenido del Día 1
2. Investigar un vehículo de interés (precio nuevo, precio usado, oferta de arrendamiento)
3. Traer información de presupuesto personal (si se siente cómodo compartiéndola)

## Actividades del Laboratorio de Aprendizaje

### Actividad 1: Desglose de Costos Reales de Vehículos (15 minutos)
**Objetivo:** Calcular el costo total REAL de propiedad más allá del precio de etiqueta

**Instrucciones:**
1. Seleccione uno de tres perfiles de vehículos proporcionados:
   - **Perfil A**: Honda Civic 2024 (Sedán compacto, $28,000 nuevo)
   - **Perfil B**: Toyota RAV4 2021 (SUV de tamaño mediano usado, $24,000)
   - **Perfil C**: Hyundai Elantra 2024 (Oferta de arrendamiento: $299/mes, 36 meses)

2. Usando la Calculadora de Costo Total, ingrese estos factores específicos del estado:
   - **Impuesto sobre ventas**: {{STATE_SALES_TAX}}% (tasa de su estado)
   - **Tarifas de registro/título**: Inicial ${{STATE_REGISTRATION_INITIAL}}, Anual ${{STATE_REGISTRATION_ANNUAL}}
   - **Seguro**: Investigue las tarifas típicas para su edad/ubicación en {{STATE_INSURANCE_COMPARISON_URL}} (promedio para adolescentes: ${{STATE_INSURANCE_AVG_TEEN}}/mes)
   - **Costos de combustible**: Calcule basándose en millas anuales según EPA × millas anuales ÷ mpg × ${{STATE_GAS_PRICE_CURRENT}}/galón
   - **Mantenimiento**: Use el cronograma del fabricante (típicamente $500-1000/año)

3. Calcule los totales de 6 años incluyendo:
   - Pagos de compra/arrendamiento
   - Impuesto sobre ventas y tarifas (una sola vez)
   - Renovaciones de registro (anual)
   - Seguro (anual, aumenta ~3% anualmente)
   - Combustible (anual, ajustado por inflación)
   - Mantenimiento programado
   - Reparaciones estimadas (aumentan a medida que el vehículo envejece)
   - Valor residual en el año 6

4. Cree un cálculo de costo por milla: Costo total de 6 años ÷ millas totales conducidas

5. Comparta hallazgos: ¿Qué perfil tiene el costo más bajo por milla? ¿Qué le sorprendió sobre el desglose del costo total?

### Actividad 2: Simulador de Decisión Comprar vs. Arrendar (20 minutos)
**Objetivo:** Experimentar la comparación financiera completa utilizando datos reales del mercado

**Instrucciones:**
1. Elija UN vehículo que le interese genuinamente (investigue los precios actuales)

2. Construya tres escenarios completos en la Calculadora de Decisiones de Financiamiento Automotriz:

   **ESCENARIO 1: Comprar Nuevo**
   - Precio de compra: [Su precio investigado]
   - Impuesto sobre ventas: {{STATE_SALES_TAX}}%
   - Registro: Inicial ${{STATE_REGISTRATION_INITIAL}}, Anual ${{STATE_REGISTRATION_ANNUAL}}
   - Pago inicial: 20% del precio de compra
   - Préstamo: 60 meses al {{STATE_AVG_AUTO_LOAN_RATE_NEW}}%
   - Seguro: Aproximadamente ${{STATE_INSURANCE_AVG_TEEN}}/mes (obtenga cotizaciones de {{STATE_INSURANCE_COMPARISON_URL}})

   **ESCENARIO 2: Comprar Usado (3 años de antigüedad)**
   - Precio de compra: [Investigue el mismo modelo, 3 años de antigüedad]
   - Impuesto sobre ventas: {{STATE_SALES_TAX}}%
   - Registro: Inicial ${{STATE_REGISTRATION_INITIAL}}, Anual ${{STATE_REGISTRATION_ANNUAL}}
   - Pago inicial: 15% del precio de compra
   - Préstamo: 48 meses al {{STATE_AVG_AUTO_LOAN_RATE_USED}}%
   - Seguro: Típicamente 10-15% más bajo que el vehículo nuevo (estime 85% de ${{STATE_INSURANCE_AVG_TEEN}})

   **ESCENARIO 3: Arrendar Nuevo**
   - MSRP: [Igual que Escenario 1]
   - Tarifa de adquisición: ${{STATE_LEASE_ACQUISITION_FEE}}
   - Reducción de costo capitalizado: $2,000
   - Arrendamiento: 36 meses, [investigue el factor de dinero actual]
   - Millas anuales: 12,000
   - Cargo por millas excesivas: $0.25/milla
   - Tarifa de disposición: $400 al final del arrendamiento

3. La calculadora muestra:
   - Pago mensual para cada uno
   - Desglose de costos año por año
   - Posición de equidad a lo largo del tiempo (saldo del préstamo vs. valor)
   - Costo neto total de 6 años
   - Punto de decisión: ¿Cuándo comprar supera a arrendar?

4. Agregue escenarios "qué pasaría si":
   - Escenario 3B: ¿Qué pasa si conduce 18,000 millas/año? (Agregue costos por exceso de millaje)
   - Escenario 1B: ¿Qué pasa si mantiene el auto comprado por 10 años en lugar de 6?
   - Escenario 2B: ¿Qué pasa si el auto usado necesita $2,500 en reparaciones inesperadas en el año 4?

5. Documente sus hallazgos:
   - ¿Qué escenario tiene el pago mensual más bajo? ¿Costo total más bajo?
   - ¿En qué punto el vehículo comprado se vuelve "gratis" (pagado) mientras el arrendamiento continúa?
   - ¿Cómo afectan las necesidades de millaje a la decisión?

### Actividad 3: Análisis del Impacto de los Términos del Préstamo (15 minutos)
**Objetivo:** Comprender cómo la duración del préstamo afecta tanto la flexibilidad como el costo total

**Configuración:** Está comprando un vehículo de $26,000 (después de intercambio/pago inicial) al {{STATE_AVG_AUTO_LOAN_RATE_NEW}}% (tasa promedio actual en {{STATE_NAME}})

**Instrucciones:**
1. Compare estas estructuras de préstamo utilizando el Analizador de Términos de Préstamo:
   - **Opción A**: 36 meses al 5.5% APR
   - **Opción B**: 60 meses al 6.0% APR
   - **Opción C**: 72 meses al 7.5% APR

2. Para cada opción, rastree:
   - Monto del pago mensual
   - Interés total pagado durante la vida del préstamo
   - Saldo del préstamo vs. valor del vehículo en los años 1, 2, 3, 4
   - "Período bajo el agua" (meses debiendo más de lo que vale)

3. Calcule el punto de equilibrio:
   - Si necesitara vender en el año 3, ¿qué opción le deja con equidad positiva?
   - ¿Cuánto extra paga en interés total por el préstamo de plazo más largo?
   - ¿Cuál es el ahorro mensual del préstamo más largo vs. el préstamo más corto?

4. Ejercicio de integración de presupuesto:
   - Si su pago mensual objetivo es $400, ¿qué términos de préstamo puede pagar?
   - Si pudiera pagar los pagos de la Opción A ($784/mes) pero eligió la Opción C ($390/mes), ¿qué podría hacer con la diferencia de $394?
     - ¿Pagar deuda de tarjeta de crédito?
     - ¿Construir un fondo de emergencia?
     - ¿Invertir para el retiro?
   - Use la Calculadora de Costo de Oportunidad: $394/mes invertidos durante 6 años al 7% de rendimiento = $34,785

5. Reflexión: ¿Cuándo está justificado un préstamo más largo a pesar del mayor costo total? ¿Cuándo debe evitarlo?

### Actividad 4: Estrategia Personal de Financiamiento de Vehículos (5 minutos)
**Objetivo:** Crear su marco de decisión personalizado

**Instrucciones:**
1. Complete la Matriz de Decisión de Financiamiento de Vehículos:

   **Sus Prioridades** (clasifique 1-5):
   - [ ] Pago mensual más bajo
   - [ ] Costo total más bajo
   - [ ] Siempre tener un vehículo más nuevo
   - [ ] Sin pagos de auto eventualmente
   - [ ] Flexibilidad para cambiar vehículos frecuentemente

   **Sus Circunstancias:**
   - Ingreso anual: $________
   - Ahorros actuales: $________
   - Millaje anual esperado: ________
   - Estabilidad profesional: Estable / Incierto / Cambiante
   - Rango de puntaje de crédito: Excelente / Bueno / Regular / En construcción

   **Factores Específicos del Estado:**
   - Costos de seguro en {{STATE_NAME}}: Promedio ${{STATE_INSURANCE_AVG_TEEN}}/mes para conductores jóvenes
   - Inspección de emisiones/seguridad: {{#if STATE_INSPECTION_REQUIRED}}Requerida (${{STATE_INSPECTION_COST}} anualmente){{else}}No requerida{{/if}}
   - Tasa de impuesto sobre ventas: {{STATE_SALES_TAX}}% (compare con estados vecinos al comprar vehículo)

2. Basándose en su análisis de las Actividades 1-3, identifique:
   - Enfoque recomendado: Comprar nuevo / Comprar usado / Arrendar
   - Pago mensual máximo asequible: $________
   - Rango de precio de vehículo objetivo: $________ a $________
   - Plan después del pago del préstamo: Conducir 5+ años más / Intercambiar / Otro

3. Establezca sus reglas personales:
   - "No financiaré un vehículo por más de ___ meses"
   - "No compraré un vehículo que cueste más del ___% de mi ingreso anual"
   - "Priorizaré [pago bajo / costo total bajo / confiabilidad / características]"

## Reflexión y Cierre (5 minutos)
1. Una idea clave de hoy: ¿Qué le sorprendió más sobre el análisis de costo total?
2. Una acción que tomará: ¿Qué hará diferente al adquirir su próximo vehículo?
3. Comparta con la clase: ¿Qué enfoque de financiamiento se alinea con SU etapa de vida actual y objetivos financieros?

## Conclusiones Clave
- El pago mensual es solo UNA pieza del costo total de propiedad
- Los factores específicos del estado (impuestos, registro, seguro) agregan miles al costo de los vehículos
- El plazo del préstamo afecta dramáticamente el interés total pagado y la posición de equidad
- Los años de conducción sin pagos después del pago del préstamo es donde ocurren los ahorros reales
- Sus circunstancias personales (ingresos, millaje, estabilidad) deben impulsar su decisión de financiamiento
- Comprender el costo de oportunidad ayuda a contextualizar el gasto en vehículos dentro de objetivos financieros más amplios
