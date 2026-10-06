# metadata

Microsoft Graph metadata — gehostet für den direkten Download und die Nutzung im Browser.

## Dateien

| Pfad | Beschreibung | Größe |
|------|-------------|-------|
| `openapi/v1.0/openapi.yaml` | OpenAPI Spezifikation v1.0 (stabil) | 42.3 MB |
| `openapi/beta/openapi.yaml` | OpenAPI Spezifikation beta (Preview) | 66.7 MB |
| `schemas/type-mappings/v1.0-entity-types.json` | Typ-Mappings (Entity-Typen) | 335 KB |

## URLs

Alle Dateien sind über `raw.githubusercontent.com` erreichbar (CORS: `*`):

```
https://raw.githubusercontent.com/qapdex-maker/metadata/main/openapi/v1.0/openapi.yaml
https://raw.githubusercontent.com/qapdex-maker/metadata/main/openapi/beta/openapi.yaml
https://raw.githubusercontent.com/qapdex-maker/metadata/main/schemas/type-mappings/v1.0-entity-types.json
```

## Nutzung

Die Dateien werden vom [Graph Metadata Hub](https://qapdex-maker.github.io/msgraph/react/) geladen. Der Worker liest die Specs als Text (`res.text()`), nie als Browser-Dokument — kein Freeze.

## Quelle

Die Dateien stammen aus dem [metadata-msgraph](https://github.com/qapdex-maker/metadata-msgraph) Repo (Fork von microsoftgraph/msgraph-metadata).
