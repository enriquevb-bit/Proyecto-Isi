# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | [dd/mm/aaaa] |
| Versión | [Versión de trabajo] |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como persona usuaria registrada, quiero tener la capacidad de aplicar criterios de búsqueda, para encontrar exactamente las recetas afines a los criterios aplicados.

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

Como criterios de búsqueda es una capacidad amplia, se necesita descomponer la épica en tres historias de usuario para especificar qué criterios de búsqueda se van a definir.

Se consideran la búsqueda por una palabra o frase (US-01), la búsqueda por ingredientes (US-02), y la exclusión de ingredientes (US-03).

## US-01

**Título:** Buscar mediante palabras clave

Como persona usuaria registrada, quiero tener la capacidad de buscar una receta mediante una palabra o frase clave, para encontrar sin necesidad de añadir más filtros las recetas que deseo ver.

**Fuentes:** UR-08; UC-21; FR-085; acta, Apartado 2 - Acuerdos, "La búsqueda por texto comprueba si la palabra o frase aparece en el título o en la descripción breve. Una frase debe aparecer seguida y en el mismo orden. No se distinguen mayúsculas ni tildes.".

### Criterios de aceptación

- **CA-01.** Dado una búsqueda por palabra clave, cuando se indique la palabra y se realice la búsqueda, entonces se mostrarán las recetas con esas palabras en el título o en la descripción breve.
- **CA-02.** Dado una búsqueda por frase clave, cuando se indique una frase de varias palabras y se realice la búsqueda, entonces se mostrarán únicamente las recetas en las que esas palabras aparezcan seguidas y en el mismo orden dentro del título o de la descripción breve.
- **CA-03.** Dado una búsqueda por palabra o frase clave, cuando se indique el término con o sin tildes y en mayúsculas o minúsculas y se realice la búsqueda, entonces se mostrarán las recetas coincidentes en el título o en la descripción breve sin distinguir mayúsculas ni tildes.

## US-02

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** [Capacidad]

Como [rol], quiero [capacidad], para [beneficio].

**Fuentes:** UR-08; UC-21; [FR principal]; acta, [apartado pertinente].

### Criterios de aceptación

- **CA-01.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
