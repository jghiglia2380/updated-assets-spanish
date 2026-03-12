# L-54: Inflación, Desempleo y Finanzas Personales
## Día 2: Protegiéndote de la Inflación y el Desempleo - Laboratorio de Aprendizaje

> **Implementation Note:**
> Use the standardized header template (templates/student-header-template.html) for consistent styling.
> This includes:
> - Purple header with navigation menu (Home, Curriculum, Resources, Profile)
> - Left navigation with blue vertical indicators for active items and green checkmarks for completed items
> - Content styling using the standard component classes

### Objetivos de Aprendizaje
Al final del Laboratorio de Aprendizaje de hoy, podrás:
- Calcular valores reales vs. nominales y comprender la erosión del poder adquisitivo
- Desarrollar estrategias para protegerte contra la inflación (inversiones, negociaciones salariales, ajustes de gasto)
- Evaluar estrategias del mercado laboral para diferentes condiciones de desempleo
- Evaluar decisiones financieras personales en varios escenarios de inflación/desempleo

---

## Reflexión de Apertura (5 minutos)

**Escribe:** Piensa en una compra que hiciste o planeas hacer en los próximos 5-10 años (auto, casa, educación, etc.)

**Preguntas:**
- ¿Cuánto costará hoy?
- ¿Cuánto costará en 10 años con 3% de inflación anual?
- ¿Tu ingreso mantendrá el ritmo de la inflación?
- ¿Qué puedes hacer para protegerte?

Ten esto en mente mientras desarrollamos estrategias de protección contra la inflación.

---

## Actividades del Laboratorio de Aprendizaje

### Actividad 1: Cálculos de Valor Real vs. Nominal (15 minutos)

**Objetivo:** Calcular la erosión del poder adquisitivo y comprender los valores reales vs. nominales

---

#### Parte A: El Dólar que se Encoge (7 minutos)

**Escenario: Ahorras $10,000 debajo de tu colchón (ganando 0% de interés)**

**Calcula el poder adquisitivo futuro a diferentes tasas de inflación:**

| Años | Inflación 2% | Inflación 5% | Inflación 8% |
|------|--------------|--------------|--------------|
| 0 (hoy) | $10,000 | $10,000 | $10,000 |
| 5 años | $_______ | $_______ | $_______ |
| 10 años | $_______ | $_______ | $_______ |
| 20 años | $_______ | $_______ | $_______ |
| 30 años | $_______ | $_______ | $_______ |

**Fórmula:**
```
Valor Real = Valor Nominal / (1 + Tasa de Inflación)^Años

Ejemplo (2% de inflación, 10 años):
Valor Real = $10,000 / (1.02)^10 = $10,000 / 1.219 = $8,203
```

**Tus Cálculos:**

**Inflación del 2%:**
- 5 años: $10,000 / (1.02)^5 = $10,000 / 1.104 = $________
- 10 años: $10,000 / (1.02)^10 = $10,000 / 1.219 = $8,203
- 20 años: $10,000 / (1.02)^20 = $________
- 30 años: $10,000 / (1.02)^30 = $________

**Inflación del 5%:**
- 5 años: $10,000 / (1.05)^5 = $________
- 10 años: $10,000 / (1.05)^10 = $________
- 20 años: $10,000 / (1.05)^20 = $________
- 30 años: $10,000 / (1.05)^30 = $________

**Inflación del 8% (alta):**
- 5 años: $10,000 / (1.08)^5 = $________
- 10 años: $10,000 / (1.08)^10 = $________
- 20 años: $10,000 / (1.08)^20 = $________
- 30 años: $10,000 / (1.08)^30 = $________

**Ideas Clave:**

**Con inflación del 2% (meta de la Fed):**
- Después de 30 años, $10,000 valen solo $5,521
- Perdiste 45% del poder adquisitivo
- **Mantener efectivo es PERDER dinero**

**Con inflación del 5%:**
- Después de 30 años, $10,000 valen solo $2,314
- ¡Perdiste 77% del poder adquisitivo!

**Con inflación del 8%:**
- Después de 30 años, $10,000 valen solo $994
- ¡Perdiste 90% del poder adquisitivo!

**Preguntas de Análisis:**

1. **¿Cuál es el costo de oportunidad de mantener efectivo?**
   - _______________________________________________________

2. **¿Cuánto interés debes ganar para mantener el poder adquisitivo?**
   - Como mínimo: La tasa de interés debe igualar la tasa de inflación
   - 3% de inflación → Necesitas 3% de retorno para empatar
   - 5% de inflación → Necesitas 5% de retorno para empatar

3. **¿Qué pasa si tu salario solo crece 1% por año pero la inflación es del 3%?**
   - El salario real DISMINUYE 2% por año
   - Después de 10 años: Salario real = 98% × 10 = 82% del original
   - ¡Estás ganando 18% MENOS en poder adquisitivo!

---

#### Parte B: Ajuste Salarial por Inflación (8 minutos)

**Escenario: Te ofrecen un trabajo con salario que crece con el tiempo**

**Oferta 1:** $60,000 de salario inicial, aumento anual garantizado del 2%

**Oferta 2:** $55,000 de salario inicial, aumento anual garantizado del 4%

**Pregunta:** ¿Cuál es mejor si la inflación es del 3%/año?

**Calcula el Salario Real Después de 10 Años:**

**Oferta 1:**
- Salario nominal año 10: $60,000 × (1.02)^10 = $60,000 × 1.219 = $73,140
- Ajuste por inflación: / (1.03)^10 = / 1.344
- **Salario real año 10:** $73,140 / 1.344 = $54,420

**Oferta 2:**
- Salario nominal año 10: $55,000 × (1.04)^10 = $55,000 × 1.480 = $81,400
- Ajuste por inflación: / (1.03)^10 = / 1.344
- **Salario real año 10:** $81,400 / 1.344 = $60,565

**¿Cuál es Mejor?**
- ¡Oferta 2! A pesar del salario inicial más bajo, los aumentos del 4% superan la inflación
- Después de 10 años, la Oferta 2 proporciona $6,145 MÁS en poder adquisitivo real

**Tu Cálculo:**

**Tu salario inicial actual o esperado:** $__________

**Aumento anual esperado:** _____%

**Inflación esperada:** 3%

**Calcula el salario real en 10 años:**
1. Salario nominal: Inicial × (1 + aumento%)^10 = $________
2. Factor de inflación: (1.03)^10 = 1.344
3. Salario real: Nominal / 1.344 = $________

**Análisis:**
- ¿Tu salario real está creciendo o disminuyendo?
- Si aumento% < inflación%, estás perdiendo poder adquisitivo
- Si aumento% = inflación%, estás manteniendo el nivel
- Si aumento% > inflación%, estás ganando poder adquisitivo

**Idea Clave:** Enfócate en el crecimiento REAL del salario, no en aumentos nominales. Un aumento del 5% suena genial, pero si la inflación es del 7%, estás perdiendo 2% en poder adquisitivo.

---

### Actividad 2: Estrategias de Protección contra la Inflación (20 minutos)

**Objetivo:** Desarrollar una estrategia integral para protegerte contra la inflación

---

#### Parte A: Estrategias de Inversión (8 minutos)

**Tienes $10,000 para invertir. La inflación es del 3%/año. ¿Qué deberías hacer?**

**Opción 1: Efectivo/Cuenta de Ahorros**
- Tasa de interés: 0.5%/año
- Después de 10 años: $10,000 × (1.005)^10 = $10,511 (nominal)
- Ajustado por inflación: $10,511 / (1.03)^10 = $10,511 / 1.344 = $7,821
- **Resultado:** PERDISTE $2,179 en poder adquisitivo (-22%)

**Opción 2: Ahorros de Alto Rendimiento**
- Tasa de interés: 4.5%/año
- Después de 10 años: $10,000 × (1.045)^10 = $15,530 (nominal)
- Ajustado por inflación: $15,530 / 1.344 = $11,556
- **Resultado:** GANASTE $1,556 (+16%)

**Opción 3: Mercado de Valores (Promedio Histórico)**
- Retorno promedio: 10%/año (histórico)
- Después de 10 años: $10,000 × (1.10)^10 = $25,937 (nominal)
- Ajustado por inflación: $25,937 / 1.344 = $19,303
- **Resultado:** GANASTE $9,303 (+93%)
- **Riesgo:** Volátil, puede perder valor a corto plazo

**Opción 4: Bonos**
- Retorno promedio: 5%/año
- Después de 10 años: $10,000 × (1.05)^10 = $16,289 (nominal)
- Ajustado por inflación: $16,289 / 1.344 = $12,122
- **Resultado:** GANASTE $2,122 (+21%)
- **Riesgo:** Menor riesgo que acciones

**Opción 5: Bienes Raíces**
- Apreciación promedio: 4%/año (histórico)
- Después de 10 años: $10,000 × (1.04)^10 = $14,802 (nominal)
- Ajustado por inflación: $14,802 / 1.344 = $11,016
- **Resultado:** GANASTE $1,016 (+10%)
- **Además:** Ingresos por alquiler si es propiedad de inversión

**Opción 6: Valores del Tesoro Protegidos contra la Inflación (TIPS)**
- Retorno: Tasa de inflación + 0.5%
- Se ajusta automáticamente por inflación
- Después de 10 años: $10,000 × (1.035)^10 = $14,106 (nominal)
- ¡Ya ajustado por inflación! Valor real: $14,106 / 1.344 = $10,496
- **Resultado:** GANASTE $496 (+5%)
- **Beneficio:** Garantizado para superar la inflación (seguro)

**Tu Estrategia de Inversión:**

Asigna $10,000 entre las opciones:

| Inversión | Monto | Retorno Real Esperado (10 años) |
|-----------|-------|--------------------------------|
| Ahorros de alto rendimiento | $______ | × 1.156 = $______ |
| Acciones | $______ | × 1.930 = $______ |
| Bonos | $______ | × 1.212 = $______ |
| Bienes raíces | $______ | × 1.102 = $______ |
| TIPS | $______ | × 1.050 = $______ |
| **TOTAL** | **$10,000** | **$______** |

**Diversificación:**
- No pongas todos los huevos en una canasta
- Equilibra riesgo y retorno
- Más joven = puedes tomar más riesgo (acciones)
- Mayor = necesitas más estabilidad (bonos, TIPS)

**Ejemplo de Asignación (Edad 25):**
- Acciones: 60% ($6,000) → $11,580 valor real
- Bonos: 20% ($2,000) → $2,424
- TIPS: 10% ($1,000) → $1,050
- Ahorros de alto rendimiento: 10% ($1,000) → $1,156 (fondo de emergencia)
- **Total después de 10 años:** $16,210 (valor real)
- **Ganancia:** $6,210 (+62%)

**Idea Clave:** DEBES invertir para superar la inflación. El efectivo pierde valor. Un portafolio diversificado hace crecer la riqueza.

---

#### Parte B: Estrategia de Negociación Salarial (6 minutos)

**Escenario: Revisión anual de desempeño, hora de negociar un aumento**

**Aumento estándar:** 2% (apenas iguala la inflación)

**Tú quieres:** Aumento real (inflación + adicional)

**Negociación de Estrategia de Inflación:**

**Paso 1: Conoce los Números**
- Salario actual: $60,000
- Tasa de inflación actual: 3.5%
- Tu meta de aumento real: 2% (por encima de la inflación)
- **Aumento total necesario:** 3.5% + 2% = 5.5%

**Paso 2: Enmarca la Solicitud**

**Enfoque débil:**
"Me gustaría un aumento del 5.5%."

**Enfoque fuerte:**
"Dado que la inflación actualmente es del 3.5%, mi poder adquisitivo ha disminuido. Para mantener mi nivel de vida Y reconocer mis contribuciones [enumera logros], estoy solicitando un aumento del 5.5%. Esto representa un aumento real del 2% por encima de la inflación."

**Paso 3: Proporciona Evidencia**
- **Datos de inflación:** Reportes del IPC (datos oficiales del gobierno)
- **Tus contribuciones:** Cuantifica logros
  - "Aumenté ventas en 15%"
  - "Ahorré $20,000 al departamento"
  - "Lideré proyecto exitoso"
- **Datos del mercado:** "Roles similares en {{STATE_NAME}} pagan $65,000"

**Paso 4: Prepárate para Irte**
- Si la empresa no ajusta por inflación, considera buscar otro trabajo
- Cambiar de trabajo a menudo resulta en aumento del 10-20% (más que aumentos internos)
- La inflación hace que quedarse sea más costoso

**Tu Plan de Negociación:**

**Salario actual:** $__________

**Inflación actual:** _____%

**Aumento real deseado:** _____%

**Aumento total a solicitar:** _____% (inflación + aumento real)

**Tus logros clave a mencionar:**
1. _______________________________________________________
2. _______________________________________________________
3. _______________________________________________________

**Tu solicitud (escríbela):**
_______________________________________________________
_______________________________________________________
_______________________________________________________

**Plan de respaldo si te niegan:**
☐ Aceptar y buscar nuevo trabajo
☐ Pedir bono basado en desempeño
☐ Solicitar reevaluación en 6 meses
☐ Otro: _______________________

**Idea Clave:** Si no negocias ajustes por inflación, efectivamente estás aceptando un RECORTE salarial cada año. ¡Habla!

---

#### Parte C: Ajustes de Gasto (6 minutos)

**Ambiente de Alta Inflación: Cómo Ajustar el Gasto**

**Costos Fijos (Difíciles de Cambiar):**
- Alquiler/hipoteca
- Pago del auto
- Seguros
- Préstamos estudiantiles
- **Estrategia:** Fijar tasas cuando estén bajas (refinanciar antes de que suban las tasas)

**Costos Variables (Tú Controlas):**
- Comida
- Entretenimiento
- Ropa
- Suscripciones
- **Estrategia:** Cortar aquí durante alta inflación

**Estrategias de Gasto Anti-Inflación:**

**1. Comprar a Granel (No Perecederos)**
- Precios subiendo → Compra ahora antes de que suban más
- Artículos que no expiran: Papel higiénico, productos de limpieza, enlatados
- **Ahorros:** 10-20% comprando antes del próximo aumento de precio

**2. Genéricos/Marcas de Tienda**
- La prima de marca no vale la pena durante alta inflación
- Medicamentos genéricos: Mismo ingrediente activo, 70% más barato
- Alimentos de marca de tienda: A menudo mismo fabricante, 30% más barato

**3. Retrasar Compras de Lujo**
- Un auto nuevo puede esperar
- El teléfono más nuevo puede esperar
- Las vacaciones pueden ser modestas
- **Razón:** Los precios pueden estabilizarse o bajar después

**4. Acelerar Compras Necesarias**
- ¿Necesitas un electrodoméstico nuevo? Cómpralo antes del próximo aumento de precio
- ¿Necesitas reparaciones del auto? Hazlas ahora (precios de repuestos subiendo)
- ¿Planeas mejoras en casa? Fija cotizaciones ahora

**5. Auditoría de Suscripciones**
- Lista TODAS las suscripciones: Streaming, gimnasio, apps, etc.
- Cancela las que no uses
- **Hogar promedio:** $273/mes en suscripciones, solo usa la mitad

**6. Eficiencia Energética**
- Los servicios públicos suben con la inflación
- Bombillas LED, mejor aislamiento, termostato programable
- **Ahorros:** 15-25% en facturas de energía

**Tu Plan de Ajuste de Gastos:**

**Gasto mensual actual:** $__________

**Impacto de inflación (3% anual = 0.25% mensual):** +$________

**¿Dónde puedes cortar?**

| Categoría | Gasto Actual | Reducción | Nuevo Gasto |
|-----------|--------------|-----------|-------------|
| Suscripciones | $______ | $______ | $______ |
| Comer afuera | $______ | $______ | $______ |
| Entretenimiento | $______ | $______ | $______ |
| Ropa | $______ | $______ | $______ |
| Otro: _______ | $______ | $______ | $______ |
| **TOTAL** | **$______** | **$______** | **$______** |

**¿Compensas la inflación?** ☐ Sí ☐ No ☐ Parcialmente

---

### Actividad 3: Estrategias de Navegación del Desempleo (15 minutos)

**Objetivo:** Desarrollar estrategias del mercado laboral para diferentes condiciones de desempleo

---

#### Parte A: Análisis del Mercado Laboral por Tipo de Desempleo (7 minutos)

**Escenario 1: Desempleo Friccional (Búsqueda de Empleo Normal)**

**Condiciones:**
- Desempleo general: 4% (normal)
- Estás entre trabajos por elección o recién graduado
- Economía saludable

**Tu Estrategia:**

**1. Tómate Tu Tiempo (Pero No Demasiado)**
- Búsqueda promedio: 2-4 meses
- No te apresures a un mal ajuste
- Pero no seas demasiado exigente (costo de oportunidad de no ganar)

**2. Aprovecha la Red de Contactos**
- 70% de empleos se encuentran a través de networking
- LinkedIn, conexiones de exalumnos, antiguos colegas
- Entrevistas informativas

**3. Sé Estratégico**
- Apunta a industrias con crecimiento
- Habilidades que coincidan con requisitos laborales
- Ubicación con oportunidades

**4. Negocia Fuertemente**
- Tienes ventaja (economía buena)
- Pide salario ajustado por inflación
- Los beneficios también importan

**Cronograma:**
- Mes 1: Búsqueda activa, networking, aplicaciones
- Mes 2-3: Entrevistando, ofertas
- Mes 4: Aceptar posición
- **Ahorros necesarios:** 3-4 meses de gastos

---

**Escenario 2: Desempleo Estructural (Desajuste de Habilidades)**

**Condiciones:**
- Tu industria está en declive (automatización, outsourcing, cambio tecnológico)
- Existen empleos, pero requieren diferentes habilidades
- Necesitas recapacitación

**Tu Estrategia:**

**1. Evalúa Habilidades Transferibles**
- ¿Qué habilidades del trabajo anterior aplican al nuevo campo?
- Comunicación, gestión, habilidades técnicas
- Resalta estas en las aplicaciones

**2. Recapacitación/Desarrollo de Habilidades**
- Programas de colegios comunitarios
- Cursos en línea (Coursera, Udemy, bootcamps)
- Certificaciones (Google, AWS, gestión de proyectos)
- **Costo:** $1,000-15,000 (varía)
- **Tiempo:** 3-12 meses

**3. Apunta a Industrias en Crecimiento**
- Salud (población envejeciente)
- Tecnología (IA, ciberseguridad, ciencia de datos)
- Energía renovable
- Oficios (electricistas, plomeros - fuerza laboral jubilándose)

**4. Considera la Reubicación**
- Algunas regiones tienen más oportunidades
- {{STATE_NAME}} vs. otros estados
- Costo-beneficio: Salarios más altos vs. mayor costo de vida

**5. Temporal/Tiempo Parcial Mientras te Recapacitas**
- Sigue ganando durante la transición
- Construye nueva red de contactos
- Gana experiencia en nuevo campo

**Cronograma:**
- Mes 1-3: Evaluar opciones, inscribirse en capacitación
- Mes 4-12: Completar capacitación, trabajo de tiempo parcial
- Mes 13+: Búsqueda de empleo completa en nuevo campo
- **Ahorros necesarios:** 6-12 meses de gastos (o ingreso de tiempo parcial)

---

**Escenario 3: Desempleo Cíclico (Recesión)**

**Condiciones:**
- Desempleo 8-10% (recesión)
- Empresas despidiendo, congelamiento de contrataciones
- Pocas vacantes, muchos solicitantes

**Tu Estrategia:**

**1. Baja las Expectativas (Temporalmente)**
- Puede que necesites tomar trabajo por debajo de tu nivel de habilidad
- Aceptar salario más bajo de lo esperado
- **Razón:** Mejor que no tener trabajo, mantiene el currículum actualizado

**2. Maximiza los Beneficios de Desempleo**
- Solicita inmediatamente
- Típico: 50-70% del salario anterior por 26 semanas
- Extensiones durante recesiones severas
- Usa el tiempo para buscar empleo

**3. Trabajo Gig/Freelance**
- Uber, DoorDash, TaskRabbit
- Freelance en tu campo (Upwork, Fiverr)
- No es ideal, pero ingresos son ingresos

**4. Expande la Búsqueda Geográfica**
- Dispuesto a reubicarte por oportunidades
- Posibilidades de trabajo remoto
- Algunas regiones menos afectadas por la recesión

**5. Haz Networking Agresivamente**
- El mercado laboral oculto es aún más importante durante recesión
- La mayoría de empleos no se publican públicamente
- Las referencias personales importan más

**6. Mejora Habilidades Durante el Tiempo Libre**
- Tiempo libre durante la búsqueda de empleo
- Aprende nuevo software, certificación, habilidades
- Sal de la recesión más valioso

**7. Considera Volver a Estudiar**
- Las recesiones son buen momento para posgrado/capacitación
- Evita el mal mercado laboral por 1-2 años
- Emerge cuando la economía se recupere
- **Riesgo:** Deuda, costo de oportunidad

**Cronograma:**
- Meses 1-3: Búsqueda agresiva de empleo, solicitar desempleo
- Meses 4-6: Trabajo gig, continuar búsqueda, mejorar habilidades
- Meses 7-12: Considerar recapacitación si la recesión persiste
- **Ahorros necesarios:** 6-12 meses de gastos

---

#### Parte B: Plan Personal de Protección contra el Desempleo (8 minutos)

**Construye Tu Red de Seguridad:**

**1. Fondo de Emergencia**

**Meta:** 6 meses de gastos (3 meses mínimo)

**Tus gastos:** $________/mes

**Meta de fondo de emergencia:** $________ (6 meses)

**Ahorros actuales:** $________

**Brecha:** $________

**Ahorro mensual para alcanzar meta en 12 meses:** $________ / 12 = $________/mes

**Idea Clave:** El fondo de emergencia es la PRIMERA prioridad. Protege contra el desempleo.

---

**2. Portafolio de Habilidades**

**Tus habilidades actuales:**
1. _______________________
2. _______________________
3. _______________________

**Habilidades en demanda en {{STATE_NAME}}:**
- Consulta: BLS Occupational Outlook, Indeed, LinkedIn
- Identifica: ¿Qué habilidades están creciendo en tu campo?

**Habilidades a desarrollar en los próximos 2 años:**
1. _______________________ (Cómo: _______________, Cronograma: ________)
2. _______________________ (Cómo: _______________, Cronograma: ________)
3. _______________________ (Cómo: _______________, Cronograma: ________)

**El aprendizaje continuo previene el desempleo estructural.**

---

**3. Construcción de Red de Contactos**

**Tamaño actual de red profesional:** ________ personas

**Meta:** Agregar 20 conexiones significativas por año

**Estrategias:**
- ☐ Asistir a eventos de la industria
- ☐ Unirse a asociaciones profesionales
- ☐ Activo en LinkedIn (publicar, comentar, conectar)
- ☐ Entrevistas informativas
- ☐ Red de exalumnos
- ☐ Antiguos colegas/compañeros de clase

**Por qué:** 70% de empleos se encuentran a través de la red. Invierte en relaciones antes de necesitarlas.

---

**4. Flexibilidad Financiera**

**Reduce los costos fijos:**
- Alquiler/hipoteca alto = vulnerable durante desempleo
- Pago del auto = obligación fija
- Suscripciones = desperdicio si estás desempleado

**Regla:** Los costos fijos deben ser ≤50% del ingreso
- Deja espacio para cortar costos variables si es necesario

**Tus costos fijos:** $________ / mes

**Tu ingreso:** $________ / mes

**Porcentaje de costos fijos:** ________%

**¿Es esto sostenible si estás desempleado?** ☐ Sí ☐ No

**Si no, ¿qué puedes ajustar?**
_______________________________________________________

---

### Actividad 4: Análisis de Escenarios Económicos (5 minutos)

**Objetivo:** Tomar decisiones financieras informadas en diferentes condiciones económicas

**Tienes $25,000 para asignar. Elige estrategia basada en escenario económico:**

---

**Escenario 1: Alta Inflación (7%), Bajo Desempleo (3.5%)**

**Condiciones:**
- Precios subiendo rápidamente
- Empleos abundantes
- Tasas de interés altas (5%)

**Tu asignación:**
- Pagar deuda de alto interés: $________ (Tarjetas de crédito 18% → GRANDES ahorros)
- Invertir en acciones/bienes raíces: $________ (Supera la inflación)
- Ahorros de alto rendimiento: $________ (5% de retorno ayuda)
- TIPS (protegidos contra inflación): $________ (Garantizado para superar inflación)

**Razonamiento:**
- La inflación erosiona el valor del efectivo → Minimiza tenencias de efectivo
- Las tasas altas hacen costosa la deuda → Págala
- Necesitas inversiones que superen la inflación → Acciones, bienes raíces
- Seguridad laboral alta → Puedes tomar algo de riesgo

---

**Escenario 2: Baja Inflación (1%), Alto Desempleo (9%)**

**Condiciones:**
- Precios estables
- Empleos escasos, despidos comunes
- Tasas de interés bajas (1%)

**Tu asignación:**
- Fondo de emergencia (efectivo): $________ (Seguridad laboral BAJA, necesitas colchón)
- Pagar deuda: $________ (Sigue siendo buena idea, pero menos urgente)
- Inversiones conservadoras (bonos): $________ (Proteger capital)
- Mínimo en acciones: $________ (Riesgo de recesión)

**Razonamiento:**
- Riesgo de pérdida de empleo → Construye colchón de efectivo
- Recesión → Preserva capital, menos riesgo
- Baja inflación → El efectivo no pierde valor rápidamente
- Tasas de interés bajas → La deuda es barata, pero la seguridad importa más

---

**Escenario 3: Alta Inflación (6%), Alto Desempleo (8%) [Estanflación]**

**Condiciones:**
- Precios subiendo
- Empleos escasos
- Tasas de interés altas (6%)

**Tu asignación (DECISIONES DIFÍCILES):**
- Fondo de emergencia: $________ (Riesgo de desempleo ALTO)
- Pagar deuda de alto interés: $________ (Costosa en estanflación)
- Activos protegidos contra inflación: $________ (TIPS, commodities, bienes raíces)
- Mínimo en inversiones de crecimiento: $________ (Ambiente riesgoso)

**Razonamiento:**
- Necesitas efectivo para pérdida de empleo PERO el efectivo pierde valor por inflación
- Debes equilibrar seguridad y protección contra inflación
- La deuda de alto interés es asesina → Págala
- La estanflación es el peor ambiente → Estrategia defensiva

---

**Tu Escenario:**

**Condiciones económicas actuales:**
- Inflación: _____%
- Desempleo: _____%
- Tasas de interés: _____%

**Tu asignación de $25,000:**
| Uso | Monto | Razonamiento |
|-----|-------|--------------|
| Fondo de emergencia efectivo | $______ | |
| Pagar deuda | $______ | |
| Acciones | $______ | |
| Bonos | $______ | |
| TIPS | $______ | |
| Bienes raíces | $______ | |
| Otro: _______ | $______ | |
| **TOTAL** | **$25,000** | |

---

## Actividad de Cierre: Plan de Resiliencia Económica Personal (5 minutos)

**Reflexiona sobre tus estrategias:**

**1. Protección contra la Inflación:**

☐ **Inversión:** Portafolio diversificado que supera la inflación
☐ **Negociación Salarial:** Pedir aumentos ajustados por inflación
☐ **Gasto:** Ajustando por precios altos, cortando desperdicio

**Tu acción #1 de protección contra inflación en los próximos 3 meses:**
_______________________________________________________

---

**2. Protección contra el Desempleo:**

☐ **Fondo de Emergencia:** 3-6 meses de gastos ahorrados
☐ **Habilidades:** Aprendiendo continuamente, manteniéndote relevante
☐ **Red:** Construyendo conexiones profesionales
☐ **Flexibilidad:** Bajos costos fijos, adaptable

**Tu acción #1 de protección contra desempleo en los próximos 3 meses:**
_______________________________________________________

---

**3. Mayor Revelación de Hoy:**
_______________________________________________________

---

**4. ¿Cómo usarás este conocimiento?**

**En decisiones actuales:**
- ☐ Empezar a invertir para superar la inflación
- ☐ Negociar el próximo aumento agresivamente
- ☐ Construir fondo de emergencia
- ☐ Desarrollar habilidades en demanda
- ☐ Expandir red profesional

**Planificación a largo plazo:**
- ☐ Elegir campo profesional con potencial de crecimiento
- ☐ Vivir por debajo de tus medios para construir colchón
- ☐ Diversificar fuentes de ingreso
- ☐ Monitorear indicadores económicos

---

## Resumen y Puntos Clave

### Lo que Aplicamos Hoy:

✓ **Cálculos reales vs. nominales** - Comprendiendo la erosión del poder adquisitivo

✓ **Estrategias de inversión** - Superando la inflación a través de portafolio diversificado

✓ **Negociación salarial** - Pidiendo ajustes por inflación, no solo aumentos

✓ **Ajustes de gasto** - Adaptándose al ambiente de alta inflación

✓ **Navegación del desempleo** - Diferentes estrategias para desempleo friccional, estructural, cíclico

✓ **Planificación de escenarios económicos** - Tomando decisiones informadas basadas en condiciones

✓ **Resiliencia personal** - Construyendo redes de seguridad contra inflación y desempleo

### Conectando Conceptos:

**De L-48-53:**
- Los sistemas económicos experimentan ciclos (L-48)
- Costos de oportunidad en todas las decisiones (L-49)
- La oferta/demanda impulsan los precios (L-50)
- Las estructuras de mercado afectan el poder de fijación de precios (L-51)
- El gobierno interviene para estabilizar (L-52)
- Las herramientas de política fiscal/monetaria apuntan a inflación y desempleo (L-53)

**De L-54:**
- La inflación erosiona el poder adquisitivo - debes superarla invirtiendo
- El desempleo viene en diferentes tipos - requieren diferentes estrategias
- El intercambio de la Curva de Phillips significa que no puedes tener ambos bajos simultáneamente
- Las decisiones financieras personales deben adaptarse a las condiciones económicas

**Integración Clave:**
No puedes controlar la inflación o el desempleo, pero SÍ PUEDES controlar tu respuesta:
- Protegerte contra la inflación: Invertir, negociar, ajustar gasto
- Protegerte contra el desempleo: Fondo de emergencia, habilidades, red, flexibilidad
- Monitorear condiciones económicas y adaptar estrategias
- La resiliencia financiera viene de la preparación, no de la suerte

---

## Reflexión y Autoevaluación

**Responde individualmente:**

1. **Verificación de Comprensión:**
   - ¿Puedes calcular valores reales vs. nominales?
   - Califícate: 1 (no puedo hacerlo) a 5 (completamente confiado) _______

2. **¿Puedes desarrollar estrategias de protección contra la inflación?**
   - Califícate: 1 (no puedo hacerlo) a 5 (completamente confiado) _______

3. **Mayor sorpresa:**
   - ¿Qué aprendiste sobre protegerte?
   - _______________________

4. **¿Cambió tu enfoque?**
   - ¿Harás algo diferente basado en el análisis de hoy?
   - _______________________

5. **Acción personal:**
   - ¿Cuál es tu PRIMER paso la próxima semana?
   - _______________________

---

## Conexión al Próximo Capítulo

**Siguiente: L-55 - Comercio Internacional y Desarrollo Económico**

Ahora que comprendes los indicadores económicos domésticos, exploraremos:

- **Comercio internacional** - Importaciones, exportaciones, ventaja comparativa
- **Tipos de cambio** - Cómo las monedas afectan el comercio y los viajes
- **Globalización** - Cómo la economía internacional afecta tu empleo y compras
- **Desarrollo económico** - Por qué algunos países son ricos y otros pobres
- **Tu rol en la economía global** - Como consumidor, trabajador, inversionista

**Pregunta de Vista Previa:**
- ¿Debería EE.UU. comerciar libremente con todos los países o proteger las industrias nacionales?
- ¿Cómo afecta el comercio con China tus perspectivas laborales?
- ¿Es la globalización buena o mala para ti?

¡Nos vemos la próxima vez!
