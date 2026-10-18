[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Marco presupuestario unificado para lo personal y lo empresarial
### Separa el dinero personal del dinero empresarial sin perder la capacidad de tomar decisiones financieras integradas.

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Tool](https://img.shields.io/badge/Type-Decision%20Support-orange.svg)

**Un kit de herramientas gratuito para navegador y Excel que convierte las transacciones dispersas en un sistema operativo financiero estructurado—sin instalación, suscripciones ni software de contabilidad.**

**Sin registro. Sin instalación. Gratis en tu navegador.**

Prueba la versión de navegador gratis. Si necesitas la versión de Excel, puedes comprarla con una garantía de devolución de 30 días sin preguntas.
>
> 🌐 Abrir en el navegador → [Demo HTML en vivo](https://hyvoid.github.io/Personal-Business-Dual-Track-Budget-Manager/)  
> 📥 Descargar Excel → https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager/blob/main/Personal%20%26%20Business%20Unified%20Budget%20Framework.xlsx

---

## Lo que te ayuda a seguir

- El gasto personal frente a los costes operativos empresariales sin mezclar ambos.
- La rentabilidad real de la empresa después de los retiros del propietario.
- Los costes mínimos de subsistencia personal frente al gasto de estilo de vida discrecional.
- La deriva presupuestaria semanal antes de que el exceso de gasto se convierta en una sorpresa mensual.
- El margen de operación de la empresa y la capacidad de cubrir los compromisos próximos.
- El progreso del ahorro y la acumulación de activos junto al rendimiento operativo.

---

## Por qué construí esto

La mayoría de las pequeñas empresas y operadores independientes no fracasan por falta de registros de transacciones.

Fracasan porque no pueden interpretar correctamente esos registros.

Los gastos personales se filtran a las cuentas empresariales. Las ganancias de la empresa parecen mayores que la realidad porque se ignoran los retiros del propietario. La inflación del estilo de vida se esconde en docenas de pequeñas transacciones. [...]

La respuesta más común es no hacer nada o adoptar sistemas de contabilidad que resultan demasiado pesados para el uso diario.

Construí este marco después de ver repetidamente el mismo fracaso analítico:

> Se estaba siguiendo el dinero.
>
> No se estaban siguiendo las decisiones.

Por ejemplo:

**Antes**

Un propietario de negocio ve \$12,000 en el banco y concluye:

> "El negocio está saludable."

No existe distinción entre:

- las obligaciones operativas futuras,
- las necesidades de subsistencia personales,
- la rentabilidad de la empresa,
- los compromisos de ahorro.

Los retiros del propietario ocurren de forma aleatoria.

Los gastos personales ocasionalmente pasan por las cuentas de la empresa.

La cifra de efectivo disponible se vuelve engañosa.

**Después**

Los mismos \$12,000 se separan en:

- \$4,500 de obligaciones empresariales comprometidas,
- \$2,500 de asignación para retiro del propietario,
- \$2,000 de gastos de subsistencia personales,
- \$1,500 de presupuesto discrecional,
- \$1,500 de objetivo de ahorro.

La pregunta cambia de:

> "¿Cuánto dinero hay disponible?"

a:

> "¿Qué decisiones se pueden tomar con seguridad?"

Este libro de trabajo productiviza ese razonamiento.

No es un reemplazo de la contabilidad.

Es un marco de decisión reutilizable que hace visibles las compensaciones financieras antes de que los errores se acumulen.

---

## Problemas financieros comunes que resuelve

| Problema | Sin esta herramienta | Con esta herramienta |
|---|---|---|
| El dinero personal y empresarial se mezclan | La rentabilidad real se vuelve imposible de estimar | La separación de entidades preserva tanto la claridad como la flexibilidad |
| Los grandes saldos bancarios generan confianza falsa | Las obligaciones futuras permanecen invisibles | El efectivo se interpreta a través de los compromisos y el margen de operación |
| Los retiros del propietario ocurren de forma inconsistente | El gasto de estilo de vida desestabiliza las operaciones | Los retiros se vuelven intencionales y medibles |
| El exceso de gasto semanal pasa desapercibido | Los fracasos presupuestarios aparecen después de que termina el mes | Las alertas de umbral identifican la deriva pronto |
| Los objetivos de ahorro compiten con los gastos diarios | El ahorro solo ocurre cuando es conveniente | El ahorro se convierte en asignaciones explícitas |
| Las transacciones ambiguas se acumulan | La conciliación se vuelve dolorosa y tardía | Los elementos pendientes se resuelven durante revisiones semanales breves |

---

## Para quién es esto

Diseñado para:

- Freelancers que gestionan tanto los ingresos del negocio como los gastos personales.
- Propietarios de pequeñas empresas sin personal financiero dedicado.
- Consultores que operan mediante configuraciones bancarias simples.
- Emprendedores abrumados por registros de transacciones fragmentados.
- Personas que buscan claridad operativa en lugar de sistemas de contabilidad completos.

No diseñado para:

- Consolidaciones de empresas multi-entidad.
- Entornos ERP empresariales.
- Flujos de trabajo de contabilidad legal y presentación de impuestos.
- Equipos que requieren jerarquías de aprobación avanzadas.

No se necesita experiencia en hojas de cálculo.

Abre la versión de navegador y empieza a seguir de inmediato, o descarga la versión de Excel para tener control total.

---

## Acerca de

Construyo rastreadores ligeros y herramientas de apoyo a la decisión para situaciones con demasiadas piezas móviles para retenerlas de forma fiable en la memoria.

La pregunta detrás de cada herramienta es simple:

> ¿Qué información necesita existir en un solo lugar para tomar la próxima decisión con confianza?

Este marco aplica esa filosofía a las finanzas personales y empresariales. En lugar de reemplazar los sistemas de contabilidad, ayuda a revelar la información necesaria para operar de forma responsable entre grandes [...]

---

## Detalles técnicos

<details>
<summary>Para revisores técnicos, practicantes de Excel y colaboradores</summary>

---

### Arquitectura del libro de trabajo

| Capa | Función | Propósito |
|---|---|---|
| Captura de transacciones | Entradas e importaciones brutas | Almacena toda la actividad |
| Clasificación | Asignación de entidad y categoría | Preserva la integridad analítica |
| Validación | Revisión pendiente y controles | Reduce los errores de clasificación |
| Cálculos | Presupuestos y métricas financieras | Genera indicadores de decisión |
| Salidas | Paneles Pulse y resúmenes | Apoya las decisiones semanales |

Flujo de datos:

```text
Transactions
    ↓
Entity Classification
    ↓
Category Assignment
    ↓
Validation Checks
    ↓
Budget Calculations
    ↓
Pulse Indicators
    ↓
Decision Outputs
````

Dependencias de validación:

```text
Pending Transactions
        ↓
Weekly Review
        ↓
Approved Classification
        ↓
Financial Reporting
```

---

### Tres trampas que atrapan incluso a operadores experimentados

#### Trampa 1: el saldo bancario equivale al efectivo disponible

Se tomó una decisión.

Se aprobó el gasto de expansión.

La decisión se basó únicamente en el saldo bancario.

| Enfoque incorrecto             | Enfoque correcto             |
| -------------------------- | ---------------------------- |
| Usar el saldo total          | Deducir primero las obligaciones     |
| Ignorar los compromisos futuros  | Calcular el margen de operación |
| Tratar el efectivo como no restringido | Asignar por propósito          |

La falla:

El efectivo y el efectivo disponible no son idénticos.

Resultado corregido:

Las decisiones de expansión ocurren solo después de cubrir los gastos comprometidos.

<details>
<summary>Lógica de fórmula</summary>

```excel
Available Cash
=
Bank Balance
- Committed Expenses
- Planned Draws
```

</details>

---

#### Trampa 2: el gasto personal oculto dentro de los costes empresariales

Se tomó una decisión.

Se evaluó la rentabilidad.

Los gastos personales incrustados en las cuentas empresariales distorsionaron los márgenes.

| Enfoque incorrecto               | Enfoque correcto    |
| ---------------------------- | ------------------- |
| Transacciones mezcladas           | Separación de entidades   |
| Retiros estimados        | Retiro explícito del propietario |
| Gastos o ganancias inflados | Transferencias rastreables |

La falla:

Las entidades mezcladas destruyen la interpretabilidad.

Resultado corregido:

El rendimiento empresarial y el consumo personal se vuelven medibles de forma independiente.

<details>
<summary>Lógica de fórmula</summary>

```excel
Entity
=
Business
OR
Personal
OR
Owner Draw
```

</details>

---

#### Trampa 3: las revisiones mensuales detectan los problemas demasiado tarde

Se tomó una decisión.

El gasto de estilo de vida continuó sin cambios.

Los excesos presupuestarios se descubrieron después del hecho.

| Enfoque incorrecto             | Enfoque correcto             |
| -------------------------- | ---------------------------- |
| Descubrimiento mensual          | Revisiones Pulse semanales         |
| Sin umbrales de advertencia      | Indicadores tempranos             |
| Se requieren grandes correcciones | Pequeños ajustes son suficientes |

La falla:

Los bucles de retroalimentación llegaban demasiado lento.

Resultado corregido:

El exceso de gasto se vuelve manejable antes de que se acumule.

<details>
<summary>Lógica de fórmula</summary>

```excel
Discretionary Usage %
=
Actual Spend
/
Budget

Alert Trigger
=
Usage % > 85%
```

</details>

---

### Escenario de ejemplo

Un consultor termina la semana con:

| Entrada                    |  Importe |
| ------------------------ | ------: |
| Saldo de la cuenta empresarial | $12,000 |
| Costes SaaS próximos      |    $800 |
| Pagos a contratistas      |  $2,200 |
| Retiro planificado del propietario       |  $2,500 |
| Costes de subsistencia personales  |  $2,000 |
| Objetivo de ahorro           |  $1,500 |

Interpretación intermedia:

```text
Business Obligations
=
800 + 2,200
=
3,000

Remaining After Operations
=
12,000 − 3,000
=
9,000

Remaining After Draw
=
9,000 − 2,500
=
6,500

Remaining After Personal Allocation
=
6,500 − 2,000 − 1,500
=
3,000
```

Recomendación:

La empresa puede soportar las obligaciones planificadas y la compensación del propietario preservando al mismo tiempo los objetivos de ahorro.

Implicación de decisión:

El gasto discrecional adicional debe permanecer por debajo del colchón restante hasta que lleguen nuevos ingresos.

El saldo por sí solo no respondió a esta pregunta.

La asignación estructurada sí lo hizo.

---

### Referencia de fórmulas

<details>
<summary>Clasificación de entidades</summary>

Propósito:

Separar contextos analíticos.

```excel
Business
Personal
Owner Draw
```

</details>

<details>
<summary>Monitoreo del presupuesto</summary>

Propósito:

Detectar el exceso de gasto pronto.

```excel
Actual / Budget
```

Umbral:

```excel
>85%
```

</details>

<details>
<summary>Asignación de efectivo</summary>

Propósito:

Estimar la liquidez segura para la decisión.

```excel
Balance
− Obligations
− Planned Transfers
```

</details>

---

### Reglas de validación

| Campo                   | Regla                     | Comportamiento ante errores        |
| ----------------------- | ------------------------ | --------------------- |
| Entidad                  | Debe seleccionarse         | Marcar como pendiente       |
| Categoría                | Debe coincidir con la entidad        | Rechazar la clasificación |
| Importe                  | Numérico y distinto de cero     | Advertencia de entrada         |
| Fecha de transacción        | Obligatoria                 | Excluida de los informes |
| Retiro del propietario              | Debe puentear entidades     | Alerta de validación      |
| Umbral presupuestario        | Advertencia por encima del 85%        | Resaltar el exceso de gasto   |
| Varianza de conciliación | Varianza menor tolerada | Se requiere revisión       |

</details>

---

## Otras herramientas de esta serie

* **Previsión de inventario y planificación de reposición** — Determina el momento de reposición antes de que ocurran desabastecimientos.
* **Rastreador de apoyo a decisiones CRM** — Convierte la actividad de prospectos en decisiones de pipeline estructuradas.
* **Kit de planificación de gasto de proveedores** — Monitorea los compromisos frente a los presupuestos aprobados.
* **Rastreador de pulso financiero de proyectos** — Revela el riesgo de entrega mediante revisiones operativas ligeras.

Perfil de GitHub: *enlace de perfil*
Sitio web: [Visita nuestro sitio web](https://www.theseusworkshop.com/)

---

## Licencia

Este proyecto está licenciado bajo la **Apache License 2.0**.

Eres libre de usar, modificar y distribuir esta obra conforme a los términos de la Apache License 2.0. Consulta el archivo `LICENSE` para más detalles.
