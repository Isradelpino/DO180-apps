# openCert – Proof of Concept (CHG)

Este repositorio contiene la prueba de concepto de **openCert**, un marco basado en capacidades para la certificación de IA bajo el Reglamento Europeo de IA (AI Act).

## Contenido generado

| Ruta | Descripción |
|------|-------------|
| `ontology/` | Ontología RDFS/OWL de openCert (TTL, JSON‑LD, HTML). |
| `ns/context.jsonld` | Contexto JSON‑LD que incluye `eu-aiact`, `sector-infra` y `oc`. |
| `catalog/abbs/` | Architecture Building Blocks (ej. gobernanza de datos, calidad, seguridad). |
| `catalog/sbbs/` | Solution Building Blocks (implementaciones basadas en certificaciones CHG). |
| `docs/abbs/` | Documentación legible de los ABBs. |
| `docs/sbbs/` | Documentación legible de los SBBs. |
| `docs/ai-act-elements/` | Conceptos SKOS (medidas AESIA, amenazas). |
| `schemas/` | Esquema JSON de validación para SBBs. |
| `.htaccess` | Redirecciones para identificadores permanentes (w3id.org). |

## Vocabularios utilizados

- **`eu-aiact`** – Conceptos legales del AI Act (https://w3id.org/dpv/legal/eu/aiact)
- **`sector-infra`** – Propósitos sectoriales del DPV (https://w3id.org/dpv/sector/infra)
- **`oc`** – Extensiones propias de openCert (reusabilidad, tipos de organización)

## Licencia

Todos los archivos se publican bajo licencia MIT, salvo indicación contraria en cada archivo.

Generado automáticamente el 2026-03-16 18:37:54.
