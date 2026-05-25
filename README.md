# RIPS Converter

Herramienta web gratuita para convertir paquetes **RIPS** (Registro Individual de Prestación de Servicios de Salud) de Colombia desde el formato legado TXT (Resolución 3374/2000) al formato JSON exigido por la Resolución 2275/2023 del MinSalud.

## Características

- Conversión TXT → JSON 2275 (consultas, procedimientos, urgencias, hospitalización, recién nacidos, medicamentos y otros servicios)
- Conversión bidireccional JSON ↔ Excel
- Bases maestras de diagnósticos y fechas de nacimiento
- Mapeos SISPRO validados y editables
- Bitácora de auditoría descargable
- Empaquetado ZIP automático por factura
- **100% offline**: procesa todo en su navegador, los datos clínicos nunca salen de su computador (cumple Ley 1581 / Habeas Data)

## Uso

Abra `index.html` en cualquier navegador moderno (Chrome, Edge, Firefox, Safari). No requiere instalación, servidor ni conexión a internet después de cargar la página.

## Despliegue

Este sitio está publicado con **GitHub Pages**. Cualquier cambio que se haga a `index.html` y se suba al repositorio queda en línea automáticamente en pocos minutos.

## Tecnología

HTML + JavaScript vanilla + [JSZip](https://stuk.github.io/jszip/) + [SheetJS](https://sheetjs.com/) — todo embebido en un solo archivo, sin backend.

## Normativa de referencia

- [Resolución 2275 de 2023](https://www.minsalud.gov.co/) — formato JSON vigente
- [Resolución 3374 de 2000](https://www.minsalud.gov.co/) — formato TXT anterior

---

© RIPS Converter. Herramienta de uso libre.
