# Liderazgo de Medición de Impacto en un Programa Social Complejo

**Rol ejercido:** Dueña de la estrategia de medición, documentación de datos y traducción de resultados para financiadores
**Sector:** Derechos Humanos / Protección de la niñez y juventud / Cooperación internacional
**Ubicación:** Quibdó, Chocó, Colombia
**Financiadores:** Embajada de Suiza (ejecución en curso) · propuesta en desarrollo para el Gobierno de Navarra

> *Nota de confidencialidad: por la naturaleza sensible de los casos documentados (homicidios de niños, niñas, adolescentes y jóvenes), este resumen omite nombres de víctimas, cuidadoras, colaboradores del equipo y números de contrato. Las cifras exactas se generalizan cuando es necesario para proteger la confidencialidad del proceso.*

---

## Contexto

Lideré el componente de documentación y monitoreo de una estrategia de acompañamiento psicosocial y defensa de derechos humanos dirigida a madres y cuidadoras de niños, niñas, adolescentes y jóvenes (NNAJ) víctimas de homicidio, en un contexto de conflicto armado urbano. Esto incluyó ser la persona responsable, dentro de la organización, de decidir qué se mide, cómo se mide, y cómo esos datos se convierten en información útil para el equipo interno, para un financiador internacional y para audiencias externas (autoridades, prensa, aliados).

No fue un rol de "correr los reportes" — fue definir la estrategia de medición desde cero, para un proyecto que no tenía un sistema de datos consolidado, y sostenerla en el tiempo con un equipo que no reportaba jerárquicamente a mí.

## Mi rol frente a los cinco ejes centrales del trabajo

**1. Estrategia y lineamientos de medición**
Diseñé desde cero qué se documenta, con qué instrumento, en qué momento del proceso y por qué — una ficha de 74 preguntas dividida en 7 secciones temáticas, más un sistema paralelo de monitoreo de los espacios de acompañamiento psicosocial. Identifiqué huecos metodológicos reales en el camino (por ejemplo: tipos de dato mal definidos que generaban errores de migración, lógica de guardado offline que fallaba silenciosamente) y corregí el diseño antes de que escalaran a un problema de calidad de datos.

**2. Implementación y seguimiento en campo**
Acompañé el despliegue del instrumento de documentación con el equipo de campo, revisando el estado de las fichas (completas, en proceso, que requieren revisión) y resolviendo cuellos de botella técnicos que afectaban la calidad y oportunidad del dato — incluyendo fallas de guardado que hacían parecer que un registro se había guardado cuando en realidad no llegó a la base de datos.

**3. Puente entre los datos y el resto de la organización**
Proceso y analizo los datos de forma autónoma (migración y limpieza con Python/pandas, estructuración de indicadores) y traduzco esos resultados en narrativas comprensibles para audiencias no técnicas: informes para el financiador, una propuesta técnica y financiera para un nuevo cooperante, y una estrategia de comunicación de prensa internacional. Mantengo un criterio explícito sobre qué se reporta como resultado consolidado, qué se presenta con matiz metodológico (por ejemplo, datos autorreportados sin triangulación externa) y qué todavía no está listo para reportarse.

**4. Relacionamiento con aliados y comunicación de resultados**
Diseñé el material de reporte diferenciado por audiencia: anexos técnicos como evidencia de capacidad instalada para un financiador nuevo, una matriz de indicadores para seguimiento periódico con el financiador actual, y una estrategia de incidencia mediática internacional con un pitch de prensa. Actualmente desarrollo el marco de indicadores (producto y resultado) que sostendrá la cadencia de reporte de la propuesta en curso.

**5. Coordinación interna sin autoridad jerárquica**
El equipo de campo (documentación, acompañamiento psicosocial, apoyo logístico) no reporta jerárquicamente a mí, pero dependía de que el diseño de instrumentos, la distribución de trabajo y los estándares de calidad estuvieran alineados entre todas las personas para que el dato fuera consistente. Distribuí la revisión de más de 140 casos migrados entre el equipo, definí estándares de documentación compartidos y sostuve la coherencia metodológica sin tener poder de gestión sobre las personas que ejecutaban el trabajo de campo.

## Uso de IA aplicada a medición y narrativa (MEL)

Ya utilizo IA como parte del flujo de trabajo de medición, no como reemplazo del criterio técnico:

- Transcripción y síntesis asistida de entrevistas de documentación de casos (actualmente vía carga manual de audio; en diseño un botón de síntesis directamente integrado a la herramienta de captura).
- Apoyo en la detección de inconsistencias durante la migración de datos históricos (valores fuera de vocabulario controlado, columnas desalineadas).
- Uso de IA para acelerar borradores de narrativas de impacto a partir de resultados técnicos — manteniendo siempre una revisión humana sobre qué se reporta y cómo se dice.

## Resultados destacados

- Sistema de documentación digital operativo (Power Apps + SharePoint + Power Automate), reemplazando un flujo basado en Excel propenso a errores.
- Más de 200 casos migrados y estandarizados hacia una base de datos centralizada.
- Matriz de indicadores de producto y resultado en desarrollo para una propuesta de expansión del proyecto, con línea base, meta y verificación definidas.
- Propuesta técnica y financiera completa presentada a un nuevo cooperante internacional, con anexos de metodología como evidencia de capacidad instalada.
- Estrategia de comunicación de resultados diferenciada por audiencia: financiador, prensa internacional, mecanismos de rendición de cuentas en derechos humanos.

## Ver los prototipos (datos 100% ficticios)

Para ilustrar cómo se ve el sistema completo sin exponer información real, construí una serie de prototipos con datos inventados:

| Prototipo | Qué ilustra |
|---|---|
| [`narrativa-impacto-onepager.html`](./narrativa-impacto-onepager.html) | El eje central del rol: mismo resultado, traducido para audiencia técnica vs. audiencia de financiador, con criterio explícito de qué se reporta / se separa / queda fuera |
| [`indicadores-marco-logico.html`](./indicadores-marco-logico.html) | Matriz de indicadores conectada al marco lógico: línea base, meta, avance |
| [`powerapps-mockup.html`](./powerapps-mockup.html) | Instrumento de captura de datos en campo |
| [`power-automate-flow.html`](./power-automate-flow.html) | Automatización del control de calidad y cierre de registros |
| [`powerbi-dashboard.html`](./powerbi-dashboard.html) | Panel analítico general del programa |
| [`lector-contexto.html`](./lector-contexto.html) | Prototipo en desarrollo: lectura de fuentes públicas (prensa, redes) para cruzar patrones territoriales con los casos documentados |

## Habilidades aplicadas

`Estrategia de medición e indicadores (MEL)` `Traducción de datos técnicos a narrativa` `Python (pandas)` `Power BI` `Power Apps` `SharePoint Online` `Power Automate` `Grant writing / redacción de propuestas` `Coordinación de equipos sin autoridad jerárquica` `IA aplicada a análisis y narrativa de impacto`

---

*Disponible para ampliar detalles metodológicos o técnicos en entrevista, respetando siempre la confidencialidad de las personas participantes.*
