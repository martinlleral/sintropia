# SintropIA

Sistema de observabilidad sintrópica que traduce procesos ecológicos complejos (sucesión, estratificación, poda, biomasa, pulso de luz) en datos estructurados, métricas accionables y visualizaciones útiles para la toma de decisiones de manejo agroforestal.

## Estado

MVP en implementación (Fase 1: Setup y diseño de base de datos).

## Problema que aborda

- La agroforestería sintrópica depende fuertemente del operador experto
- Baja estandarización de registros y métricas
- La ausencia de datos comparables impide entrenar modelos de IA, validar impacto y escalar conocimiento

## Hipótesis de trabajo

1. **Pulso de Luz**: La poda del estrato alto genera aumentos medibles de radiación en suelo que aceleran el crecimiento del estrato bajo
2. **Eficiencia Sistémica**: La relación biomasa producida / hora-hombre es un mejor KPI que el rendimiento aislado
3. **Low-tech confiable**: Protocolos simples y consistentes generan datos suficientes para análisis útiles en sistemas biodiversos

## Roadmap (MVP)

| Fase | Semanas | Entregable |
|------|---------|------------|
| Setup | 1-2 | DB en Notion, protocolos de medición, normalización espacial |
| Captura de datos | 3-8 | Registro sistemático de eventos, mediciones ambientales, documentación fotográfica |
| Análisis exploratorio | 9 | Cruce de variables, gráficos de correlación, patrones |
| IA Readiness | 10 | Dataset limpio y exportable, features clave definidas |

## Base de datos

Log de Sucesión Sintrópica en Notion con campos de:
- Identificación (evento, fecha, tipo)
- Ubicación espacial (línea sintrópica, cuadrícula 2D/3D, estrato)
- Especie y función ecológica
- Intervención (poda, plantación, cosecha, inputs)
- Medición ambiental (lux antes/después, humedad)
- Biomasa y producción (kg generados, destino, cosecha)

## Contexto

Agroforesta sintrópica periurbana en La Plata, Argentina.

## Roles demostrados

Business Analyst, Product Manager, Systems Thinker

## Autor

Martín Lleral - [GitHub](https://github.com/martinlleral)
